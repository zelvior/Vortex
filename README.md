# 🎬 Vortex — Media Intelligence Platform

**Vortex** is a sophisticated, single-page web application (SPA) for managing and tracking your personal media collection. Whether you're tracking movies, series, anime, games, or any other media, Vortex provides an intelligent, beautifully designed interface to organize your digital entertainment universe.

**Live Demo:** [Vortex Media Platform](https://zelvior.github.io/Vortex/)

---

## ✨ Features Overview

### 🎯 Core Functionality
- **Multi-Profile Vault System** — Create and manage separate media vaults for different profiles or categories
- **Smart Media Tracking** — Track movies, series, anime, games, and other media with detailed metadata
- **Status Management** — Categorize media as: Plan to Watch, In Progress, Completed, or Watchlist
- **Rating System** — Rate titles with star-based scoring (0-10)
- **Progress Tracking** — Monitor watch progress for ongoing titles with visual progress bars
- **Smart Tags** — Tag media with custom labels for better organization and filtering
- **Cover Image Management** — Fetch, upload, and manage cover artwork for each title

### 🔍 Search & Filtering
- **Global Search** — Find media by title, notes, or metadata with real-time results
- **Multi-Filter System:**
  - All Media
  - In Progress
  - Completed
  - Watchlist
- **Tag-Based Filtering** — Filter and organize by custom tags
- **Advanced Sorting:**
  - Recent First (newest additions)
  - Highest Rated
  - Alphabetical

### 📊 Statistics Dashboard
- **Vault Capacity** — Total number of titles in your vault
- **Active Now** — Currently watched/playing media count
- **Finished** — Completed media count
- **Watchlist** — Items marked to watch
- **Advanced Analytics:**
  - Completion rings and radial progress visualizations
  - Heatmaps showing watch activity patterns
  - Milestone tracking and achievement badges
  - Sparkline charts for trends

### 🎨 Customization & Appearance

#### Theme Options
- **Dark Mode** — Deep blue (default)
- **Dim Mode** — Softer, mid-tone interface
- **Light Mode** — Bright, comfortable for day use
- **AMOLED Mode** — True black background (OLED optimized)
- **Nord** — Popular Nordic-inspired palette
- **Solarized** — Classic, warm color scheme

#### Accent Colors
- Blue (default)
- Violet
- Rose
- Amber
- Emerald
- Cyan

#### Layout Density
- **Compact** — 4-6 columns (ultra-dense grid)
- **Normal** — 2-3 columns (balanced)
- **Spacious** — 1-2 columns (large, prominent cards)

### 📱 Responsive Design
- **Full Mobile Support** — Optimized for phones, tablets, and desktops
- **Adaptive Grid System:**
  - 1 column on mobile (<480px)
  - 2 columns on tablets (481-1023px)
  - 3 columns on desktops (1024-1279px)
  - 5-6 columns on ultra-wide screens (1920px+)
- **Safe Area Handling** — Respects notches and island devices
- **Touch-Optimized** — Gestures and touch-friendly interactions
- **Landscape Support** — Smart layouts for landscape orientation

### 💾 Data Management
- **Export as JSON** — Backup your entire vault as a portable JSON file
- **Import from JSON** — Restore previously exported vaults
- **Local Storage** — Data persists in browser storage
- **Auto-Save Badge** — Visual indicator of saved state
- **Recently Deleted Bin** — Recover accidentally deleted entries

### 🔐 Security Features
- **Vault Lock Screen** — PIN-based vault protection
- **PIN Pad** — Secure numeric PIN entry (4-8 digits)
- **Multi-Profile Isolation** — Separate data per profile

### 🎯 Advanced Features

#### Drag & Drop
- Drag media cards to reorder
- Grab handle for intuitive rearrangement
- Visual feedback during dragging

#### Bulk Operations
- Multi-select media items
- Bulk actions bar with batch operations
- Checkbox selection interface

#### Views
- **Grid View** — Default card-based layout
- **List View** — Compact, text-focused view
- **Kanban Board** — Column-based organization by status
- **Timeline** — Chronological view of additions

#### PWA Support
- **Progressive Web App** — Install as native app
- **Offline Capability** — Access stored data offline
- **App Shortcuts** — Quick actions from home screen
- **Safe Area Insets** — Full-screen support on PWA

#### Command Palette
- Quick access search (Cmd/Ctrl + K)
- Command shortcuts for power users
- Keyboard navigation support

### 🔔 User Experience
- **Toast Notifications** — Non-intrusive feedback messages
- **Skeleton Loaders** — Shimmer animations during load
- **Smooth Animations** — Cubic-bezier transitions (0.16,1,0.3,1)
- **Glass-Morphism UI** — Blurred backdrop effects
- **Accessibility Modes:**
  - High contrast
  - Reduced motion support
  - Focus-visible indicators
- **Tooltips & Help** — Data-attribute based tooltips

### ⚙️ Settings & Preferences

#### Appearance
- Color mode selection
- Accent color picker (6 options)
- Card animation toggle
- Theme selection (6+ themes)

#### Layout
- Grid density adjustment (3 levels)
- Safe area padding customization

#### Behavior
- Confirm before delete toggle
- Default sort order
- Default filter tab
- Animation preferences

#### Debug Features
- Debug panel for developers
- Performance KPIs
- Live data inspection
- Development shortcuts

### 🎁 Additional Features
- **Floating Donate Button** — Support developer link with pulsing animation
- **Support Link** — External link to support/donation page
- **Changelog Modal** — View recent updates
- **Feedback System** — User feedback collection
- **QR Modal** — QR code sharing for data/vaults
- **Offline Banner** — Network status indicator
- **Backup Badge** — Auto-save status

---

## 🛠️ Technical Stack

### Frontend
- **HTML5** — Semantic markup
- **CSS3** — Advanced styling with CSS variables
- **Vanilla JavaScript** — No framework dependencies (currently)
- **Tailwind CSS** — Utility-first CSS framework

### External Libraries
- **Supabase.js** — Backend/database integration (ready for integration)
- **Google Identity Services** — OAuth authentication support
- **Google Fonts** — Inter & Plus Jakarta Sans fonts

### Design System
- **CSS Variables** — Themeable design tokens
- **Backdrop Filters** — Modern glass-morphism effects
- **CSS Grid & Flexbox** — Modern layout techniques
- **Media Queries** — Mobile-first responsive design
- **Animations** — Custom keyframe animations

---

## 📋 Installation & Setup

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- No backend server required for basic usage

### Quick Start
1. **Clone the repository:**
   ```bash
   git clone https://github.com/zelvior/Vortex.git
   cd Vortex
   ```

2. **Open in browser:**
   ```bash
   # Simply open index.html in your browser
   open index.html
   ```

3. **Or use a local server (recommended):**
   ```bash
   # Python 3
   python -m http.server 8000
   
   # Python 2
   python -m SimpleHTTPServer 8000
   
   # Node.js
   npx http-server
   ```

4. **Access the app:**
   - Open `http://localhost:8000` in your browser

### For PWA Installation
1. Visit the live demo on a modern mobile browser
2. Look for "Add to Home Screen" or "Install" prompt
3. Install as a native app
4. Access offline and get app-like experience

---

## 🎮 Usage Guide

### Creating a Vault
1. Click **"New Vault"** button in the Vault selector
2. Enter a name for your vault
3. Your vault is created and ready to use

### Adding Media
1. Click the **"+"** button in the header
2. Fill in media details:
   - Title (required)
   - Type (Movie, Series, Anime, Game, etc.)
   - Status (Plan to Watch, In Progress, Completed, Watchlist)
   - Rating (0-10 stars)
   - Notes/description
   - Cover image (fetch or upload)
   - Tags
3. Click **Save**

### Searching & Filtering
1. Use the **search bar** to find by title or notes
2. Use **filter tabs** for status-based filtering
3. Use **tag chips** to filter by tags
4. Use **sort dropdown** to change order (Recent, Rating, Alphabetical)

### Customizing Appearance
1. Navigate to **Settings** (gear icon)
2. **Appearance Tab:**
   - Choose color mode (Dark, Dim, Light, etc.)
   - Select accent color
   - Toggle animations
3. **Layout Tab:**
   - Adjust grid density
4. **Behavior Tab:**
   - Set preferences for delete confirmations
   - Choose default sort and filter
5. Changes apply instantly

### Exporting & Importing
- **Export:** Click export button → download JSON file
- **Import:** Click import button → select JSON file → data restores

### Using Advanced Views
- **Grid View** (default) — Click grid icon
- **List View** — Compact card display
- **Kanban** — Organize by status columns
- **Timeline** — Chronological view

---

## 🎨 Design & Styling Details

### Color Palette (Default Dark Theme)
```css
Primary Blue:        #3b82f6
Primary Blue Hover:  #2563eb
Primary Glow:        rgba(59,130,246,0.45)
Background:          #020617
Card Background:     rgba(30,41,59,0.7)
Text Primary:        #f8fafc
Text Muted:          #94a3b8
Border:              rgba(255,255,255,0.08)
```

### Typography
- **Heading Font:** Plus Jakarta Sans (700, 800 weights)
- **Body Font:** Inter (300-800 weights)
- **Monospace:** System monospace (for debug panel)

### Animation Timings
- **Default Easing:** cubic-bezier(0.16,1,0.3,1)
- **Card Hover:** 400ms
- **Modal Transition:** 350ms
- **Toast Animation:** 250ms

### Responsive Breakpoints
```
Mobile:     <480px
Tablet:     481-1023px
Desktop:    1024-1279px
Wide:       1280-1919px
Ultra-Wide: ≥1920px
```

---

## 📂 File Structure

```
Vortex/
├── index.html           # Main application (single file)
├── README.md            # This file
└── LICENSE              # License information
```

The entire application is contained in a single `index.html` file with:
- Embedded CSS (full stylesheet)
- Embedded JavaScript (application logic)
- Inline PWA manifest
- Embedded SVG icons

---

## 🔧 Development Guide

### CSS Variables
All colors and values use CSS custom properties. Edit the `:root` section to customize:

```css
:root {
    --primary: #3b82f6;
    --bg-base: #020617;
    --text-primary: #f8fafc;
    /* ... */
}
```

### Adding a New Theme
1. Add a new `body.theme-name` rule
2. Define all CSS variables
3. Reference in settings section

### JavaScript Modules (Inferred)
Based on HTML structure, the app likely uses:
- `dataManager` — Handle export/import
- `ui` — UI rendering and interactions
- `cfg` — Configuration/settings
- `profiles` — Vault management
- `tagSystem` — Tag filtering
- Supabase client (when enabled)

### Extending Functionality
1. Modify inline CSS for styling changes
2. Add event handlers via `onclick` attributes
3. Extend JavaScript modules as needed
4. Test with `python -m http.server`

---

## 🌐 Browser Support

| Browser | Support | Notes |
|---------|---------|-------|
| Chrome  | ✅ Full | All features |
| Firefox | ✅ Full | All features |
| Safari  | ✅ Full | All features |
| Edge    | ✅ Full | All features |
| Mobile  | ✅ Full | PWA support |

---

## 🔐 Privacy & Data

- **Local Storage:** All data stored in browser's IndexedDB/LocalStorage by default
- **No Telemetry:** No tracking or analytics (currently)
- **Optional Cloud:** Supabase integration available but not required
- **Export Control:** You control your data via export/import

---

## 🎯 Keyboard Shortcuts

| Shortcut | Action |
|----------|--------|
| `Cmd/Ctrl + K` | Open command palette |
| `Esc` | Close modals/palettes |
| `Tab` | Navigate elements |
| `Enter` | Confirm/Submit |

---

## 🐛 Known Limitations & Future Enhancements

### Current
- Single-file architecture (no bundling)
- Browser-only storage (no cloud sync by default)
- Limited to viewport size for modals

### Planned
- Supabase backend integration
- OAuth authentication
- Cloud synchronization
- Advanced filtering UI
- Mobile app (React Native)
- Browser extensions

---

## 📝 License

This project is licensed under the **Apache License 2.0**. See the [LICENSE](LICENSE) file for details.

**Important:** Vortex is distributed on an **"As-Is"** basis, without warranties or conditions of any kind, unless required by applicable law.

---

## 🤝 Contributing

Contributions are welcome! To contribute:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Make your changes
4. Test thoroughly
5. Commit your changes (`git commit -m 'Add amazing feature'`)
6. Push to the branch (`git push origin feature/amazing-feature`)
7. Open a Pull Request

### Areas for Contribution
- Performance optimization
- New themes
- Bug fixes
- Documentation improvements
- Accessibility enhancements
- Mobile experience improvements

---

## 💬 Feedback & Support

- **Issues:** Report bugs via GitHub Issues
- **Suggestions:** Feature requests welcome
- **Support:** Visit [Support Page](https://zelvior.github.io/Support/)
- **Donations:** Support the dev through the in-app donate button

---

## 🙏 Acknowledgments

- **Tailwind CSS** — Utility-first CSS framework
- **Google Fonts** — Inter & Plus Jakarta Sans typefaces
- **Supabase** — Backend-as-a-service platform
- **Google Identity Services** — OAuth integration
- **Noto Emoji** — Icon source

---

## 📊 Statistics

- **Code Size:** Single HTML file (self-contained)
- **Themes:** 6+ built-in themes
- **Languages:** HTML, CSS, JavaScript
- **Responsive Breakpoints:** 5+
- **Supported Views:** 4+ (Grid, List, Kanban, Timeline)
- **Status Types:** 4 (Plan to Watch, In Progress, Completed, Watchlist)

---

## 🚀 Performance Features

- **Lazy Loading:** Images load on demand
- **CSS Optimization:** Minimal CSS with custom properties
- **No Dependencies:** Vanilla JavaScript (fast loading)
- **Offline Support:** Progressive Web App
- **Caching:** Browser caching and service workers ready
- **Optimized Animations:** GPU-accelerated transforms

---

## 📱 Mobile Optimization

- **Viewport Meta:** Proper viewport settings
- **Safe Area:** Notch/island device support
- **Touch Gestures:** Swipe-enabled interactions
- **Responsive Text:** Font sizes adjust per breakpoint
- **Compact UI:** Mobile-optimized spacing and buttons
- **Offline Functionality:** Full app works offline

---

## ✅ Checklist for First Use

- [ ] Open `index.html` in browser
- [ ] Create your first vault
- [ ] Add a media entry
- [ ] Try different themes
- [ ] Test search and filtering
- [ ] Export your data for backup
- [ ] (Optional) Install as PWA
- [ ] Configure your preferences

---

## 🎓 Learning Resources

- **Tailwind CSS:** [Tailwind Documentation](https://tailwindcss.com)
- **CSS Custom Properties:** [MDN Guide](https://developer.mozilla.org/en-US/docs/Web/CSS/--*)
- **Web Components:** [MDN Reference](https://developer.mozilla.org/en-US/docs/Web/Web_Components)
- **PWA Guide:** [Web.dev PWA](https://web.dev/progressive-web-apps/)

---

## 📞 Contact

- **GitHub:** [@zelvior](https://github.com/zelvior)
- **Project:** [Vortex Repository](https://github.com/zelvior/Vortex)
- **Live Demo:** [https://zelvior.github.io/Vortex/](https://zelvior.github.io/Vortex/)

---

**Happy tracking! 🎬🎮📚**

*Vortex — Your personal media intelligence platform.*
