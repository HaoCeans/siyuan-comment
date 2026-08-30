<div align="center">

# Whale Quick Comment

Select to annotate · Sidebar management · Slide to comment · Zero pollution

[Tutorial (Zhihu)](https://zhuanlan.zhihu.com/p/2064425147713508327) &nbsp;·&nbsp; [Video (Bilibili)](https://www.bilibili.com/video/BV1Nv336uEjc/)

</div>

> 🔒 **Plugin promise**: Absolutely safe, zero pollution, original data permanently preserved, instant annotation on 10k-word documents, fully offline. After uninstalling the plugin, highlighted text automatically restores its native underline, and your comment notes remain untouched inside SiYuan — you can still view, edit, and modify them via SiYuan's built-in block references and backlinks. Only the popover editor and sidebar features are lost.

<div align="center">

  <a href="https://github.com/HaoCeans/siyuan-comment/issues">💌 Feedback & Suggestions</a>
  &nbsp;·&nbsp;
  <a href="https://qm.qq.com/q/pVIyMulbS8">💬 User Group (QQ)</a>
  &nbsp;·&nbsp;
  <a href="https://github.com/HaoCeans/comment">⭐ GitHub</a>

</div>

---

# 📱 Full Platform Support

Works on desktop, mobile, and tablet, with interactions adapted per platform:

| Platform | Comment panel | Slide-to-annotate | Continuous mode | How to exit |
|---|---|---|---|---|
| **Desktop** (Windows / macOS / Linux / Browser) | Dock panel | Mouse drag-select | ✅ Supported | `ESC` key |
| **Mobile** (App / Mobile browser) | Sidebar comment tab | Touch swipe | Single comment | Auto-exit after creating |
| **Tablet** (App / Tablet browser) | Floating right panel | Touch swipe | ✅ Supported | Bottom toolbar「Exit」button |

# ✨ Core Features

#### 🤖 AI Explanation (Powered by SiYuan's Native AI)
- **Zero configuration**: reuses SiYuan's built-in AI engine — no API key, no third-party service
- **One-click from the comment popover**: tap the ✨ button → AI explains the highlighted text in document context
- **Smart Prompt templates**: supports `{docContent}` `{highlightedText}` `{commentText}` placeholders, customizable in settings
- **Follow-up questions**: keep asking for deeper discussion in the AI panel
- **Persistent cache**: conversation history survives closing and reopening the popover
- **One-click insert**: AI results can be inserted at the end of the comment editor, or copied to the clipboard

#### 🚀 Three Ways to Create
- **Custom shortcut** — select text, one-key annotate (Settings → Shortcuts → plugin "Whale Quick Comment")
- **Slide-to-annotate** — drag-select on mobile/desktop for immersive annotation
- **Toolbar button** — one-click from the editor's floating toolbar

#### 🎯 Four Insertion Targets
- **Document bottom · Today's daily note · Target document · Child document** — you decide where comments go
- Independent header template per target (supports `{year}{month}{day}{sourceRef}` placeholders)
- Manual target mode: pick one of four on every creation

#### 🎨 Underline Styles · 35+ Combinations
- 7 preset colors × 5 line styles = 35 combinations
- Plus **custom color**: any color you like (8 colors × 5 line styles total), pure DOM rendering, **never modifies the document markdown**
- One-click update of all underline styles in the current document
- **Quick styles**: favorite color+style combos (incl. custom colors) for one-click switching in the popover, applied instantly

#### ⚡ One-click Flashcard · Progressive Reading
- 📖 **Incremental Learning tutorial**: [▶ Read](https://www.yuque.com/supermemo/wiki/what_is_incremental_learning)
- **Comments as flashcards**: the ⚡ button in the popover turns a comment into a SiYuan flashcard — annotate while reading, review later
- **Heading-based cards**: choose「comment header block」as the card source (set the header template to a heading like `#### xxx`), the card question auto-takes the heading for focused review
- **Auto flashcard**: enable「Auto-create flashcard after comment」to add every new comment to your card deck automatically
- **Cancel anytime**: tap the button again to un-flashcard; data is fully managed by SiYuan's native card system, offline-friendly

#### 🏷️ Custom Tag Categories
- 5 presets (📌Pinned ⭐Important 📖Reading ✔️Todo ❓Question) — rename / recolor / re-icon / reorder
- **Custom tags** — create in settings with independent colors and emoji icons
- **Cross-document aggregation** — all tagged comments in one view, filter & search, one-click jump to the source document
- Tag filters are remembered; the whole collapsed bar is clickable

#### 📋 Sidebar Management
- Cards show source preview + comment content, three sort orders
- Click a card to jump to the highlight in the document, or to the comment block at the end
- Orphan comment detection with cleanup hints
- **Global search**: filters both the tagged section and the main list, matching source text and comment content

#### 🔄 Continuous Slide Mode
- With「Continuous mode」on, slide-to-annotate **stays active** after creating
- Drag-select multiple passages in a row; press `ESC` to exit

#### ✏️ Protyle Popover Editing
- Full rich-text editing, `Ctrl+Enter` to save
- Clean mode (hide markers) / numbered mode; four list structures (unordered / ordered / task / quote)
- Custom copy format and three independent time formats

#### 📱 Mobile Deep Optimizations
- RAF throttling + `deferAttrs` server acceleration for slide-to-annotate — popover appears the moment you release
- Transparent overlays for popover / target picker — tapping outside only closes, never pops the keyboard

#### 🌓 Dark Mode
Auto-detects the SiYuan theme; Apple-style sidebar adaptation

#### 🛡️ Zero Data Pollution
All metadata lives in block attributes; document kramdown stays clean; exports are unaffected

---

<details>
  <summary style="font-size: 20px; font-weight: 600; cursor: pointer;">📖 User Guide</summary>

### Creating Comments

| Method | How |
|------|------|
| Shortcut | Select text → custom shortcut (Settings → Shortcuts → plugin "Whale Quick Comment") |
| Toolbar | Select text → comment button in the floating toolbar |
| Slide mode | Enable「Slide to annotate」in the sidebar → drag-select in the document (desktop supports **continuous mode**: check it to keep creating, `ESC` to exit) |

With manual target selection enabled, a four-choice picker appears at creation time: use ← → to switch and Enter to confirm.

### Viewing & Editing
- **Sidebar**: dock icon bottom-right on desktop / top-bar icon on mobile
- **Click the underline**: opens the editing popover
- **Sidebar cards**: source area → jump to highlight; content area → jump to the comment block

### Popover Actions

| Action | Description |
|------|------|
| `Ctrl+Enter` / Save button | Save and close |
| Copy | Copy to clipboard in your custom format |
| Jump | Locate the comment across documents |
| Delete | Delete the comment (with confirmation) |
| `Esc` | Close the popover |

### Tag Management
Click the tag icon on a sidebar card → tag menu → pick a tag. Tagged comments appear in a dedicated section at the top of the sidebar.

**Custom tags**: sidebar top-right ⚙ → Tag Management → create / edit / delete / reorder tags with custom names, emoji icons, and colors.

### Settings
Sidebar top-right ⚙ button.

</details>

<details>
  <summary style="font-size: 20px; font-weight: 600; cursor: pointer;">⌨️ Shortcuts</summary>

| Action | Shortcut |
|------|------|
| Add comment | Custom shortcut (none by default; bind in Settings → Shortcuts) |
| Save popover | `Ctrl+Enter` / `⌘+Enter` |
| Close popover | `Esc` |

</details>

---

# 📦 Installation

SiYuan → **Settings → Marketplace → Plugins** → search "Whale Quick Comment" → Install.

Or download `package.zip` from [Releases](https://github.com/HaoCeans/siyuan-comment/releases), extract it into `data/plugins/siyuan-comment/`.

> Requirements: SiYuan ≥ 3.8.2, desktop and mobile supported.

---

# 🔧 Development

```bash
npm install && npm run dev    # dev mode
npm run build                 # production build
```

---

<div align="center">
  Made with 💙 by whale🐋
</div>
