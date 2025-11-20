# My Markdown Editor

A featu re-rich markdown editor built on Toast UI Editor with full dark mode support.

## Features

- **Rich Markdown Editing**: WYSIWYG and markdown modes powered by Toast UI Editor
- **Dark Mode**: Three theme options (light, dark, system) with persistent preferences
- **Code Syntax Highlighting**: Prism.js integration for beautiful code blocks
- **File Management**: Create, switch, and organize multiple markdown files
- **Smart Code Block Escape**: Context-aware feature to break out of code blocks
- **Local Storage**: All files saved automatically in your browser
- **Import/Export**: Download files as .md or import existing markdown files
- **Drag & Drop Reordering**: Organize your files with ease

## Usage

Simply open the editor in your browser - no installation or setup required. All files are stored locally in your browser's localStorage.

### Theme Switching
Click the theme button in the header to cycle through:
- Light mode
- Dark mode
- System (follows your OS preference)

### File Management
- **New File**: Click the "New File" button in the sidebar
- **Switch Files**: Click any file in the sidebar to switch to it
- **Delete File**: Click the trash icon next to a file
- **Auto-naming**: Files are automatically named from the first H1 header in your content

### Import/Export
- **Export**: Click the download button to save the current file as .md
- **Import**: Click the upload button to import a markdown file

## Technical Details

- Single-file HTML application (no build process required)
- Uses Toast UI Editor for markdown editing
- Prism.js for syntax highlighting
- Font Awesome for icons
- Google Fonts: Inter (UI) and JetBrains Mono (code)

## License

Free to use and modify.
