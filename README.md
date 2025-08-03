# Smart Bookmarks Manager

A clean, drag-and-drop bookmark organizer with archive functionality.

## Features

- **Card-based Organization** - Group bookmarks into customizable cards
- **Drag & Drop Interface** - Reorder bookmarks and cards with intuitive drag and drop
- **External Link Support** - Drop links directly from your browser into cards
- **Archive System** - Deleted bookmarks are automatically archived (500 item limit)
- **Search & Filter** - Find bookmarks across all cards
- **XML Import/Export** - Backup and restore your bookmark collections
- **Responsive Design** - Works on desktop and mobile devices

## Technical Approach

**Single-File Architecture**: Complete application in one HTML file with embedded CSS and JavaScript.

**Event Delegation**: Clean drag-and-drop system using a single event router to handle all interactions without duplicate listeners.

**Local Storage**: Data persisted in browser's localStorage as XML format for easy backup and portability.

**Modern Web Standards**: Built with vanilla JavaScript, CSS Grid/Flexbox, and HTML5 Drag & Drop API.

## Usage

1. Open `bookmark-manager.html` in your browser
2. Create cards to organize your bookmarks
3. Drag links from your browser to the "Drop links here" zones
4. Use drag and drop to reorder bookmarks and cards
5. Switch to Archive tab to view deleted bookmarks

## File Structure

```
smart-bookmarks/
├── bookmark-manager.html    # Complete application
└── README.md               # This file
```

No build process or dependencies required - just open the HTML file. 