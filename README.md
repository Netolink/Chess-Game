# Chess Arena featuring Stockfish.JS WASM Engine

A sleek, highly responsive chess client running entirely in the browser. It features real-time AI-powered analysis, a highly accurate engine evaluation bar, seamless dark/light modes, and granular match configuration options.

---

## 🎨 Key Features

- **In-Browser Stockfish AI**: Play against the world's strongest chess engine running locally inside your browser via high-performance WebAssembly (WASM) technology.
- **Live Engine Evaluation**: A dynamic, responsive visual slider that calculates and updates current position advantages (Centipawns) on every move.
- **Polished Responsive Interface**: A clean, modern board layout with support for responsive screens, drag-and-drop moves, move highlighting, and check warning signals.
- **Light & Dark Themes**: Fully supported visual presets accessible via a single header toggle button, adjusting colors, backgrounds, and text for optimal day or night contrast.
- **Comprehensive Match Settings**:
  - Adjustable engine calculation limits (optimized to a default of **1.2 seconds**).
  - Time controls supporting Bullet, Blitz, Rapid, Classical, or casual unlimited play.
  - 20 distinct AI strength levels catering to all players—from beginners to Grandmaster status (2800+ ELO).
- **Notation & Importers**:
  - Active PGN move notation stream viewer.
  - Quick-copy exporters for both FEN and PGN strings.
  - Live custom FEN state importer to load custom setups, puzzles, or opening practices.
- **Distraction-Free Environment**: Silent-first gameplay mode for maximum strategic focus and uninterrupted tactical evaluation.

---

## 🛠️ Built With

- **Stockfish.js v18**: The world's leading open-source chess engine compiled to WASM.
- **Chessboard.js v1.0.0**: Interactive browser board interface.
- **Chess.js**: Full chess game rule validator and state manager (detecting check, mate, stalemate, draw conditions).
- **Tailwind CSS**: Clean, modern styling using utility classes and responsive layouts.
- **jQuery**: Dynamic document object model (DOM) updates and event handling.

---

## 🚀 How to Play

1. **Pick Your Color**: Choose whether you play as White or Black inside the "Match Setup Console" on the right.
2. **Choose Your Challenge**: Set the Stockfish ELO strength, pick a time control, and set the maximum calculation duration (1.2 seconds recommended for casual instant play).
3. **Move Your Pieces**: Drag and drop pieces on the board or click on the starting piece and the destination square.
4. **Leverage Evaluation**: Keep an eye on the centipawn evaluation slider at the top to see if your moves are keeping you in a winning position!
