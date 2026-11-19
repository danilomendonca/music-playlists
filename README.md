# Music playlists

Plain-text playlists curated for import through [TuneMyMusic](https://www.tunemymusic.com/pt) and export to Deezer.

## Catalog

| Playlist | Main styles | Mood | Energy | Tracks |
| --- | --- | --- | --- | --- | --- |
| [Jazz in Motion](jazz/high-energy/jazz-in-motion.txt) | Big-band jazz, hard bop, jazz-funk, contemporary jazz | Driving, exploratory | High-energy | 16 |
| [After Hours](jazz/low-key/after-hours.txt) | Vocal jazz, ballads, intimate instrumental jazz | Intimate, reflective | Low-key | 12 |
| [Between Notes](jazz/low-key/between-notes.txt) | Instrumental ballads, cool jazz, small-group jazz | Spacious, reflective | Low-key | 12 |
| [Brazilian Jazz Groove](jazz/high-energy/brazilian-jazz-groove.txt) | Samba-jazz, Brazilian jazz-funk, fusion | Warm, percussive, lively | High-energy | 12 |
| [Night Signal](rock/post-punk-revival/night-signal.txt) | Post-punk revival, indie rock, dance-punk | Tense, driving | High-energy | 14 |
| [The Long Goodbye](pop/60s-pop/the-long-goodbye.txt) | 1960s pop, yé-yé, Italian pop | Defiant, cinematic | Mid-energy | 12 |

## Listening feedback

Give track or playlist feedback in plain language in the Music project. The [listening log](curation/feedback.md) records the reactions, and the [taste profile](curation/taste.md) turns them into guidance for future playlists. The [ChatGPT project instructions](curation/project-instructions.md) tell sessions to read the current files and record new feedback.

## Organization

Use broad genre folders and descriptive playlist names. Create folders when their first playlist is added; keep one primary home per playlist.

- `jazz/`: jazz playlists grouped by the energy they sustain across the set.
  - `jazz/low-key/`: intimate vocals, ballads, and spacious playing.
  - `jazz/high-energy/`: driving swing, forceful drumming, and propulsive grooves.
- `rock/`: rock playlists grouped by subgenre.
  - `rock/post-punk-revival/`: guitar-driven rock with post-punk rhythms and textures, including dance-punk and adjacent indie rock.
- `pop/`: pop playlists grouped by era or style.
  - `pop/60s-pop/`: 1960s pop, including yé-yé, Italian pop, and related vocal styles.
- `electronic/`: electronic music, including techno and house.
- `soul-and-blues/`: soul, blues, and related styles.
- `classical/`: classical music.
- `cross-genre/`: playlists whose purpose is to mix genres.

Record overlapping styles, mood, and energy in the catalog rather than duplicating files across folders. Tracks may appear in multiple playlists when they serve different listening purposes.

## File format

- Use UTF-8 plain-text `.txt` files.
- Put one track per line using `Artist - Song`.
- Keep titles, comments, numbering, and metadata outside playlist files.
- Preserve the intended listening order.
- Use lowercase filenames with hyphens, such as `jazz-in-motion.txt`.
- Keep expressive display names in the catalog.
- Use Git history for revisions; avoid filenames such as `final-v2`. Use dates only for playlists tied to a particular occasion.
- Update the catalog when adding or changing a playlist.

## Import

Open a playlist file, copy its contents, and paste them into TuneMyMusic's free-text importer. Review the matched recordings before exporting to Deezer.

GitHub is the source of truth for the lists. Importing to Deezer is a separate step; repository changes do not automatically update Deezer playlists.
