# Music playlists

Plain-text playlists curated for import through [TuneMyMusic](https://www.tunemymusic.com/pt) and export to Deezer.

## Catalog

| Playlist | Main styles | Mood | Energy | Tracks |
| --- | --- | --- | --- | --- | --- |
| [Jazz in Motion](jazz/jazz-in-motion.txt) | Jazz, hard bop, jazz-funk, contemporary jazz | Rhythmic, exploratory | Medium | 16 |

## Organization

Use broad genre folders and descriptive playlist names. Create folders when their first playlist is added; keep one primary home per playlist.

- `jazz/`: jazz and its related styles.
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
