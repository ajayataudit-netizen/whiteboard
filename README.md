# Whiteboard Pro

A fast, clean, infinite-canvas whiteboard with zero external dependencies, zero CDN links, zero external fonts, and zero tracking.

---

## 🚀 How to Run

### Method 1: Direct Double-Click (Zero Setup)
Simply double-click [`index.html`](file:///C:/Users/G095/.gemini/antigravity/scratch/offline-whiteboard/index.html) in your file manager. It will open directly in Google Chrome, Microsoft Edge, Mozilla Firefox, Apple Safari, or Opera.

### Method 2: Local Static Server & PWA Installation
To install it as a native desktop or mobile PWA:
1. Open PowerShell / Command Prompt in this folder:
   ```bash
   npx serve .
   # or
   python -m http.server 8080
   ```
2. Navigate to `http://localhost:8080`.
3. In Chrome or Edge, click the **Install App** icon in the address bar (or go to `Menu > Apps > Install Whiteboard Pro`).

---

## 🎨 Professional Features & Controls

### 1. Mode Switcher (Draw vs Type)
- **Draw Mode**: Optimized for pen, brush, highlighter, shapes, and freehand sketching with smooth curves and pressure sensitivity.
- **Type Mode**:
  - Freehand drawing tools are **completely locked out** to avoid accidental strokes.
  - **Instant Keyboard Typing**: Simply start typing any letter, number, or symbol on your keyboard and words appear immediately on the canvas with an active blinking cursor.
  - Clicking on the canvas places or relocates the text cursor instantly.
- Toggle anytime by clicking the segmented control or pressing **`M`**.

### 2. Canvas Slidebars & Navigation Controls
- **Horizontal Slidebar (`#canvas-slidebar-h`)**: Draggable pill slider along the bottom to slide horizontally across your infinite canvas.
- **Vertical Slidebar (`#canvas-slidebar-v`)**: Draggable pill slider along the right edge to slide vertically.
- **Quick Pan Directional Pad (Bottom-Right)**: 4-way arrow controls (`▲` `▼` `◀` `▶`) and center reset view (`⌖`).
- **Standard Navigation**: Space + mouse drag or scroll wheel zoom around the cursor.

### 3. Clean, Professional UI
- Streamlined top application bar with clean "Saved" indicator (no intrusive labels).
- Left tool dock with crisp SVG icons and visual state cues.
- Responsive, collapsible properties dock for stroke colors, fill colors, widths, opacity, and typography.

### 4. 32+ Curated Theme Palettes
- Click **Palette** (`C`) to cycle through schemes (Corporate Blue, Forest Canopy, Sunset Horizon, Monochrome Slate, Pastel Dream, Neon Cyber, etc.).
- Includes **Previous Palette** (`◀`) and **Lock Palette** (🔒) buttons.

### 5. 10 Built-In Themes
- Light, Dark, Midnight, Paper, Blueprint, Chalkboard (classroom dark green chalk board), Sepia, High Contrast, Solarized, and Pastel.

### 6. 25+ Vector Shapes & Connectors
- Line, Arrow, Double Arrow, Curved Arrow, Rectangle, Rounded Rect, Circle, Ellipse, Triangle, Right Triangle, Diamond, Star, Heart, Cloud, Speech Bubble, Parallelogram, Trapezoid, Cylinder, Cross, Checkmark, Bracket, and Flowchart symbols (Process, Decision, Terminator, Data) with snap connectors.

### 7. Dual-Mode Eraser
- Interactive pixel/partial stroke carver & whole-object eraser with cursor preview.

### 8. 13 Background Options
- Plain, Grid, Dots, Lined (Narrow/Wide with red margin), Graph Paper, Isometric Grid, Ruler guides (with cm/inch marks), Music Staff, Cornell Notes, Checklist Layout, Weekly Planner, and Blueprint.

### 9. 15 Document & Image Export Formats
- **Images**: PNG (transparent toggle, 1x/2x/4x), JPG, WebP, SVG, BMP.
- **Documents**: PDF 1.4, Word (.docx) with embedded drawing + extracted text, Excel (.xlsx) with object data inventory, PowerPoint (.pptx) with board slide.
- **Text & Backup**: TXT, Markdown (.md), standalone HTML, CSV, `.json` and `.whiteboard` backups, plus Copy Image to Clipboard and Print.

---

## ⌨️ Keyboard Shortcuts Reference

| Shortcut | Action |
| :--- | :--- |
| **`M`** | Toggle Draw / Type mode |
| **`V`** | Select & Move tool |
| **`P`** | Freehand Pen tool (Draw mode) |
| **`H`** | Highlighter tool |
| **`E`** | Eraser tool |
| **`T`** | Text tool (Type mode) |
| **`R`** | Shapes palette |
| **`S`** | Sticky Note |
| **`C`** | Cycle random colour palette |
| **`Slidebars`** | Slide horizontally or vertically to pan canvas |
| **`Space + Drag`** | Pan canvas |
| **`Mouse Wheel`** | Zoom canvas |
| **`Ctrl + Z`** | Undo |
| **`Ctrl + Y`** / **`Ctrl + Shift + Z`** | Redo |
| **`Ctrl + D`** | Duplicate selected object(s) |
| **`Delete`** / **`Backspace`** | Delete selected object(s) |
| **`Ctrl + E`** | Open Export dialog |
| **`?`** | Open Keyboard shortcuts modal |
