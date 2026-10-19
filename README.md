

# Birthdays

Little interactive birthday websites for the people I love. Each person has their own folder.

```
birthdays/
├── index.html        a blank "nothing here" page, so names aren't listed
└── zafrin/
    ├── index.html    Zafrin's site
    └── zafrin.jpg    her favorite photo (add this)
```

Each site lives at `https://<your-username>.github.io/birthdays/<name>/`.

## Add a new person

1. Copy the `zafrin` folder and rename it, for example `riya`.
2. Put their photo in the new folder.
3. Open the new `index.html` and edit the `CONFIG` block near the top of the script:
   - `name`: the name they type to get in
   - `candles`: how many candles on the cake
   - `photo`: the photo's file name, for example `"riya.jpg"`
   - `photoCaption`, `reasons` (the balloon notes) and `letter`
4. Commit and push. The new site is live in a minute or two.

## Turn on GitHub Pages (once)

Settings → Pages → Source: "Deploy from a branch" → Branch: `main`, folder `/ (root)` → Save.

Note: on a free account the repository has to be public for Pages to work, so anyone who finds the repo can read the letters.
