# Sudoku Prime — No Ads

A clean, ad-free Sudoku game for iOS with multiple difficulty levels, hints system, and a polished SwiftUI interface.

<!-- <p align="center">
  <img src="screenshots/screenshot1.png" width="200">
  <img src="screenshots/screenshot2.png" width="200">
  <img src="screenshots/screenshot3.png" width="200">
</p> -->

## Tech Stack

| Layer | Technology |
|-------|-----------|
| **UI** | SwiftUI |
| **Data** | SwiftData |
| **Game Logic** | Custom Sudoku generator & solver |
| **Payments** | RevenueCat (hint packs) |
| **Architecture** | MVVM |

## Key Features

- **No Ads** — Completely ad-free experience
- **Multiple Difficulties** — Easy, Medium, Hard, and Expert puzzles
- **Smart Hints** — Purchasable hint packs (3-pack and 10-pack) + unlimited hints option
- **Notes Mode** — Pencil marks for candidate tracking
- **Error Highlighting** — Real-time conflict detection
- **Game Statistics** — Track completion times and solve rates
- **Auto-Save** — Resume any game where you left off

## Architecture

```
SudokuPrime/
├── Models/          # Board, Cell, Game state
├── Views/           # SwiftUI game board, controls, settings
├── ViewModels/      # Game logic, puzzle generation, validation
├── Services/        # RevenueCat, statistics tracking
└── Utils/           # Sudoku algorithms, timer
```

## Links

- [Home](https://peretz2.github.io/SudokuPrime)
- [Support](https://peretz2.github.io/SudokuPrime/support.html)
- [Privacy Policy](https://peretz2.github.io/SudokuPrime/privacy.html)
- [Terms of Use](https://peretz2.github.io/SudokuPrime/terms.html)
