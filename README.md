# Early Christian Events – Interactive Timeline

An interactive first-century timeline of early Christian events with map integration, search, scripture links, and historical location details.

## Features
- Searchable timeline of events from Jesus’ birth through Nerva
- Interactive OpenStreetMap with markers
- Click timeline dots to focus the map
- Rich popups with historical and modern location names
- Scripture references link to Blue Letter Bible
- Two embedded Paul’s life / missionary journey videos at the top

## How to View
1. Download or clone this repository.
2. Open `index.html` in any modern web browser.
3. Place the two video files in the `videos/` folder (see below).

## Project Structure
```
├── index.html
├── videos/
│   ├── paul_timeline_16x9-2.mp4
│   └── Pauls_Journeys_Horizontal_v3.mp4
└── README.md
```

## Videos (required for the embedded players)
Place these exact filenames in the `videos/` folder:
- **paul_timeline_16x9-2.mp4** — Timeline overview (~60 seconds)
- **Pauls_Journeys_Horizontal_v3.mp4** — Missionary journeys map animation (~70 seconds)

## Notes
- Map tiles are provided by OpenStreetMap (no API key required).
- Scripture links open on Blue Letter Bible (ESV).
- All content is self-contained in a single HTML file plus the two videos.
