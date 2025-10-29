# ABCGen - Letter Studio Pro

**Ultimate Pixel Art Letter Creator & Font Generator**

Transform sprite sheets into custom pixel fonts with an intuitive desktop application built for artists, game developers, and designers.

---

## 🎨 Overview

ABCGen (also known as LetteringPlus) is a comprehensive desktop application that allows you to extract, create, and compile pixel art letters into reusable fonts. Whether you're working with existing sprite sheets or creating letters from scratch, ABCGen provides all the tools you need.

### Key Features

- **🖼️ Smart Crop Mode** - Extract letters from sprite sheets with auto-detection
- **✏️ Advanced Draw Mode** - Create custom letters with multi-layer support
- **📝 Text Compiler** - Generate pixel art text using your custom fonts
- **💾 Native File Operations** - Full desktop integration with system file dialogs
- **🎨 Professional Tools** - Layers, color palette, undo/redo, and more

---

## 📥 Installation

### Requirements

- **Windows**: Windows 10 or later
- **macOS**: macOS 10.14 (Mojave) or later
- **Linux**: Ubuntu 18.04+ or equivalent

### Download

1. Visit the [Releases](../../releases) page
2. Download the latest version for your operating system:
   - Windows: `ABCGen.exe`
   - macOS: `ABCGen.dmg`
   - Linux: `ABCGen.AppImage`
3. Run the executable (no installation required)

---

## 🚀 Quick Start

### Creating Your First Font

1. **Import a Sprite Sheet**
   - Click "📸 Crop" mode
   - Upload your sprite sheet image
   - Click "🤖 Auto-Detect" to find letters automatically

2. **Save Letters**
   - Click on detected regions or manually select areas
   - Name each letter (A-Z, 0-9, symbols)
   - Letters are saved to your library

3. **Generate Text**
   - Switch to "📝 Text" mode
   - Type your message
   - Click "🎨 Generate" to create pixel art text
   - Export as PNG

---

## 🎯 Feature Guide

### 📸 Crop Mode

Extract letters from existing sprite sheets or images.

**Tools:**
- **Auto-Detect** - Automatically finds individual letter regions
- **Manual Selection** - Click and drag to select specific areas
- **Quick Name Buttons** - Rapidly name letters A-Z, 0-9
- **Preset Sizes** - Quick selection boxes (8×8, 16×16, 32×32, 64×64)

**Workflow:**
```
Upload Image → Auto-Detect → Click Regions → Name Letters → Save
```

**Keyboard Shortcuts:**
- `Enter` - Save selected letter
- `Esc` - Clear selection
- `Space` - Run auto-detect
- `+/-` - Zoom in/out

---

### ✏️ Draw Mode

Create custom letters from scratch with professional drawing tools.

**Features:**
- **Multi-Layer Support** - Organize your artwork in layers
- **Brush Sizes** - 1px, 2px, 4px, 8px brushes
- **Tools** - Draw, Erase, Fill
- **Layer Controls** - Opacity, visibility, reorder
- **Undo/Redo** - Up to 50 steps of history
- **Pixel Grid** - Toggle snap-to-grid for precision

**Keyboard Shortcuts:**
- `Ctrl+Z` - Undo
- `Ctrl+Y` - Redo
- `+/-` - Zoom in/out

---

### 📝 Text Mode

Compile your saved letters into beautiful pixel art text.

**Features:**
- **Multi-line Support** - Create paragraphs with line breaks
- **Spacing Controls** - Letter spacing, line height, space width
- **Color Tint** - Apply colors while preserving shading
- **Live Preview** - See results in real-time
- **Export to PNG** - Save as image with transparency

**Settings:**
- **Letter Spacing**: -5px to 20px
- **Line Height**: 10px to 50px
- **Space Width**: 2px to 30px

---

## 💡 Tips & Best Practices

### Sprite Sheet Preparation

1. **Use PNG format** with transparency for best results
2. **Separate letters** with transparent pixels
3. **Consistent sizing** helps auto-detection
4. **High contrast** makes detection more accurate

### Letter Naming Convention

Follow standard order for quick access:
```
A B C D E F G H I J K L M N O P Q R S T U V W X Y Z
0 1 2 3 4 5 6 7 8 9
! ? . , ; : ' " - +
```

### Layer Organization

- **Layer 1**: Base/outline
- **Layer 2**: Fill colors
- **Layer 3**: Highlights/shadows
- **Layer 4**: Effects

### Color Palette

- Click custom color picker to add new colors
- Existing colors won't duplicate
- Palette persists during session

---

## 📂 File Management

### Export Options

**Download ZIP**
- Exports all saved letters as individual PNG files
- Organized in a single compressed archive
- Perfect for sharing or backup

**Export PNG** (Text Mode)
- Saves compiled text as transparent PNG
- Preserves pixel-perfect quality
- Ready for use in games or graphics

