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

1. Open `safehouse-tracker.html` directly in any modern browser.
2. No installation, build step, or internet connection required.
3. Use the **+ Add Station** button to create a new station.
4. Expand a station to view its upgrade levels and manage items.
5. Click a status badge to cycle through statuses: `Pending → In Progress → Completed`.
6. Data is saved automatically to `localStorage` in your browser.

## Data Persistence

Progress is saved to your browser's `localStorage`. To avoid data loss:

- Do **not** clear your browser's site data for this file.
- Use the **Export** button to back up your data as JSON.
- To transfer progress to another device, export and re-import the JSON.

## File Structure

```
safehouse-tracker.html   # Self-contained app (HTML + CSS + JS)
LICENSE                  # CC BY-NC-SA 4.0
README.md
```

## Browser Support

Works in any modern browser (Chrome, Firefox, Safari, Edge). No extensions or plugins needed.

## License

This project is licensed under the **Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0)** license. See [LICENSE](LICENSE) for the full text.

**In short:**
- You may use, copy, and adapt this project freely in your own repository.
- **Attribution is mandatory** — you must credit the original repository and author.
- **No commercial use** — you may not use this for commercial purposes.
- **Share-Alike** — any derivative work must be published under the same CC BY-NC-SA 4.0 license.

**Disclaimer:** This is an independent, fan-made tool. The author is NOT affiliated with, endorsed by, or connected to the developers of Incursion Red River or any related studio or publisher.

## Credits

Created and maintained by **[TmYNooB](https://github.com/TmYNooB)**.
Original repository: **https://github.com/TmYNooB/IRR-HideoutTracker**

If you fork or build upon this project, please credit the original repository as required by the [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/) license.
