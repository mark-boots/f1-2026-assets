# F1 2026 Assets Viewer 🏎️

A comprehensive web-based viewer for Formula 1 2026 season assets, including drivers, teams, race schedules, and official F1 media resources.

## 🌐 Live Demo

**https://mark-boots.github.io/f1-2026-assets/**

## ✨ Features

### Drivers
- Complete 2026 F1 driver roster with circular team-colored portraits
- Driver profiles with nationality flags, birth dates, and team affiliations
- Driver numbers (white and black variants)
- Three-angle driver portraits (right, front, left)
- Driver codes and personal information

### Teams
- All 10 F1 teams with circular team badges
- Team logos in multiple formats (color, white, black)
- Team colors (primary and accessible)
- Car renders from three angles (left, front, right)
- Team information (chassis, power unit, base, team chiefs)

### Race Calendar
- Complete 2026 F1 season schedule (24 races)
- Country flags for each Grand Prix
- Track outlines and detailed track images
- Race dates and locations
- Direct links to official F1 race pages

### Visual Assets
- F1 official logos and branding elements
- Partner logos (DHL, Pirelli, FIA, etc.)
- Formula 1 official fonts
- Categorized asset library

### Fonts
- Official Formula 1 font family
- KH Interference fonts
- Northwell fonts
- Preview and download capabilities

## 🎨 Design Features

- **Dark Mode UI** - Sleek black background optimized for viewing
- **Formula 1 Branding** - Official F1 logo and Formula1 Bold typeface
- **Circular Badges** - Team-colored driver portraits and team logos
- **Responsive Tables** - Organized data with alternating row colors
- **Cloudinary Integration** - Dynamic image transformations for optimal display
- **Interactive Tabs** - Easy navigation between different asset categories

## 🛠️ Technologies

- **HTML5/CSS3** - Modern responsive design
- **Vanilla JavaScript** - No dependencies, pure JS
- **Cloudinary** - Image CDN with on-the-fly transformations
- **GitHub Pages** - Static site hosting
- **Python** - Web scraping scripts (not deployed)

## 📊 Data Sources

All data is scraped from official Formula 1 sources:
- **formula1.com** - Driver profiles, team information, race schedules
- **Cloudinary Media CDN** - Official F1 media assets

> **Note:** Not all 2026 assets are available yet on Formula 1's official media platform.

## 🚀 Local Development

1. Clone the repository:
   ```bash
   git clone https://github.com/mark-boots/f1-2026-assets.git
   cd f1-2026-assets
   ```

2. Open `index.html` in your browser:
   ```bash
   # Windows
   start index.html
   
   # macOS
   open index.html
   
   # Linux
   xdg-open index.html
   ```

That's it! No build process or dependencies required.

## 📁 Project Structure

```
f1-2026-assets/
├── index.html              # Main application
├── drivers.json            # Driver data
├── teams.json             # Team data
├── schedule.json          # Race calendar
├── assets.json            # Visual assets metadata
├── fonts.json             # Font information
├── flags/                 # Country/race flag SVGs
├── fonts/                 # F1 font files
│   ├── formula1/
│   ├── kh-interference/
│   ├── kh-interference-f1/
│   └── northwell/
└── assets/                # Logo and branding SVGs
```

## 🔄 Updating Data

Python scraping scripts are available in the development repository to fetch the latest data from Formula 1's official website. These scripts are not included in the deployed version.

## 📝 License

This project is for educational and informational purposes only. All Formula 1 trademarks, logos, and assets are property of Formula One World Championship Limited.

## 🙏 Credits

- **Data Source:** [Formula1.com](https://www.formula1.com/)
- **Image CDN:** Cloudinary
- **Fonts:** Formula 1 Official Typography
- **Developer:** [mark-boots](https://github.com/mark-boots)

## 📮 Contact

For questions or suggestions, please open an issue on GitHub.

---

**Disclaimer:** This is an unofficial fan-made project and is not affiliated with or endorsed by Formula 1, FIA, or any F1 team.