### File Formats

| Format | Use Case |
|--------|----------|
| **PNG** | Individual letters, exported text |
| **ZIP** | Complete font package |

---

## 🎨 Example Workflows

### Workflow 1: Extract Letters from Game Sprite Sheet

```
1. Open sprite sheet in Crop Mode
2. Click "Auto-Detect" to find all letters
3. Click each region and name them (A, B, C...)
4. Click "Auto-Save All" for automatic naming
5. Switch to Text Mode
6. Type message and generate text
7. Export as PNG
```

### Workflow 2: Create Custom Letter from Scratch

```
1. Switch to Draw Mode
2. Set canvas size (e.g., 16×16)
3. Select brush size and color
4. Draw your letter design
5. Add layers for details
6. Enter letter name (e.g., "A")
7. Click Save
8. Repeat for each letter
```

### Workflow 3: Modify Existing Letter

```
1. Find letter in sidebar
2. Click edit button (✏️)
3. Click "Edit in Draw Mode"
4. Make changes on canvas
5. Save with same or new name
```

---

## 🔧 Technical Details

### Supported Image Formats

- **Input**: PNG, JPG, JPEG, GIF, SVG
- **Output**: PNG (with alpha channel)

### Performance

- **Auto-detection**: ~100ms for typical sprite sheets
- **Layer rendering**: Real-time at 60 FPS
- **History**: 50 undo states (configurable)

### Canvas Limits

- **Minimum**: 8×8 pixels
- **Maximum**: 128×128 pixels
- **Recommended**: 16×16 or 32×32 for pixel art

---

## ❓ FAQ

<details>
<summary><b>Q: Can I import existing fonts?</b></summary>

Yes! Import any sprite sheet or font atlas using Crop Mode's auto-detection feature.
</details>

<details>
<summary><b>Q: What's the difference between "Save" and "Download ZIP"?</b></summary>

- **Save** (in Crop/Draw modes): Adds letters to your current session
- **Download ZIP**: Exports all saved letters as PNG files
</details>

<details>
<summary><b>Q: Why do some colors appear duplicated?</b></summary>

This has been fixed! The color palette now prevents duplicates automatically.
</details>

<details>
<summary><b>Q: Can I use this for commercial projects?</b></summary>

Yes! Fonts you create are yours to use however you'd like.
</details>

<details>
<summary><b>Q: Does it work offline?</b></summary>

Yes, ABCGen is a fully offline desktop application.
</details>

---

## 🐛 Troubleshooting

### Auto-Detect Not Finding Letters

- Ensure letters have **transparent spacing** between them
- Try **adjusting image contrast**
- Use **manual selection** for complex layouts

### Save Button Not Working

- Make sure you've **named the letter**
- Verify you have a **selection active**
- Check that you're in the correct mode

### Text Mode Not Showing Letters

- Ensure letter **names match** your text (case-insensitive)
- Verify letters are **saved** in your library
- Check the **letter count** in sidebar

### Performance Issues

- **Reduce canvas size** if drawing is slow
- **Merge layers** to improve rendering
- **Clear unused letters** from library

---

## 🛠️ Keyboard Shortcuts Reference

### Global

| Shortcut | Action |
|----------|--------|
| `Enter` | Save/Confirm |
| `Esc` | Cancel/Clear |
| `+` / `=` | Zoom In |
| `-` | Zoom Out |

### Crop Mode

| Shortcut | Action |
|----------|--------|
| `Space` | Auto-Detect Letters |
| `Enter` | Save Selected Letter |

### Draw Mode

| Shortcut | Action |
|----------|--------|
| `Ctrl+Z` | Undo |
| `Ctrl+Y` | Redo |
| `1-8` | Select Brush Size |

---

## 🔄 Version History

### Latest Version: v4.0 (October 2025)
- ✅ Fixed color palette duplication
- ✅ Fixed auto-save download spam
- ✅ Improved save button behavior
- ✅ Enhanced file dialog integration
- ✅ Better layer management

---

## 🤝 Contributing

This project was built to solve real workflow problems for pixel artists. If you have suggestions or find bugs, please [open an issue](../../issues).

### Reporting Bugs

Include:
1. **Steps to reproduce**
2. **Expected behavior**
3. **Actual behavior**
4. **Screenshots** (if applicable)
5. **OS and version**

---

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 🙏 Acknowledgments

- Built with [PyWebView](https://pywebview.flowrl.com/)
- Uses [JSZip](https://stuk.github.io/jszip/) for archive creation
- Inspired by the pixel art community

---

## 📞 Support

- **Issues**: [GitHub Issues](../../issues)
- **Discussions**: [GitHub Discussions](../../discussions)
- **Author**: [@Anonventions](https://github.com/Anonventions)

---

<div align="center">

**Made with ❤️ for pixel artists**

[⬆ Back to Top](#abcgen---letter-studio-pro)

</div>
