# Markdown Notes

Markdown Notes is a lightweight, browser-based note-taking application that supports Markdown formatting, image embedding, and multi-note management. It is designed to work entirely offline using local browser storage.

## Features

- Create and manage multiple notes
- Markdown support with live preview
- Paste images directly into notes
- Images are stored and referenced per note
- Automatic saving of content
- Per-tab state preservation (active note, cursor position, UI state)
- Collapsible sidebar
- Inline note renaming (double-click)
- Works without any backend

## How It Works

All data is stored locally in the browser:

- Notes and images are stored using `localStorage`
- UI state (active note, sidebar state, cursor position) is stored using `sessionStorage`

Each browser tab maintains its own independent UI state.

## Usage

1. Open the application in your browser
2. Create a new note using the sidebar
3. Write Markdown in the editor
4. Paste images directly into the editor
5. Use the preview panel to view rendered output

## Deployment

This project can be deployed easily using GitHub Pages:

1. Upload the `index.html` file to a public repository
2. Enable GitHub Pages in repository settings
3. Access the app via the provided GitHub Pages URL

## Limitations

- Data is stored locally and is not synced across devices
- Clearing browser storage will remove all notes
- Image storage is limited by browser storage capacity (~5MB)
- No collaboration or sharing features

## Future Improvements

- Export and import notes as Markdown files
- Search across notes
- Drag and drop image support
- Improved editor with block-based structure

## License

This project is open source and available for personal and educational use.
