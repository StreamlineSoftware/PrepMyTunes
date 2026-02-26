# PrepMyTunes

**The all-in-one music library manager and DJ prep tool for your MP3 collection.**

PrepMyTunes helps DJs and music enthusiasts find, organize, clean, tag, and harmonically mix their local MP3 libraries — all offline, all on your machine. No uploads. No cloud. No subscriptions required to get started.

Available for **Windows**, **macOS** (Intel + Apple Silicon universal), and **Linux**.

---

## What It Does

PrepMyTunes is built around four core tools, each accessible from its own tab:

| Tab | Purpose |
|-----|---------|
| **Find My Tunes** | Import playlists from streaming services and match tracks against your local library |
| **Fix My Tunes** | Clean and normalize messy ID3 tags with 17 automated tools |
| **Tag My Tunes** | Organize your library with custom tags, ratings, genres, and favorites |
| **Mix My Tunes** | Find harmonically compatible songs using the Camelot Wheel |

---

## Find My Tunes

Import a playlist from a streaming service or a file and instantly see which tracks you already own locally.

- Paste a **Spotify, Apple Music, or TIDAL** playlist URL and import the track list automatically
- Import via **M3U or CSV** file, drag and drop, or paste content directly
- Tolerant search matching handles case differences, punctuation, extra words, and formatting variations
- View full track details: artwork, title, artist, rating, genre, BPM, key, comment, bitrate, duration
- Export matched results to **M3U** or export missing tracks to **CSV**

**Built-in audio player:**
- Artwork display with auto-scrolling title and artist
- Play/Pause, Previous/Next, and skip ±15 seconds
- Loop modes: Loop One / Loop All / Off
- ReplayGain toggle for consistent volume
- Keyboard-friendly: Space to play/pause, arrow keys to skip or navigate rows

---

## Fix My Tunes

Stop living with messy tags. Fix My Tunes runs 17 automated cleaning operations on your MP3 metadata, each with an approve/reject workflow so you stay in control.

| # | Tool | What it does |
|---|------|--------------|
| 1 | Text Normalization | Removes leading, trailing, and double spaces |
| 2 | URL Removal | Strips URLs and URL-like patterns from tags |
| 3 | Placeholder Removal | Clears "Unknown", "N/A", and similar filler values |
| 4 | "pn" Suffix Removal | Strips `_pn` / ` pn` from the end of tags |
| 5 | Parentheses Standardization | Converts `[]` and `{}` to your preferred bracket style |
| 6 | Featuring Standardization | Normalizes `feat.` / `ft.` / `featuring` to one format |
| 7 | Custom Text Removal | Remove any text you specify from all tags |
| 8 | Leading Number Removal | Strips track numbers from Title fields |
| 9 | Smart Title Case | DJ-optimized casing that preserves important words |
| 10 | Record Pool Tag Normalization | Detects and standardizes record pool identifiers |
| 11 | Artist / Featuring Split | Removes featured artists from Artist field, optionally moves info to Title |
| 12 | "The" Normalization | Moves "The" from the start of an artist name to the end |
| 13 | BPM Removal from Title | Strips BPM values accidentally embedded in Title tags |
| 14 | Filename Extraction | Auto-extracts Artist and Title from the filename pattern |
| 15 | Comment Hashtag Cleaner | Keeps only `#hashtags`, removes all other comment text |
| 16 | Underscore Replacement | Converts underscores to spaces across all text tags |
| 17 | Artwork Removal | Strips embedded album artwork to reduce file size |

Every operation includes pagination, batch approval, and a backup/restore system so you can always undo.

---

## Tag My Tunes

Build a structured, searchable library with a full tagging system.

- Assign **custom tags**, **genres**, **star ratings** (0–5), and **favorites** to any song
- **Auto-tag rules** — automatically assign tags based on folder path whenever new songs are imported
- Filter by folder, genre, tag, rating, or favorites — and combine any filters freely
- **Bulk operations** — apply or remove tags across all visible songs at once
- **Archive workflow** — move songs out of your active library to a separate archive folder in one click
- Resizable, toggleable columns — show only the fields that matter to you

