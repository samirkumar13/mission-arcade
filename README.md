# Mission Arcade

Mission Arcade is a lightweight, gamified daily task board that turns your to-do list into a quest system.
Complete tasks, earn XP, rank up, and keep momentum through a clean interface designed for everyday use.

## Live Demo
- GitHub Pages: `https://samirkumar13.github.io/mission-arcade/`

## Features
- XP-based progress system with rank levels
- Add custom tasks with custom XP values
- Mark tasks as completed and undo completion anytime
- Boss-task flag for high-impact tasks
- Delete tasks instantly
- Auto-save progress in browser storage (`localStorage`)
- Export memory to JSON and import it on another device/browser

## Tech Stack
- HTML
- CSS
- Vanilla JavaScript
- GitHub Pages (for hosting)

## Project Structure
- `index.html`: production entry for GitHub Pages
- `mission_arcade.html`: editable working version
- `.github/workflows/deploy-pages.yml`: GitHub Actions workflow for Pages deploy

## Getting Started (Local)
1. Clone the repository:
   - `git clone https://github.com/samirkumar13/mission-arcade.git`
2. Open the project folder.
3. Launch `index.html` in any modern browser.

No build step or dependencies are required.

## Persistence Model
- **Automatic persistence:** Data is saved automatically in your current browser using `localStorage`.
- **Cross-device transfer:** Use:
  - `Export Memory` to download `mission-arcade-memory.json`
  - `Import Memory` on another device/browser to restore progress

## Deployment (GitHub Pages)
This project is configured to deploy via GitHub Actions.

1. Push changes to `main`
2. Go to `Settings -> Pages`
3. Set **Build and deployment Source** to **GitHub Actions**
4. Wait for the workflow in the `Actions` tab to complete

## Future Scope
- User accounts + cloud sync (true persistent memory across all devices without manual export/import)
- Task categories, tags, and filters
- Recurring tasks (daily/weekly quests)
- Streaks, achievements, and badges
- Difficulty modes with dynamic XP balancing
- Rich analytics dashboard (focus trends, completion rates, XP velocity)
- Dark/light theme toggle and theme presets
- Drag-and-drop task ordering
- PWA support (installable app + offline mode)
- Optional reminders/notifications
- Data encryption for exported backups

## Contributing
Suggestions and pull requests are welcome.
If you have ideas for gameplay, UI polish, or productivity features, open an issue.

## License
MIT (recommended to add a `LICENSE` file if you want formal open-source usage terms).
