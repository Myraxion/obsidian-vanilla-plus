# Obsidian Vanilla+ CSS Snippets

English | [简体中文](README.md)

A curated collection of minimalist, lightweight, and elegant CSS snippets designed for Obsidian. Powered entirely by vanilla CSS, ready out of the box with zero third-party plugin dependencies, crafted to elevate everyday writing and layout aesthetics with restraint and precision.

---

## 📂 Modules & Snippets

| Snippet | Scope | Highlights & Features |
| :--- | :--- | :--- |
| `headings.css` | **Headings System** | • **Harmonious Palette**: Balanced 6-level heading color scheme; keeps the inline title matching regular text color to prevent visual clutter;<br>• **Fading Dividers**: Smooth rightward-fading dividers beneath inline title and H1/H2 for clearer document structure;<br>• **Indicator Bar**: Left-aligned accent bars matching font height that smoothly expand on hover or cursor focus;<br>• **Heading Badges**: Replaces native collapse arrows with refined vector H1~H6 badges that highlight when collapsed. |
| `code.css` | **Code System** | • **Dot Matrix Texture**: Adaptive dot-matrix background pattern for light/dark modes, providing a subtle engineering tactile feel;<br>• **Inline Code Highlight**: Vibrant pink accent with rounded badge background for instant code recognition;<br>• **Dashed Borders**: Light dashed border and subtle rounded corners for code blocks, preserving native syntax highlighting intact;<br>• **Line Numbers**: Clean line numbers dynamically appear on hover or focus. |
| `quote.css` | **Blockquote System** | • **Grid Paper Texture**: Clean 18px dual-directional subtle grid pattern built with vanilla CSS gradients, delivering a tactile graph notebook feel;<br>• **Accent Tint Background**: Soft translucent background derived dynamically via `color-mix`, seamlessly echoing the left border color;<br>• **Layout Breathing Room**: Comfortable internal padding ensuring text never clings to the border while decoupling completely from inline bold/italic formatting. |
| `focus-indicator.css` | **Line Focus Indicator** | • **Focus Micro-Bar**: Subtle vertical accent bar on the left edge of paragraph text lines;<br>• **Dynamic Cursor Tracking**: Smoothly extends on hover and automatically highlights the active line where the cursor is placed, enhancing deep reading and writing flow. |
| `markdown-formatting.css` | **Inline Text Formatting** | • **Bold & Italic**: High-contrast neutral bold with subtle translucent background tint and muted secondary italic, preventing color competition with rainbow headings;<br>• **Gentle Highlights**: Translucent yellow highlighting with gentle padding and rounded edges;<br>• **Keyboard & Strikethrough**: Tactile 3D-styled `<kbd>` keys with micro drop shadows, accompanied by softly dimmed strikethrough text. |
| `cjk-italic.css` | **CJK & Latin Italic** | • **Unicode Range Splitting**: Accurately targets CJK ideographs and punctuation via `unicode-range`, mapping them to native system KaiTi (楷体);<br>• **Eliminates Faux-Italics**: Disables synthetic obliquing (`font-synthesis-style: none`) so Latin retains true italic while Chinese renders crisp, upright regular KaiTi without blurred geometric distortion. |
| `colored-folder.css` | **Colored Root Folders** | • **7-Color Cycle Partitioning**: Assigns translucent, harmonious pastel backgrounds to top-level folders in the file explorer;<br>• **Instant Visual Navigation**: Rapidly distinguish category vaults with light/dark adaptive palettes;<br>• **Focus Enhancement**: Active and selected items feature subtle left accent bars and bold text contrast for clear visual hierarchy over colored backgrounds. |

---

## 🚀 Installation & Usage

1. Open your Obsidian vault folder and navigate into `.obsidian/`.
2. If the `snippets` folder doesn't exist, create it (i.e. `.obsidian/snippets/`).
3. Copy all or desired `.css` files from the `snippets/` directory of this repository into `.obsidian/snippets/`.
4. In Obsidian:
   - Go to **Settings** -> **Appearance** -> **CSS snippets**.
   - Click **Reload snippets**.
   - Toggle on the snippets you wish to enable.

---

## 🙏 Credits & Acknowledgements

Part of the visual design and stylistic inspiration comes from the outstanding open-source community theme:

- **[Border](https://github.com/akifyss/obsidian-border)** by [@akifyss](https://github.com/akifyss): Provided immense inspiration for the heading indicator bars, fading dividers, dot-matrix textures, and subtle aesthetic details. Special thanks and respect to the author!
