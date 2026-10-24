# Prep My Tunes

**Find. Fix. Tag. Mix. The all-in-one music library manager and DJ prep tool for your local collection.**

Prep My Tunes helps DJs and music enthusiasts find, organize, clean, tag, cue and harmonically mix their local MP3 and FLAC libraries - all offline, all on your machine. No uploads. No cloud. No subscriptions required to get started.

Available for **Windows**, **macOS** (Intel + Apple Silicon universal), and **Linux**.

---

## What It Does

Prep My Tunes is built around eight tools, each with its own tab:

| Tab | Purpose |
|-----|---------|
| **Find My Tunes** | Import playlists from streaming services, files, or radio charts and match them against your local library |
| **Fix My Tunes** | Clean and normalize messy tags with 20 automated tools, including lossless volume leveling |
| **Tag My Tunes** | Organize your library with custom tags, ratings, genres, favorites, and auto-tag rules |
| **Mix My Tunes** | Find harmonically compatible songs, build playlists, and mix live with SmartMix |
| **Dedupe My Tunes** | Find duplicate tracks and keep only the best copy |
| **Cue My Tunes** | Set DJ hot cues on a waveform and write them into your files, or cut a section out of a track into a new file |
| **Get My Tunes** | Pull missing songs from an archive drive, NAS, or cloud folder with download rules |
| **Play My Tunes** | Just listen: browse your whole library by folder, genre, tag or playlist, filter it, and press play |

A guided onboarding walks new users through their first scan, and every tab opens its Quick Tour by itself the first time you land on it, so you are never staring at an empty screen wondering what to click. Every tour can be replayed later from that tab's Quick Tour button.

---

## Find My Tunes

Import a playlist from almost anywhere and instantly see which tracks you already own.

- **One side panel** holds every way to add songs - AI playlist, Playlist link, Charts and Lists, From a file, Add one song - and your saved playlists, last changed first, with a search box, the open list lit in place so the next one in the same group is one click away, and a **Mass Update** button that refreshes every ticked playlist in one click. Mass Update **shows what it will change first** (songs added and removed, links fixed, per playlist, nothing saved until you press Apply), backs up every playlist it changes, and **Undo last Mass Update** puts them all back, M3U files and Serato crates included. While the playlist is empty, the same ways to add songs sit in the middle of the tab as well, one click each
- **One set of import options** for every way of adding songs: add new songs below the list or replace it, select every version found, and add similar songs picked by AI
- Paste a **Spotify, Apple Music, TIDAL, YouTube, or YouTube Music** playlist URL and import the track list automatically
- **Charts and Lists** opens right in the tab: SiriusXM airplay charts (the most-played songs of the week on 150+ music stations, no account required), Billboard's Year-End Hot 100 from 1946 to 2025, Apple Music, Deezer, Shazam and radio charts, ready-made Spotify Samples, or a pasted tracklist. **Pick a chart and see which songs you already have before you import** - every song shows how many versions you own or that it is missing, and nothing is added until you press Import. Billboard years you already saved are marked, and open your saved list in one click
- Import via **M3U, CSV, or XLSX** file, drag and drop, or paste content directly. An imported file is **saved as a playlist straight away** (in an "Imported" group, with Undo), with the export settings you used last so it auto-exports like your other playlists, ticked for Mass Update, and importing the same file again updates that playlist instead of making a copy. Each line keeps its one best match ticked - the line's own file when your library has it - and the other versions stay in the list, unticked
- **Set lists or crates** - each saved playlist is either "Keep exactly these songs" (Exact) or "Include every version" (All versions). Mass Update never adds songs to an Exact list, it only fixes its links; an All versions list picks up every new version of every song, as before. Change one list from its chip, or a whole group at once, with a single Undo. Playlists you already have start as All versions, so nothing changes until you choose
- **Import Playlist Folder** (PRO) - point at the folder your DJ software exported its playlists to and every .m3u / .m3u8 underneath is imported in one go, with the folder structure mirrored into your playlist groups. Tick the box in the import dialog and it also writes a fresh .m3u for each one into your export folder, in the same folder structure, with the paths pointing at your own copies of the tracks, and keeps that same file up to date when you change the playlist later
- Tolerant search matching handles case differences, punctuation, extra words, and formatting variations
- **Folder filter** - a dropdown beside the search box lists only the folders the current playlist actually uses, each with a song count. Pick one and the list shows just those songs (groups with nothing in that folder drop out), and skipping to the next track stays inside that folder, so working through the copies sitting in a Temp or Downloads folder is one click
- Green/red rows show at a glance what was found and what is missing
- View full track details: artwork, title, artist, rating, genre, BPM, key, energy, comment, bitrate, duration
- Export matched results to **M3U** or export missing tracks to **CSV**
- **Send to DJ apps** (Settings > DJ software) - a **"Tags changed" list** collects every song whose tags the app changed, so after tag work your DJ app reloads one list instead of your whole library (VirtualDJ: right-click it, Batch > Reload Tags). Pick playlist groups to send to **Serato as crates** (PRO, like every automatic playlist export), inside a PMT crate with no drag and drop: crates are only written while Serato is closed (they wait and go in when you close it), and a crate you changed in Serato is never replaced without asking. The app also warns when VirtualDJ's sidebar does not show your playlist folder, and never replaces a DJ app's own library file
- Send missing songs straight to **Get My Tunes** as download rules, one track or the whole playlist at once, or every song in the playlist, found or missing
- **Saved Playlists** shows everything you have saved as an expandable **tree** - groups and playlists together, with folder and playlist icons, so a group that holds nothing but subgroups opens to show them instead of looking empty. Expand or collapse the lot in one click, sort and search across every group at once (the search opens the branches it matches), see at a glance which playlists **auto-export** (an M3U or Serato badge on each, with the export folder in its tooltip, also shown in the Find panel; filter to the ones with **No M3U export** and turn it on for all of them at once with **Turn on M3U export**, PRO), rename or delete a group, **Move** any playlist into another group at any depth taking its auto-exported .m3u with it, and **Move a whole group** - subgroups, playlists and all - somewhere else in the tree. The same ticks that pick playlists for Mass Update also drive **Move Selected** and **Delete Selected**: tick playlists (or a folder to take everything inside it), then move them all into one group in a single step, each auto-exported .m3u following along, or delete them after a confirm that names every playlist about to go and warns you when the ticks cover your whole collection. **Remove empty groups** clears out the leftovers an interrupted folder import leaves behind: it lists every group that holds no playlists anywhere inside it, names them before it touches anything, and skips any group a playlist has landed in since. However you work through the list - deleting, renaming, opening or closing a folder - it stays exactly where you left it instead of jumping back to the top
- **Fix broken links** - when a playlist points at a song file that has moved, it finds the file again: where the app moved it, the same audio, the same file name and length, or a slightly different file name. It shows what it found before anything changes (fixed automatically, likely, needs your choice, only in an archive folder, not found), never links to an archive folder or picks between versions for you (not even an archived copy you chose before), always does what you picked for each song (or one answer for every song you select, with a line saying what each answer does), and keeps each song's tick and place in the list. Filter Saved Playlists to the lists with broken links, fix them all in one go, **Look in a folder** for songs you moved yourself, and Undo if you change your mind. After a Dedupe archive, one click points your playlists at the copies you kept, every fix is remembered for next time, Update and Mass Update fix links before they remove anything, and **Old exports** moves playlist files nothing updates any more out of your DJ app's view, deleting nothing

