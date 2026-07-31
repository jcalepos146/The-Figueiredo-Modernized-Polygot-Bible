# The Figueiredo Polyglot — Complete New Testament

A GitHub Pages-ready trilingual New Testament reader featuring the Clementine Vulgate, a historical Spanish public-domain text, the Douay-Rheims tradition, chapter arguments, and annotations associated with António Pereira de Figueiredo.

## Live website

**Read the complete New Testament edition:**  
https://jcalepos146.github.io/The-Figueiredo-Modernized-Polygot-Bible/

## Quality-of-life features

- Full-text search across Scripture, chapter arguments, and annotations
- Direct links to chapters, verses, annotations, and focused passage ranges
- Copy, citation, sharing, local bookmarking, and verse-card tools
- Latin, Spanish, and English display combinations
- Collapsible grouped navigation and keyboard shortcuts
- Continue Reading and recent-reading history
- Parchment, light, and dark themes with font, spacing, and width controls
- Annotation popovers with verse backlinks and provenance labels
- Searchable annotation index
- Clickable New Testament cross-references within notes
- Searchable glossary for archaic and theological terms
- Passage-range comparison and print-friendly formatting
- Installable Progressive Web App shell
- Accessibility improvements, including semantic controls, language tags, focus states, and reduced-motion support
- Portable self-contained HTML export after the Tomo VI texts have been stored

## Direct routes

The site supports shareable fragment links:

- Chapter: `#john-6`
- Verse: `#john-6-v53`
- Passage range: `#john-6-v35-58`
- Annotation: `#john-6-note-a`

For example:

```text
https://jcalepos146.github.io/The-Figueiredo-Modernized-Polygot-Bible/#john-6-v35-58
```

## Offline use

Matthew through Hebrews are embedded directly in `index.html`. James through Revelation retrieve their public-domain Scripture columns on first use and store them locally in the browser.

Use **Make Tomo VI available offline** to store all eight remaining books at once. Afterward, **Download self-contained edition** creates a portable single-file HTML containing all 27 New Testament books, all three Scripture columns, arguments, annotations, and study tools without a continuing network dependency for the biblical text.

## Publish on GitHub Pages

1. Upload the contents of this folder to the repository root.
2. Open **Settings → Pages** in the GitHub repository.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select the `main` branch and `/root` folder.
5. Save the configuration.

No build process or package manager is required.

## Repository contents

```text
├── index.html
├── README.md
├── manifest.webmanifest
├── sw.js
├── icon-192.png
└── icon-512.png
```

## Textual and editorial note

The biblical texts used by the site are public-domain editions. Figueiredo-related chapter arguments, annotations, condensations, and editorial supplements are identified within the interface where applicable. The site is an independent digital study edition rather than an official ecclesiastical publication.

## Commentary attributions

The commentary apparatus has been checked against the OCR scans of Figueiredo’s New Testament. All **103 formerly blank historical attribution fields** now identify Pereira or the commentator(s) named in the printed note. No blank attribution fields remain.

The files [`COMMENTARY_ATTRIBUTIONS.md`](COMMENTARY_ATTRIBUTIONS.md) and [`commentary-attribution-audit.csv`](commentary-attribution-audit.csv) record every recovered attribution and its volume locator. Labels such as **Traditional commentary** identify modern editorial syntheses and are not falsely assigned to historical authors.
