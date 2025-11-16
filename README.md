# Nine by Nine

A fully-featured Sudoku game built with vanilla JavaScript - no libraries, just clean code and smooth gameplay.

**Play now:** [brianjgoodwin.github.io/nine_by_nine](https://brianjgoodwin.github.io/nine_by_nine/)

## What

Nine by Nine is a complete Sudoku implementation designed for both casual players and puzzle enthusiasts. Built with accessibility in mind, it features multiple difficulty levels, smart hints, comprehensive keyboard controls, and high contrast mode.

Created as part of a portfolio of simple, thoughtful web applications and specifically built with my dad in mind - a solid alternative to daily Sudoku apps with a cleaner, more focused experience.

## Tech Stack

- **Frontend:** Vanilla HTML, CSS, and JavaScript
- **Storage:** Browser LocalStorage (for game state, high scores, and settings)
- **Hosting:** GitHub Pages
- **Dependencies:** None

Zero libraries or frameworks - just well-structured, readable vanilla JavaScript. The entire game lives in a single HTML file for maximum simplicity.

## Setup & Run

### Running Locally

Simply open `index.html` in any modern web browser. No server, build process, or installation required.

```bash
# Clone the repository
git clone https://github.com/brianjgoodwin/nine_by_nine.git
cd nine_by_nine

# Open in browser (macOS example)
open index.html

# Or just double-click index.html in your file browser
```

## Deployment

### GitHub Pages

The game is deployed via GitHub Pages and automatically updates when changes are pushed to the main branch.

**Live URL:** [https://brianjgoodwin.github.io/nine_by_nine/](https://brianjgoodwin.github.io/nine_by_nine/)

To deploy your own version:
1. Fork the repository
2. Enable GitHub Pages in repository settings
3. Select the branch to deploy (typically `main`)

## Status

**Actively maintained** (low priority) - Live at [brianjgoodwin.github.io/nine_by_nine](https://brianjgoodwin.github.io/nine_by_nine/)

Repository: [github.com/brianjgoodwin/nine_by_nine](https://github.com/brianjgoodwin/nine_by_nine) (public)

## Features

### Core Gameplay
- **Three difficulty levels** - Easy, Medium, and Hard with appropriate puzzle generation
- **Smart puzzle generation** - Ensures exactly one valid solution per puzzle
- **Auto-save** - Never lose progress, game state automatically saves
- **Resume capability** - Pick up right where you left off

### Player Tools
- **Notes mode** - Mark potential candidates in cells
- **Hint system** - Two-tier hints (basic and advanced)
- **Undo function** - Revert mistakes (up to 100 moves)
- **Pause/Resume** - Pause with board blur for fair timed play
- **Timer** - Optional timed mode for competitive play
- **Error detection** - Automatic conflict highlighting

### Accessibility & UX
- **High contrast mode** - Enhanced visibility with system preference detection
- **Keyboard navigation** - Full keyboard support (arrows, digits, shortcuts)
- **Touch-optimized** - On-screen numpad for mobile devices
- **Print support** - Print puzzles for offline solving
- **Celebration animation** - Confetti burst on completion (respects reduced motion)
- **Responsive design** - Works seamlessly on desktop, tablet, and mobile

### Data & Progress
- **High score tracking** - Local leaderboard with completion times
- **Game statistics** - Track your solving performance
- **Persistent settings** - Preferences saved across sessions

### Keyboard Shortcuts
- **1-9**: Place digits
- **Backspace/Delete**: Erase cell
- **Arrow keys**: Navigate grid
- **N**: Toggle notes mode
- **H**: Get hint
- **Shift+H**: Show all candidates for selected cell
- **U**: Undo last move
- **P**: Pause/Resume

## Notes

This project demonstrates that you don't need heavy frameworks to build polished, feature-rich applications. The focus is on:
- **Clean, readable code** - Easy to understand and modify
- **Performance** - Fast puzzle generation and smooth interactions
- **Accessibility** - Keyboard controls, high contrast, reduced motion support
- **User experience** - Thoughtful features that enhance gameplay without complexity

Built primarily for family use (my dad's daily Sudoku fix) and as a portfolio piece showcasing vanilla JavaScript capabilities. Part of an ongoing series of simple, focused web applications.

The entire game is self-contained in a single HTML file, making it incredibly portable and easy to host anywhere.