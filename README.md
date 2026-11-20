# Anime Name Guess

A Wordle-style browser game: guess the anime character's name in 6 tries.
The clue shows which anime the character is from and how many letters the name has.

- 🟩 Green: right letter, right spot
- 🟨 Yellow: right letter, wrong spot
- ⬜ Gray: letter isn't in the name

## Play

Open `index.html` in any web browser. There's nothing to install.

You can type on your keyboard or tap the on-screen keys. Click **New character** to start another round.

## Add your own characters

Edit the `CHARACTERS` list near the top of the `<script>` in `index.html`:

```js
{ name: "LUFFY", anime: "One Piece" },
```

Names must be letters only (A–Z).
