# IRR Safehouse Tracker

A standalone, offline-first browser-based tracker for managing safehouse/hideout upgrades in **Into the Radius Reloaded (IRR)**.

## Features

- Track multiple stations and their upgrade levels
- Mark individual levels as Pending / In Progress / Completed
- Track required items and collected quantities per level
- Filter and sort stations/levels
- Add notes to levels and stations
- Progress bars and summary stats in the header
- Collapsible station rows
- All data stored locally in the browser (localStorage) — no server required

## Usage

1. Open `037 safehouse-tracker.html` directly in any modern browser.
2. No installation, build step, or internet connection required.
3. Use the **+ Add Station** button to create a new station.
4. Expand a station to view its upgrade levels and manage items.
5. Click a status badge to cycle through statuses: `Pending → In Progress → Completed`.
6. Data is saved automatically to `localStorage` in your browser.

## Data Persistence

Progress is saved to your browser's `localStorage`. To avoid data loss:

- Do **not** clear your browser's site data for this file.
- Use the **Export** button (if available) to back up your data as JSON.
- To transfer progress to another device, export and re-import the JSON.

## File Structure

```
037 safehouse-tracker.html   # Self-contained app (HTML + CSS + JS)
```

## Browser Support

Works in any modern browser (Chrome, Firefox, Safari, Edge). No extensions or plugins needed.

## License

Personal use project. Not affiliated with the developers of Into the Radius.