**AI Playlist Builder:** describe the set you want in plain English ("upbeat house tracks for a rooftop set at sunset") and AI suggests tracks matched directly against your library, so every result is something you actually own. Choose which music folders AI lists may use in Settings > AI, down to a single folder inside one, so a folder of stems or raw downloads stays out.

- **Build a set for an event** - pick a wedding, bar or club night, school dance, corporate event, birthday, holiday party, brunch or theme night, then the whole event or one part of it (Cocktail hour, Open dance floor, Last call...), and the event is the request
- **Clean rule** - Strict ticks only Clean files, Prefer ticks a Clean file when there is one, and a song with no Clean file is flagged for you to check
- **Do not play and Must play** - leave songs out by title, Title - Artist, #tag or crate, keep a list of songs you never play for every AI list, and pin the songs that have to be there, to a part if you like
- **Set length in minutes** - the app works out how many songs fill the time, or ask for a number of songs
- **Set flow order** - the finished set comes back in playing order: energy that builds and eases, steady tempo steps, and the same artist kept apart
- **Balance line** - under the playlist name: running time, decades, top crates, clean / unknown / explicit counts, missing songs and artist repeats, in amber when a Strict set holds an explicit file
- **Build from My library** - the AI searches your own library by tags, crates, Clean, BPM and energy, so every song is a file you own, with an option to add a few songs you don't own as a shopping list
- **Fast or Better model** - with your own OpenAI or Anthropic key, pick Better (slower) in Settings > AI for a larger model; the shared keys and Gemini stay on Fast

**Your own AI keys, in one place:** AI is used in more than one tab, so the OpenAI, Gemini and Anthropic keys live on their own AI tab in Settings and apply everywhere at once - the AI Playlist Builder, SmartMix suggestions and every chart or playlist import panel. Each key has its own on/off switch, so you can keep a key saved without spending it. The app ships with shared keys and works without any of this; adding your own raises the result limit from 50 to 300. Keys are stored on your machine and go to the provider you picked through the Prep My Tunes server.

**Built-in audio player:** artwork display, play/pause, previous/next, skip, loop modes, and keyboard-friendly controls - available on every tab.

---

## Ask the assistant

A button at the top of the window opens a built-in assistant you can ask how to do things: "what is an energy boost", "can I undo a fix", "how do I get songs off my archive drive". Answers are short, and usually come with a button that takes you straight to the tab in question.

**It cannot see your music.** Not as a promise but as a matter of how it is built: the assistant answers from a written guide to the app that lives on our server, and the only thing your computer sends is the words you typed. It has no access to your library, files, folder names, tags, playlists or settings, and it cannot change anything. Ask it to do something for you and it explains where in the app you do it yourself.

It also only knows what is in that guide. Ask it something the guide does not cover and it says so rather than guessing, because a confident wrong answer about your library is worse than no answer.

Requires being signed in. Every account gets a monthly allowance of questions, and PRO gets a much larger one; the window shows roughly how many you have left. If you run out, add your own Anthropic key in Settings > AI and it stops counting against our allowance entirely.

---

## Fix My Tunes

Stop living with messy tags. Fix My Tunes runs 20 automated operations on your library, each with a full before/after preview and an approve/reject workflow so you stay in control. The text tools cover every text tag, including Album Artist and Disc #, since that is where remix packs hide their promo links too.

| # | Tool | What it does |
|---|------|--------------|
| 1 | URL & Pattern Removal | Strips URLs and URL-like patterns from tags, tidying the spaces they leave behind |
| 2 | Basic Text Normalization | Removes leading, trailing, and double spaces |
| 3 | Remove Empty Placeholders | Clears "Unknown", "N/A", and similar filler values |
| 4 | Remove "pn" Suffix | Strips `_pn` / ` pn` from the end of tags |
| 5 | Standardize Parentheses/Brackets | Converts `[]` and `{}` to your preferred bracket style, puts a space between groups that touch (`)(` becomes `) (`), and brackets remix types left bare at the end of the title ("My Song Quick Hit" becomes "My Song (Quick Hit)") |
| 6 | Standardize Featuring Artists | Normalizes `feat.` / `ft.` / `featuring` to one format |
| 7 | Remove Custom Text | Remove any text you specify from all tags |
| 8 | Smart Number Handling | Strips leading track numbers from Title and Artist fields, with a per-field ignore list so names like "50 Cent" survive |
| 9 | Smart Title Case | DJ-optimized casing that preserves important words |
| 10 | Standardize Record Pool Tags | Detects and standardizes record pool identifiers |
| 11 | Artist Name Processing | Removes featured artists from the Artist field, optionally moves the info to Title |
| 12 | Normalize "The" Prefix | Moves "The" from the start of an artist name to the end |
| 13 | BPM Removal | Strips BPM values accidentally embedded in Title tags, plus key/BPM/energy stamps left at the end of the title, old ones included |
| 14 | Extract Tags from Filename | Auto-extracts Artist and Title from the filename pattern |
| 15 | Remove Non-Hashtag Text | Keeps only `#hashtags`, removes all other comment text |
| 16 | Replace Underscores with Spaces | Converts underscores to spaces across all text tags |
| 17 | Remove Artwork from Files | Strips embedded album artwork to reduce file size |
| 18 | Convert PNG Artwork to JPEG | Re-encodes PNG cover art as JPEG at the same size, keeping the picture and dropping most of the bytes |
| 19 | Fix Track & Disc Numbers | Finds Track # and Disc # fields holding links or text instead of a number and clears them, keeping any real number stuck to the junk. Vinyl positions like A1 are left alone |
| 20 | Level Volume | Makes every MP3 play at the same loudness, the MP3Gain way: the volume field inside each frame is moved in 1.5 dB steps, so nothing is re-encoded, nothing is lost, files keep their dates and Restore puts it back exactly. Pick 89 dB, 92 dB or a LUFS target; a "never let a song distort" guard raises quiet tracks only as far as their peaks allow. This is the leveling DJ software actually hears, because Serato, VirtualDJ, rekordbox and Traktor all ignore ReplayGain tags |

Level Volume works from the **Measure Volume** step in Analyze My Tunes, which measures each track's loudness (EBU R128) and peak once, alongside the BPM and key analysis, without writing anything to the file.

All 20 tools sit in one list on the left, each showing how many songs it would fix (or All Clear), with a Show filter for To fix, All clear, Manual only and Hidden. Click one and its songs open on the right, one line per song with the value now and after the fix, 25 to a page. The top row says how many songs were checked and how many fixes are waiting, and Mass Approve shows its progress right on the page, counting each tool down song by song as the files are written.