---

## Mix My Tunes

Harmonic mixing tools for DJs, built around the **Camelot Wheel**.

- Pick a **seed song** — Mix My Tunes instantly finds songs from your library in compatible keys
- Results are labeled with match type badges:
  - **Perfect Match** — exact same key
  - **Compatible** — harmonically adjacent on the Camelot Wheel
  - **Energy Boost** — higher-energy compatible keys
- **BPM-based search** — find songs within a BPM range of your seed song
- Filter results further by genre, folder, tag, rating, or favorites
- **Auto-add to playlist** — songs are queued automatically as you browse
- **Mix Playlists** — organize curated sets in a nested group/playlist structure that persists between sessions

---

## AI Playlist Builder

Describe the set you want to build in plain English and let AI suggest tracks from your local library.

- Natural language prompts — "upbeat house tracks for a rooftop set at sunset"
- Advanced prompt mode for power users who want more control
- Results matched directly against your library

---

## Streaming & File Import

| Source | Method |
|--------|--------|
| Spotify | Paste playlist URL |
| Apple Music | Token-based import |
| TIDAL | Token-based import |
| M3U | File import or drag and drop |
| CSV / XLSX | File import or paste |

---

## Library Management

- Scan **multiple root folders** — the app watches for file changes and updates automatically
- **SQLite database** stores all metadata locally — no cloud required
- Incremental updates scan only changed files; removed files are pruned automatically
- Real-time file watching detects additions, changes, and deletions without a manual rebuild
- Search across title, artist, genre, and comment fields instantly
- Database reset clears the library while preserving your playlists and settings

---

## Columns & Display

Toggle visibility of any column across all tabs:

`Number` · `Artwork` · `Title` · `Artist` · `Rating` · `Genre` · `BPM` · `Key` · `Energy` · `Comment` · `Bitrate` · `Duration` · `Grouping` · `Archive` · `Select`

Columns are resizable by dragging. Headers stay sticky during scrolling.

---

## Keyboard Shortcuts

| Key | Action |
|-----|--------|
| `Space` | Play / Pause |
| `←` / `→` | Skip ±15 seconds |
| `↑` / `↓` | Navigate rows |
| `Shift+L` | Cycle loop mode (One / All / Off) |
| `Shift+Delete` | Archive current song |

---

## Languages

English · Français · Italiano · Español · Deutsch

---

## Free vs PRO

| Feature | Free | PRO |
|---------|:----:|:---:|
| Fix My Tunes | 15 songs/day | Unlimited |
| Tag My Tunes | 20 songs/day | Unlimited |
| Genre changes | 10/day | Unlimited |
| Mix Next | 10 uses/day | Unlimited |
| AI Playlist Builder | 5 searches/day | Unlimited |
| Auto-updates | ✓ | ✓ |
| Library size | Unlimited | Unlimited |

PRO is available as a monthly subscription or lifetime license, managed entirely in-app — no account required, licensed per device.

---

## Privacy

- All MP3 processing happens **locally on your machine** — your files are never uploaded
- Network access is limited to streaming service import APIs and update checks
- Optional analytics with full opt-out

---

## System Requirements

| Platform | Minimum |
|----------|---------|
| Windows | Windows 10 64-bit or later |
| macOS | macOS 11 or later (Intel & Apple Silicon) |
| Linux | AppImage or Debian package |

---

## Installation

Download the latest installer from the [Releases](../../releases) page:

- **Windows**: `PrepMyTunes-Setup.exe`
- **macOS**: `PrepMyTunes-universal.dmg`
- **Linux**: `PrepMyTunes.AppImage` or `PrepMyTunes.deb`

The app checks for updates automatically and notifies you when a new version is available.

---

## License

MIT — see [LICENSE](LICENSE) for details.

Built by [Streamline Software](https://streamline-soft.com).
