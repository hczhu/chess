file-created-at:: 2026-10-14

# My chess games

One Markdown file per played Chess.com game.

Copy [game-template.md](game-template.md) into `games/` and name it
`YYYY-MM-DD-chesscom-GAME_ID.md`. Use the date you played the game and the numeric
ID from its Chess.com URL. The ID distinguishes games played on the same day.

Always include `file-created-at:` in the YAML front matter of every game note.
Set it to the note's creation date only, such as `2026-10-14` (`YYYY-MM-DD`).
Preserve it when editing the note;
it records file creation, not the date the game was played.

Each file records the game link, your color, White's opening, Black's defense,
tags, your comments, and the PGN in a fenced `pgn` code block. Preserve PGN
annotations and variations when available.

Keep tag spelling consistent so games are easy to find. Possible tags include
`#rapid`, `#blitz`, `#bullet`, `#win`, `#loss`, `#draw`, `#endgame`, and
`#missed-tactic`.

Write tags as Logseq hashtags. Use `#[[Scandinavian defense]]` for a tag with
spaces, and `#rapid` for a single word.