Every operation includes pagination, batch approval, and a backup/restore system so you can always undo. When the OS blocks a write (for example macOS folder permissions), you get a clear explanation and how to fix it instead of a silent skip.

**The backup is written before the first file is touched, not after the last.** A bulk run records each song's original tags immediately before changing it, so stopping the run part way, closing the app, or losing power still leaves everything already changed sitting in Restore. If a backup cannot be created at all, the run does not start. Restore puts back every tag field a fix touched, and the backups hold only the old and new text of your tags, never the music, so even a run over a hundred thousand songs is a few megabytes.

Tools 7, 8 and 14 are marked **Manual only**: they are left out of Mass Approve, because they are too blunt to run blind across a whole library. Tool 8 does have its own Approve all inside the section for when you have scanned the list and every row is right. Before it runs it shows you real examples of the artist names it is about to change, and asks separately about the Artist field, so you can fix every title in one press and still go through the names one at a time. When one of those hand-approvals leaves the song eligible for a different tool, the section tells you which tool picked it up and offers a Mass Approve button to clear it.

---

## Tag My Tunes

Build a structured, searchable library with a full tagging system - stored in standard tag frames so it travels with the file.

- Assign **custom tags**, **genres**, **star ratings** (0-5), **energy levels**, and **favorites** to any song. Give each tag its own color (right-click it in the palette) and it shows in that color in every tab. To reorganize the palette, Shift+click several tags and drag them onto another tab in one go. Tag with Shift+number shortcuts? Fold the palette down to its tabs row and give the song list the space
- **Genre management** with approved-genre lists, keyboard shortcuts for one-keystroke re-genreing, and a shared searchable genre picker - type a genre that is not listed yet and add it as an approved genre right there. Two spellings of the same genre (Trance and trance) are flagged where they are approved, and merge into one entry with a click
- **Genre replacement rules** - tell the app once that "00 hip hop" should be "2000s Hip Hop" and every song carrying it is re-tagged, straight away and again whenever new downloads turn up with it. Set a rule from any genre waiting for approval, or right-click a misspelled genre right in the Tag My Tunes track list, or filter the list (say, every spelling of disco), select the lot and map them all to one genre in a single step - each waiting genre shows how many songs carry it, so you can start with the big ones; after each library scan you get a one-click prompt, or tick "Apply automatically" to let it happen on its own. When a batch of rules is no longer needed, filter the rules list, select them all and delete them in one go. It also runs as a step in Analyze My Tunes, and it never moves your files
- **Genre suggestions** - every genre waiting for approval shows the closest approved genres, best first and marked High, Medium or Low. They learn from your own replacement rules (your habits, like Pop winning over House), from the genre names however they are written, and from the genres the other versions of the same song already have. Click the one that fits to make the rule, or review all the High ones and make those rules in one go; songs only change after you confirm
- **Record pool from the file name** - the app reads which record pool a download came from out of its file name (the pool's own tag, its in-house editors, remixers only that pool has, its naming style) and writes it into the Comment as a #tag, the Album or both, for example #Crate-Connect or #DJ-City. 46 pools are known and about 98% of the pools written are right. Turn it on and every library scan tags the songs it just added, or tag your whole library in one go after a count and a confirm; names that only give a weaker clue are suggestions you turn on and tick, grouped by pool so one box ticks a whole pool, and every run makes a backup first
- **Remixer and remix type from the file name** - the same idea for the version part of the name: 114 remixers and editors (DJ-Rukus, The-Goodfellas, Starjack...) and 47 remix types (Intro, Redrum, Quick-Hit, Short-Edit, Acapella-In...) are added to the end of the Comment as #tags, each only once and never touching the rest of your text. The artist and the song title are never read, so "The Final Countdown" is not a countdown edit. Clean / Dirty and writing the remixer to the Remixer tag are options; new songs can be tagged after every scan, or your whole library after a count and a confirm, with a backup first
- **Tags from file names, your way** - Settings > Tags from file names lists every record pool, remixer and remix type with how many of your songs it matches. Untick one and it comes out of the Comment on the next run (only on the songs it tagged), rename a value (Club-Killers to CK) and tagged songs get the new name, give each kind an emoji in front so they sort together, or add your own "File name contains" rule. One search box covers all three. On the Tag tab, a small card shows what the clicked song's file name gives: right-click a value to rename it or turn it off. With the tagging on, the tag palette gets Record Pool, Remixer and Remix Type tabs listing every value, so they count as your own tags
- **A compact layout** - the tag tabs, Filter tags and Auto-Tag share one slim row, and the folder's name, its song count and every bulk action share one line, so more songs fit on screen. Select some songs and every tag shows where it stands: a full tag with a check is on all of them, an outlined one with "3/5" is on some, a faded one is on none, and each tab counts how many of its tags the selection carries. A song's tags stay on one line, with "+5" opening the rest
- Filter by folder, genre, tag, rating, or favorites - and combine any filters freely. A filter in use says what it is set to ("Has tags: #wedding"), and Has tags / Doesn't have tags can match any or all of the tags you tick
- **Folder filter** - a dropdown on the filter row lists only the folders whatever you have loaded actually uses (a playlist, a genre, a tag, a folder), each with a song count. Pick one and the list narrows to those songs, so you can work a playlist's tracks one folder at a time without leaving the tab
- **Search the Browse By panel** - type part of a name and the tree narrows to what matches, opening the folders above it so the match is on screen. It searches whatever the panel is set to: folder names, genres, your own tags, or your saved playlists and the groups they sit in
- **Move several playlists at once** - in the Playlists view, Ctrl/Shift+Click the playlists you want and drag them onto another group, or right-click and choose Move to group. They move together from wherever they were, for Find My Tunes and Mix My Tunes playlists alike, and an auto-exported .m3u follows its playlist into the new group's folder
- **Bulk operations** - apply or remove tags across all visible songs at once
- **Undo last file edit** - right-click a song and put back exactly what the file held before the app's most recent edit to it: tags, cues, rating and cover art, byte for byte, one step at a time. Only the part of the file an edit replaces is kept for this, never a copy of the whole track, so edits stay fast on big mixes and external drives. If another app changed the song since, you are asked first
- **File songs by genre** - auto-move a song into its genre folder when you change its genre, and use the "Not in genre folder" filter plus the Move to Genre Folder button to file songs whose genre was already correct, such as fresh downloads. A Main Music Folder setting keeps every genre folder in one place when your library spans several folders. Your playlists follow the song to its new folder, and each auto-exported .m3u is rewritten straight away, so your DJ software never sees a broken link
- **Archive workflow** - move songs out of your active library to a separate archive folder in one click
- Resizable, reorderable, toggleable columns - key, BPM, track length, genre, rating, plays and more; show only the fields that matter to you, click a heading to sort, and right-click any column heading for a checkbox list that stays open while you tick

**Auto-Tag rules** go far beyond folder-based tagging:

- Automatically apply tags based on folder path whenever new songs are imported
- **Match on the field you actually think in** - filename, folder path, any #tag, artist, title, comment, genre, or "is a favorite". Genre matches the file's own genre tag, so "Genre contains House" can hand every house track a tag in one pass
- **Target one exact folder** - "Folder Is House" matches only the folder named House, never Deep House or House Classics, and "2025/House" pins it to the House folder inside 2025
- **Tag by playlist** - "In Playlist" tags every song on one of your Find My Tunes or Mix My Tunes playlists, or on any playlist inside a playlist group, nested groups included. File your wedding playlists in a Wedding group and one rule tags all of them #wedding
- **Embed album covers** - attach a cover image to any rule and stamp it onto every matching MP3/FLAC, with a reusable cover library, smart resizing (covers are embedded as compact JPEG, never a multi-megabyte PNG), and an "overwrite existing artwork" toggle
- **Refresh covers you already applied** - "Update mine" tells a rule to also replace covers PrepMyTunes put on before. It clears itself after each run so it can never re-apply covers behind your back, and an All/None button in the footer re-arms every cover rule at once instead of one checkbox at a time
- **Design covers in-app** - build clean cover art with text, colors, fonts, emoji, and image backgrounds, no image editor needed
- **See what a rule matches as you type it** - while you write a rule, a live count says how many songs in your library it would match and names a few, and a "How matching works" box explains the text with examples (any case, anywhere in the name, no wildcards). A rule that matches nothing, or more than half your library, asks before it is saved
- **Preview before running** - see every affected track's before/after, with added tags highlighted
- **Always your whole library** - rules count and run across every song in your database, so no setting can quietly limit a run to the songs on screen
- **See where you stand** - a status line says when the rules last ran and how many songs that run updated, and counts your library for the ticked rules: already tagged, left to tag, and not matched. Hover a rule's count to see when that rule last ran
- **Priority ordering and filtering** - drag rules into the order they should run, and filter a long rule list as you type
- **Clean up in bulk** - Ctrl+click or Shift+click rules, or select every rule the filter shows, and delete them all with one confirmation. Rules hidden by the filter are never touched
- **No accidental duplicate rules** - add a rule whose condition already exists and you are shown the combined result first, with the choice to merge the two into one rule or keep them separate. Rules that already overlap are flagged in the list
- **Activity log** - review every file a rule updated, with the tags added and cover applied

---

## Mix My Tunes

Harmonic mixing tools for DJs, built around the 12-position harmonic wheel (1A-12B notation). Key tags in note names ("Gm", "F♯m"), harmonic codes ("6A") or Open Key ("1m") are all read.

Pick a **seed song** and instantly see compatible tracks from your library, labeled by match type:

| Match type | What it means |
|------------|---------------|
| **Perfect Match** | Identical key - smoothest blend |
| **Mood Change** | Relative major/minor - same notes, mood flips |
| **Energy Boost** | One step up the wheel - lifts energy |
| **Big Boost** | Two steps up - a bigger lift |
| **Energy Drop** | One step down - eases energy |
| **Diagonal Mix** | One step up or down plus a major/minor flip |
| **Mood Shift** | Parallel major/minor - a bolder mood change |

- **BPM-based search** - find songs within a BPM range of your seed song
- **Every match counted** - each match type button shows how many songs it would give with your other filters on, and the Play My Tunes panel of folders, genres and playlists on the left shows how many of each one's songs match the seed. Click one to see only its matches; every count updates as the seed changes, and the ones with no matches are left out (a setting brings them back)
- **Energy at a glance** - a small meter under each energy level, green for 7-10, yellow for 4-6 and red for 1-3
- **A compact layout** - the seed song, SmartMix Live and your playlist share one top row, so about 16 songs show at once on a 1900-pixel-wide screen
- **Deep filtering** - stack filters on genre, energy, BPM, rating, tags, favorites and more; each filter button says what it is set to, and tag filters show your tag groups side by side with an Any / All switch. Save any combination as a named preset with an optional keyboard shortcut, and pick presets from one menu with your groups as columns
- **Open a playlist in Play My Tunes** - from the list of playlists a song is on, to look through it and play it without searching again
- **Played tracking** - songs are flagged as played automatically when you drag them into your DJ software (or with one click), an optional setting marks every other version of the song (radio edit, club mix, extended mix) along with it, and a **Hide Played** button in both the main list and SmartMix Live hides everything you have already played when you only want fresh options late in a set
- **Mix Playlists** - organize curated sets in a nested group/playlist structure with renameable groups; save in-app, export to **M3U**, or export straight to a **Serato crate**
- **Bulk playlist import** - point at a folder of playlist files and the folder structure is mirrored into playlist groups
- **AI suggestions** - ask for a set built around the current seed and your filters, matched against your library

**Track analysis, in-house:** analyze your library to detect **BPM**, **musical key** (written in harmonic notation), and a **1-10 energy level** - no third-party analysis tools required. Values are written to the file tags, including "Energy 7" in the Grouping field where Serato, VirtualDJ, rekordbox, and Traktor display it, and custom energy level names to Comments or Composer.

One **Analyze Songs** button runs the lot: tick BPM and energy, key detection, or both, and each song is read and decoded a single time for everything you ticked rather than once per job. Your ticks are remembered, every job skips the songs that already have its data, and each row shows how many are still waiting. With writing to file tags switched on, a run also writes any BPM, energy or key an earlier run saved only to your library, so your tags catch up in the same pass.

### SmartMix Live

A floating popout window built for the DJ booth:

- **Listens to VirtualDJ or Serato in real time** - the seed automatically follows whatever is playing on the decks
- **DAW mode** - no DJ software needed: search for a seed inside the popout, drag matches straight into Ableton or any DAW, and each dropped track becomes the next seed
- **AI suggestions on the floor** - get AI-picked matches for the current seed without leaving the popout, with provider choice (OpenAI/Gemini) and a BPM tolerance picker. Uses your own API key when you have one switched on in Settings > AI
- **Full column set** - artwork, title, artist, match, key, BPM, grouping, genre, rating, plays, tags - resizable, reorderable, and individually toggleable, straight from a right-click on the column headings
- **Independent filters** with saved presets, so the floor view never disturbs the main window - laid out like Mix My Tunes, every filter is one click away above the list and says what it is set to, and the list keeps the full window width
- **Browse By in the popout too** - the same folder, genre, tag and playlist panel on the left, counting the matches for the seed with the popout's own filters; fold it away when the popout is narrow
- **Always-on-top** option, a global **Ctrl+L** shortcut that works even when your DJ software has focus, and an optional **minimize-to-screen-edge tab** so the list tucks away and comes back with one click - drag the tab along its edge, or to a different edge, and it stays where you put it
- **Full screen and back in one click** - a title bar button (or **Ctrl+Shift+F** / **Cmd+Shift+F**) fills the screen, then restores the window to the exact size and position it had before; the size is remembered between sessions
- **Hide while dragging** - the SmartMix windows disappear the moment you drag a song out and reappear when you drop, so a floating popout never blocks the deck or crate you are dropping onto (on by default, with a setting to turn it off)

---

## Dedupe My Tunes

Find and clean up the duplicate copies that accumulate across years of pool subscriptions and re-rips.

- **Smart grouping** by normalized title + artist - ignores brackets, mix labels, and edition tags so "Levels (Original Mix)" and "Levels - Radio Edit" land together
- **Audio matching** compares the actual audio so renamed files still group correctly
- **Keep-best heuristic** picks the best copy in each group based on bitrate, duration, tag completeness, file format, and folder priority - all configurable
- **Misleading bitrate flag (PRO)** - track analysis also listens for files that claim a high bitrate but were re-encoded from a lower quality source (a common trait of video-site rips), and marks their bitrate with a warning badge wherever a bitrate is shown. Keep-best ranks a flagged copy by the quality it really has, so a fake 320 no longer beats a genuine 256, and the "Real quality below" archive rule catches the fakes that a plain bitrate rule lets through
- **A compact layout** - Match On, Scan, Best Priority and the rule buttons share one row at the top, one line holds the counts, the filter and Sort, and the duplicate groups get most of the window. Best Priority shows your order on its button and opens the full list in one click
- **Bulk rules across your whole library** - Keep rules and Archive rules apply to every track, not just duplicates, so "archive anything under /Old Pool/" or "always keep my 5-star tracks" works on unique tracks too. Each rule row shows how many tracks it will affect before you run it, and Preview lists them. Where a track does have duplicates, the group is still protected so a song never loses every copy
- **Change genre and file from the duplicate list** - every row has the same genre picker as the other tabs, and right-click > Move to Genre Folder files the copy you are keeping into its genre folder without leaving the tab
- **Tag while you dedupe** - the tag and genre keyboard shortcuts from Tag My Tunes work in the duplicate list too (Shift + number toggles a tag, Ctrl/Cmd or Alt + number applies a genre), alongside Delete to mark for archive and Ctrl/Cmd + K to keep
- **Hide Kept** - one tick hides the copies you have already flagged Keep, so a pass after adding new music lists only the versions still waiting on a decision. A group whose copies are all kept drops out of the list, and the setting is remembered
- **Bulk archive** moves every duplicate to a designated archive folder in one operation, with full undo via the move history

---

## Cue My Tunes

Set DJ hot cues on a zoomable waveform and write them straight into your tracks.

- **A big waveform, and the whole track at a glance** - the waveform takes most of the window, with a strip above it showing the whole track and every cue; zoomed in, drag the box on the strip to move along the song. A ruler gives the time and the bar numbers from your beat 1, and each cue card shows its time, bar and how many bars its section runs. Tips and keys lists every shortcut
- **Pick your crate in one click** - one Browse button lists All Tracks or a single folder, genre, tag or playlist, with every folder's song count; the Show menu narrows the list to tracks with or without cues, or to the ones still needing review
- **Reads the cues you already have** - cues embedded by other DJ tools show up ready to fine-tune, and every track with cues is marked in the list
- **Know what you have checked before a gig** - each track shows whether its cues were placed by Auto-Cue and not touched since, edited by hand, or confirmed by you with the Confirm cues button. Pick Needs review in the Show menu to see every track whose cues nobody has confirmed yet. Changing a confirmed track's cues, here or in another DJ app, takes the confirmation away again
- **Auto-Cue a whole folder at once** (PRO) - the wand beside any folder, genre, tag or playlist, or the Auto-Cue step in Analyze My Tunes, cues every track that has none yet. It never replaces cues you placed, edited or confirmed, or cues from other DJ software: each file is checked again just before it is written and left exactly as it was if it already holds someone's cues. Every track it cues is marked Auto-cued, ready to review. It plans each track on the grid you see in the editor - your Set Beat 1, your grid tempo, the tempo you picked and your Mix Out beat included - so re-cueing a folder never undoes a grid you fixed
- **Start a batch over** (PRO) - the eraser beside the same folder, genre, tag or playlist removes the cues Prep My Tunes wrote from every track under it and marks them as uncued again, so the wand can cue them afresh. Cues from other DJ software are never touched, a track whose cues changed outside the app since is skipped and counted, and every file is backed up first
- **Saves in the Serato format** that Serato reads directly and VirtualDJ imports from tags, plus **export to rekordbox, Traktor, and VirtualDJ**
- **Timed for the app you play out of** - Serato and VirtualDJ read cue timing in MP3 files slightly differently (up to about 25 ms on most MP3s), so choose your main DJ app in Settings and cues and beat grids land exactly on the beat there. Cues you have already saved are never moved by changing it
- **Auto-Cue** locks onto the track's beat grid and drops a starting set of cues on phrase lines, placed where the energy shifts and where the vocal enters or leaves. The first is named INTRO and the last MIX OUT - placed exactly on your Mix Out beat when you have set one, and both names are yours to change in Settings if you call them something else; the ones between are numbered (Cue 2, Cue 3...) for you to name the way you work; Snap aligns cues to the nearest transient on the beat however you place them - dragging a marker, clicking the waveform, or pressing Insert while the track plays - and pulls a dragged grid onto a cue you have already placed
- **Name a whole track in one go** - click a cue's name, on its card or on the waveform, and pick a label: the menu moves straight on to the next cue, so every cue gets its name in a row without the mouse leaving that spot. Your presets come first, numbered for the 1-9 keys, and the arrow keys step between cues. Type a name of your own and press Enter to use it for that cue only, or Shift+Enter to keep it as a label for next time; a name used once can be saved later from the same menu or the cue's right-click menu. The Presets sit beside the cue cards, one click or a drag away from any cue
- **Cues that land on the beat in your DJ software** - Auto-Cue uses the beat grid already in the file where there is one, and writes a grid itself when there is not, so VirtualDJ draws the same beats the cues were placed on instead of guessing its own. Auto-Cue never overwrites a grid written by other DJ software; when you set beat 1 by hand and the file's grid disagrees, Save asks before putting yours in its place
- **Stale and intro-only grids are caught** - a grid left behind by an earlier edit drifts, so where one disagrees with the track's own BPM tag, Auto-Cue re-measures the tempo at several points across the whole track and cues on whichever holds up. Tracks that genuinely change tempo, where no single grid is right, are cued on the tag and flagged with a "Tempo varies" note rather than quietly drifting
- **Set Beat 1, or drag the grid onto the beat** - when a grid is off, click Set Beat 1 and then the first beat on the waveform, or grab the tab at the top of any grid line and slide the whole grid until it sits on the drum hits: the phrase grid, snapping, and Auto-Cue all follow your mark, outranking anything detected or embedded. Only beat one moves, never the tempo, your mark is remembered per track, and Undo puts the automatic grid back. Everywhere below the tabs the waveform still pans, so a grid you have lined up cannot be knocked out of place
- **Set the Mix Out beat, and the tempo measures itself** - beat 1 says where the grid starts; Set Mix Out Beat says where it still has to be right. Both buttons zoom the waveform right in on the beat you are about to mark, so it is easy to hit exactly: beat 1 onto the start of the track, and Set Mix Out Beat onto the mix out the track already has - your OUT mark if you have placed one, or the MIX OUT cue if you have not - so you can see where it falls and nudge it instead of winding back from the end. On a track with no mix out yet it opens at the end, on the last hit you can actually hear rather than into a fade. Mark the first beat of a bar as far into the track as you can place it and the tempo comes from the distance between the two marks, with the number of beats between them measured from the audio rather than counted against the tempo already drawn. Neither mark snaps, whatever the Snap box says, because the marks are what make the grid, and the grid runs exactly through both of them: beat 1 on its mark and the grid line at your mix out on the OUT mark. The count appears in a pill you can correct by hand, a beat or a whole bar at a time, and the tempo follows as you go. When the track's BPM tag and the app's own analysis agree on a tempo, a count that contradicts both gives way to theirs, so a shuffle rhythm cannot talk the grid down to three quarters of the real tempo. Cues Auto-Cue placed follow the new grid by themselves, MIX OUT included, so there is no second Auto-Cue to run; cues you placed or changed stay exactly where you put them. Placed a mark wrong? Click either button again to place it anew, or, while Grid is the tempo in use, Clear grid to remove both marks and the grid tempo and take the grid off the waveform. Just want to look? The magnifier beside each button zooms straight in on beat 1 or the mix out and changes nothing
- **Hear where your mark lands** - in a breakdown or a percussion bed there is no drum hit to aim at, so while you are placing either mark, right-click the waveform: the playhead drops a bar before the line under your cursor and plays, and you hear the spot you are about to mark. Nothing moves - the line stays under your cursor and the view stays where you put it - so you can listen, nudge and listen again, then left-click to place it
- **Three tempos, and you pick one** - the BPM above the waveform shows the file's own tag, the tempo your marks give, and Prep My Tunes' own measurement, side by side. Click one and the beat grid, snapping and Auto-Cue all run on it. When a tempo reads exactly half or double what the track runs at, the /2 and x2 buttons beside them correct the one in use and the grid follows. Picking, halving and doubling write nothing to the file's BPM tag, so you can try each against the waveform; a Write to file button carries a tempo into the BPM tag when you want it to, and asks first
- **Pick an empty tempo to clear the grid** - a grid you know is wrong comes straight off the waveform: click a tempo that has no value and the lines go with it, because a grid with no tempo is no grid. Your marks are untouched, and picking a tempo that does have a value brings the grid back
- **Your BPM tag is never overwritten** - the grid tempo is fractional and is kept with the track and in a tag of its own, in full, so it travels with the file without touching the BPM tag other DJ software reads. Right-click either number to type a tempo by hand - the file's tag or the grid's - without changing which one the grid is running on
- **Decimal BPMs, everywhere** - a BPM tag of 122.78 reads as 122.78 in every list, in the Cue editor's tempo chips and in Cut My Tunes, and a tempo you write to the tag keeps its decimals too (a whole number stays a whole number). A beat grid that was written at the whole number below a decimal tag is drawn at the tag's real tempo, so the lines stay on the beat to the end of the track
- **See the song's sections** - a strip under the waveform shows the INTRO, VOX, AD-LIB, BEAT, BUILD, DROP, BREAK, BKDN and OUTRO, read from the audio in 4-bar blocks on the beat grid you see, so they move when you set beat 1 or pick another tempo. Point at one for its bars and how sure the detection is, click it to jump there
- **Follow the drummer** - for a song whose tempo moves, Cue can draw its bar lines from a beat map of the drums, so the grid follows the drums from start to end. Amber marks show stretches with no clear drums, rushed fills and slips, a "Beat 1?" button offers the choices when bar 1 is uncertain (point at one and the waveform shows where bar 1 would go before you click), and a check-by-ear click plays on the map's beats. Auto, Always and Never each say in plain words where the grid lines go. Nothing is written into the file
- **The Remix waveform in seven palettes** - the 3-band waveform from Remix My Tunes, bass in front, mids behind and highs at the back, so a kick, a voice and the hi-hats each have their own color. Pick Remix, Club, Fire, Ice, Blue Shades, High Contrast or Color-Blind Safe, or keep one of the classic single-color styles
- **Analysis runs by itself** - the measured tempo is there when you open a track rather than waiting on a button (PRO; on a free account it stays a click, so browsing tracks does not spend your daily analysis allowance)
- **The waveform follows the track** - zoomed in, the view turns the page when the playhead reaches the right edge, so a playing track stays in front of you at the zoom you set. Pan or zoom somewhere else and the view stays where you put it
- **A full set of eight** - every hot cue slot is filled and every competing cue set is cleared out, so no stale cue from another app survives in a slot we left alone
- **Check cue timing** - one click reads every cued MP3 and reports, without changing anything, the tracks whose cues or beat grid an older version saved one MP3 frame (about 26 ms) early, the tracks whose cues sit a constant distance off the grid, and the tracks whose cues are spaced at a rounded tempo. Repair moves the early-saved cues and grids onto the beat, every cue keeping its bar, and the whole run can be undone from the same report; anything the check cannot prove is listed for you to look at, never touched. In the editor the same findings appear as a line under the transport row, with Re-place cues to slide a track's cues onto the drawn grid and Repair this track for an early-saved one, and saving cues that sit off your Beat 1 grid asks first. Grid tempos show their decimals (118.997, never a misleading 119)
- **Click a cue card to play from it** - the way your DJ software fires a cue, rather than only moving the playhead there. Every click fires it again, so checking a placement is click, listen, click again
- **Works without a mouse** - + and - zoom the waveform, including the ones on the number pad, and 1 to 8 play from that cue like the pads on a controller. A number with no cue on it yet drops one at the playhead, so a whole track can be laid out from the keyboard. Space plays and pauses, and Shift with the arrow keys jumps a phrase
- **Jump by 4, 8, 16 or 32 beats** - buttons either side of Play move you a bar, a quarter phrase, a half phrase or a whole one, and every jump lands on the beat, so a run of them leaves you exactly as on-grid as the first
- **Labels, colors, presets, and hotkeys** - color-coded labels (Intro, Drop, Break and more), your own reusable labels, a Presets bar for one-click labeling, and Shift+number hotkeys
- **Fast track finding** - search your library and browse by folder, genre, tag, or playlist right beside the waveform
- **Drag straight out to your DJ software** - pull any track from the list into VirtualDJ, Serato, rekordbox, or a folder, and right-click to reveal the file in Explorer or Finder

---

## Cut My Tunes

Build a new track out of your songs the way a video editor does, and export the result as a new file. Your songs are never changed.

- **Drag songs onto rows** - browse by folder, genre, tag or playlist beside the timeline and drag a song in; drop below the last row to open a new one. Rows play together, so an overlap is a mix
- **Send a song from any tab** - right-click a song (or a selection) in Find, Tag, Mix, Dedupe, Cue or Play My Tunes and pick Send to Cut My Tunes; it lands on the end of the first row
- **Split, trim, move, repeat** - split at the playhead, drag a clip's edges, move clips between rows, Repeat, Copy and Paste, close the gaps, with full undo and redo
- **Fade a clip in and out** - drag the knob at a clip's top corner to fade that edge in or out, snapped to the beat. A fade is drawn as a ramp over the waveform while a trimmed edge stays a hard edge, so a quieter edge never looks like a shorter one, and the export writes exactly what you hear
- **Everything lands on the beat** - each song's own beat grid is drawn on its clip and a dropped clip puts its first beat on the project grid. The first song you drop on an empty timeline starts at 0:00 on bar 1 and sets the Project BPM, 1/2 and x2 halve or double it, Match clip takes it from a clip, the ruler numbers the bars, and Snap lands on a beat, a bar or an 8-bar phrase
- **See where you are in each song** - a strip along every clip shows its song's sections (Intro, Vocal, Beat only, Build, Drop, Break, Breakdown, Outro), the same ones Cue My Tunes finds. It follows the clip through trims, moves, splits and stretches, and a click puts the playhead on a section's start
- **One tempo for the whole project** - every song plays at the Project BPM, stretched in its own key so the pitch stays put: songs you add after the first are stretched to it, and typing a new tempo stretches them all, one song on its own included, with every bar staying on its bar line. Each clip shows how far it is stretched (amber over 8%, red over 16%), and the export is mixed from the same stretched audio you hear
- **Clip tools under the timeline** - Edit: Duplicate, Split, Split every (1 to 32 beats on the song's own bars), Loop (the 1, 2, 4 or 8 bars before the playhead, each choice naming the bars that play twice) and Delete. Sound: Reverse plays a clip backwards, Filter puts one of eight presets on it (High-pass build, Low-pass out, Filter in, Radio and more), and Level sets its own volume. Each is one Undo, and the export writes exactly what you hear
- **Echo and Build Up** - the clip tools' FX row. Echo out (the song stops while its echo rings, then plays on) or Echo over, 1 to 16 beats, repeating every 1/2, 3/4 or 1 beat. Build Up turns a clip of 1 to 16 bars into 8, 16, 32 or 64 beats of loops that get tighter and tighter while a filter and the level rise, and its last beat echoes on under what comes next. Both are one Undo, and the export writes exactly what you hear
- **Beat Map Trigger** - retrigger the beats of every bar of a clip in a pattern, like a sampler: 8 ready-made slots (rolls, a gallop, a fill on 4, the beats in reverse order) or draw your own on 16 squares a bar, with Listen looping the clip while you change it and Hold repeating the first bar. The waveform shows the chops, and the export writes exactly what you hear
- **A level meter and three counters** - left and right bars with a peak-hold tick, true peak and short-term loudness readouts, an amber light above -1 dBTP and a red CLIP light that latches where an export would be turned down; CURRENT, REMAINING and TOTAL above the transport
- **Fix a song's grid or cues without leaving** - the flag on a clip opens the song in Cue My Tunes, and Back to Cut My Tunes brings you to the same clip with the new grid
- **Projects stay in the app** - save a project under a name with its own artwork, open it later, and the project on screen comes back after a restart, unsaved changes included; songs the app moved are followed, and a missing one is reported
- **Export a new MP3 or FLAC** - never over the original; a one-song edit carries its cues and beat grid into the new file, and every song used is marked Edited in the list so you can see what you have already worked on

---

## Get My Tunes

Pull the songs you are missing off an archive drive, a NAS, or a cloud folder.

- **Download rules** - simple "filename contains" or "folder path contains" matches: grab one song, everything with "extended" in the title, or a whole folder
- **Source folder groups** - name sets of source folders ("Music pools", "Bootleg drive") and switch between them per scan
- **Search the archive without scanning it** - a search box on the source folders panel looks song names up in the saved file index and shows which folder each match sits in, instantly, with no drive access
- **Index rarely-changing folders** - mark an archive folder as indexed and every scan serves it from its saved file list instead of re-reading the drive; a per-folder refresh re-reads it on demand
- **Scan, count, and preview** before anything is copied - see how many songs each rule finds and exactly which files; editing, adding, or deleting a rule keeps the counts on the rules it did not touch, so one change never costs you the whole scan
- **Scan once, run later** - Run Selected and Preview work from your last Scan for 24 hours, even after a restart, so a long archive scan is never repeated just to start the download
- **Skips what you already have** - every run only copies what is genuinely new or updated
- **Re-download when you want it back** - tick Re-download on a single rule and it ignores the download history, so songs you pulled months ago come down again; a copy still sitting in your download folder is left untouched rather than duplicated
- **Saved rule groups and CSV import** - save rule sets by name, or import a whole wishlist from a CSV with a downloadable template
- **Download log** - a history of every file copied and where it went
- Feeds directly from **Find My Tunes** - turn any missing song, a whole imported playlist's missing songs, or every song in it, into download rules in one click

---

## Play My Tunes

A plain player for your whole library, for when you are not mixing and just want to listen.

- **Browse everything** - by folder, genre, tag or playlist from the panel on the left, with Ctrl and Shift clicks to combine several; nothing selected means every song you have
- **Narrow it down** - search titles, artists, albums, genres and tags, and filter by genre, energy, rating, key, a BPM range, the tags a song has or does not have (Has Tags / Exclude Tags), favorites or played; click a heading to sort, drag headings to reorder, right-click them to choose columns, including an optional Composer column for the energy level name your DJ software reads
- **Press play** - double-click a song and the player bar follows along; Up and Down move through the list, Space plays or pauses, Left and Right seek, Ctrl+Left and Ctrl+Right skip tracks, and the play-mode button decides what happens when a song ends
- **Edit as you listen** - the same columns as Tag My Tunes, edited the same way: a slow second click or the right-click menu opens a Title or Artist, rating stars and the genre picker work in place, and the panel on the right shows the artwork and every tag of the selected song
- **See which playlists a song is on** - the FMT Lists column counts its Find My Tunes playlists (MMT Lists, from the column menu, its Mix My Tunes ones); click the number and pick a playlist to open it in Find My Tunes or Mix My Tunes
- **Archive on the spot** - Delete moves a track to your archive folder and carries on with the next one
- **Work on several songs at once** - Ctrl+click and Shift+click select several songs, Ctrl+A the whole list; Change Genre of Selected (or the genre picker of any selected row) sets one genre on all of them, with one confirm and one Restore entry
- **File it by genre** - Move to Genre Folder puts the selected songs into the folder named after their genre, the same action as in Tag My Tunes, and a genre change files the song too when Auto-Move to Genre Folder is on
- **Drag it where it is needed** - pull a song out of the list into VirtualDJ or your other DJ software, a folder in Explorer or Finder, or an editor, the same as in Mix My Tunes

---

## Library Management

- Scan **multiple root folders** - external drives, network shares, gig USB sticks - with **MP3 and FLAC** support
- **SQLite database** stores all metadata locally - no cloud required
- Automatic change detection watches your folders for added, changed and deleted files and flags the database as out of date, so a refresh is one click away rather than something you have to remember
- Incremental updates scan only the folders that actually changed, and clear out songs whose files are gone
- **Files deleted outside the app are called out, not silently skipped.** Anything that can no longer be read because the file has gone is reported at the end of an Analyze run with a Refresh Database button beside it, and a playlist track whose file has vanished is dimmed and struck through in Tag My Tunes instead of looking perfectly normal until you press play
- **Cloud storage aware** - tracks kept online-only by Dropbox, OneDrive or Google Drive are recognized before they are opened, so everything already on your drive is indexed first and a slow download never holds up the rest of the scan. Writes into a synced folder are built to stay out of the sync client's way, so exporting playlists or saving tags into Dropbox or OneDrive does not fail on files it happens to be uploading
- Instant search across title, artist, genre, and comment fields
- **Parallel processing** - choose how hard long jobs work your machine (Settings > Analysis and speed). Automatic reads your cores and memory and picks for you; Maximum speed puts more of your processor behind a big job, Conservative keeps the app light while you work in something else. It applies to building the database, to writing tags in bulk (Mass Approve, Auto-Tag) and to analyzing tracks for BPM, key and energy - where it more than doubles the speed of a library-wide run. It takes effect without a restart, and always lets a file that is mid-write finish first. The panel shows how many files each job will handle at once and warns you before a choice would take every core you have
- Files are backed up before tag writes, and in-file writes are atomic so a crash never corrupts a track

---

## Customization

- **One Settings window for everything** - the gear opens the page of the tab you are on, with the whole-app pages (Folders, DJ software, Genres, Tags in your files, Analysis and speed, Keyboard shortcuts, AI, Backups) above one page per tab. Search any setting by a word like folder or ID3, switch to Changed by you to see only what you changed and put any of it back to default, and every change saves as you go with an Undo for the last one
- **Your settings in one file** - save everything you set up (except AI keys) to a file, and load it on another computer: it shows what will change first, lets you add the file's genres, rules and presets to yours or replace them, and backs up your current settings so a load can be undone
- **Display size** - draw the whole app at 90%, 85% or 80% so the lists show more rows on a laptop or MacBook screen; Automatic picks the largest size that fits your screen, and Ctrl/Cmd + and - change it on the fly
- **Columns** - toggle, resize, and reorder columns on every tab; right-click the heading row for a show/hide checklist that applies as you tick and stays in sync with Settings; a width you drag is kept exactly, across restarts and window resizes, and a column you leave alone is sized from what is actually in your list (double-click a divider to hand it back to that)
- **Edit in place** - the Title, Artist, BPM, Grouping and Comment cells in the Find, Tag, Mix and Dedupe lists, and in the SmartMix Live popout, are edited right in the row: right-click and choose Edit, or click the selected row's cell a second time slowly, type, and press Enter; the new value is written to the file and to your library (a BPM keeps up to two decimals)
- **Add to Playlist from anywhere** - right-click a song (or a selection) in Find, Tag, Mix, Dedupe, Cue, Play or Cut My Tunes and pick Add to Playlist: search your Find and Mix playlists, or pick one you used recently, and the songs go on the end of it, or make a new playlist for them right there. A song already in the playlist is never added twice
- **Search in every long dropdown** - any list of 8 or more choices opens with a search box at the top: type a few letters and it narrows to the matches, with the matching words marked (accents ignored), in every tab, Settings and the popout windows, and in the Mix playlist picker, Remove Tags and Cue's Browse panel
- **Hotkeys** - every keyboard shortcut in one searchable list (search by name or just press the keys); click one and press the new keys, and a key that is already taken is refused with the reason before anything changes. The keys built into Cue, Cut and SmartMix Live are listed beside them
- **Languages** - English, Español, Deutsch, Français, Italiano, Português, Nederlands, Polski, Bahasa Indonesia; the entire UI re-translates live
- **Minimize to tray or screen edge** - keep the app out of your way mid-set

---

## Free vs PRO

| Feature | Free | PRO |
|---------|:----:|:---:|
| Several music folders | No | Yes |
| Help assistant questions | ~125/month | ~1,250/month |
| Find My Tunes playlist imports | 1/day | Unlimited |
| AI playlist prompts | 1/day | Unlimited |
| AI results per prompt | 20 | 50 (300 with your own AI key) |
| Find My Tunes saved playlists | 3 | Unlimited |
| Find My Tunes playlist size | 20 songs | 1,000 songs (your choice of 300 to 5,000) |
| Export a playlist to M3U | No | Yes |
| Fix My Tunes | 15 songs/day | Unlimited |
| Tag My Tunes | 20 songs/day | Unlimited |
| Genre changes | 10/day | Unlimited |
| Make your own tags | No | Yes |
| Mix Next | 10 uses/day | Unlimited |
| Mix playlist size | 10 songs | Unlimited |
| Mix saved playlists | 3 | Unlimited |
| Auto-add to the Mix playlist | No | Yes |
| Dedupe scans | 3/day | Unlimited |
| Dedupe archive | 10 songs/day | Unlimited |
| Keep more than one copy, your own keep priorities | No | Yes |
| Audio Match | No | Yes |
| Cue saves | 5 tracks/day | Unlimited |
| Auto-Cue a whole folder | Not available | Yes |
| Get My Tunes downloads | 10 songs/day | Unlimited |
| Play My Tunes | Free | Free |
| Cut My Tunes exports | 2/day | Unlimited |
| BPM, energy and sound analysis | 10 songs/day | Unlimited |
| Key detection | 10 songs/day | Unlimited |
| Auto-updates | Yes | Yes |
| Library size | Unlimited | Unlimited |

The two analysis limits also count songs analyzed from Mix My Tunes and Cue My Tunes. The app's PRO window shows the same table, with the plans beside it.

PRO is available as a monthly or yearly subscription (both start with a 7-day free trial) or a lifetime license, managed entirely in-app. Your license is tied to your email address and works on up to 3 devices at once, so you can move between a studio machine and a gig laptop; you can release a device from within the app to free up a slot, including from a machine the cap has just refused. A reinstalled or reformatted machine takes its own slot back rather than using a new one. Sign in with the email you used at checkout to activate a machine. PRO keeps working offline for 14 days between check-ins, so flaky venue Wi-Fi never costs you a set.

---

## Privacy

- All audio processing happens **locally on your machine** - your files are never uploaded
- Network access is limited to playlist import APIs, AI suggestions (when you use them), license checks, update checks, the optional crash reports below, and problem reports you choose to send
- No usage analytics or tracking of any kind
- Optional crash and error reports, **off unless you say yes** - file paths, song and playlist names, your email and your computer's name are removed before anything is sent
- **Report a Problem** (in About) sends your description straight to the team, with an optional reply email and the app's diagnostics (you can untick them), and gives you a reference number

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

## About

Prep My Tunes is proprietary software. This repository hosts the official release downloads.

Built by [Streamline Software](https://streamline-soft.com).
