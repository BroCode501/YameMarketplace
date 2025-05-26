# Yame Themes and Extensions Repository

Welcome to the Yame Marketplace repository! This project serves as a central hub for discovering, sharing, and listing stylesheets (themes) and scripts (extensions) for the Yame Markdown Editor.

## Purpose
This repository is designed to make it easy for users and developers to:
- Discover new extensions and themes for Yame.
- Share their own ESM modules (scripts) and stylesheets (themes) with the community.
- Browse a curated, community-driven list of resources for enhancing the Yame Markdown Editor experience.

## How It Works
- **Extensions** are listed in the `ext-list.json` file.
- **Themes** are listed in the `ext-styles.json` file.
- The [Yame Marketplace website](index.html) (powered by this repo) fetches these lists and displays them in a beautiful, searchable UI.
- Each entry includes a name, description, URL, entrypoint, and optional image/icon.

## Contributing
We encourage everyone to contribute their own extensions and themes! To add your resource:
1. **Host your script or stylesheet in a public GitHub repository.**
   - This makes it easy for others to discover, use, and update your work.
2. **Add an entry to the appropriate JSON file:**
   - For extensions, edit `ext-list.json`.
   - For themes, edit `ext-styles.json`.
   - Each entry should include:
     - `name`: The display name of your extension/theme.
     - `description`: A short summary of what it does.
     - `url`: The GitHub repository URL.
     - `entrypoint`: The main JS or CSS file (relative to the repo root).
     - `image` (optional): A logo or icon for your extension/theme.
3. **Submit a pull request.**
   - Please ensure your entry is accurate and your resource is publicly accessible.

## Why Host Separately?
We recommend hosting your scripts and stylesheets in separate GitHub repositories. This approach:
- Makes it easier for others to contribute, fork, and update your work.
- Keeps the marketplace clean and focused on listing and discovery.
- Allows for better versioning and issue tracking.

## Using the Marketplace
- Visit the [Yame Marketplace](index.html) to browse and search for available extensions and themes.
- Click on any card to view details, copy the entrypoint URL, and read the README directly from the GitHub repo.
- Use the dark mode toggle for a comfortable browsing experience.

## License
This repository is open source and contributions are welcome. Please see individual extension/theme repos for their respective licenses.

---

For more information, see the [README](README.md) in this repository or open an issue if you have questions or suggestions.