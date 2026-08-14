# FC Spartak / Coldchester United — Squad & Tactics Site

A single-page site with:
- Full team sheet (roster table) with player profile cards
- A drag-and-drop tactics board (choose a formation, drag players onto the pitch, change pitch color)

## Deploy on GitHub Pages
1. Create a new repository on GitHub.
2. Upload `index.html` to the repo root (keep the name `index.html`).
3. Go to **Settings → Pages**, set source to the `main` branch, root folder.
4. Your site will be live at `https://<username>.github.io/<repo-name>/`.

## Editing player data
Open `index.html` and find the `players` array near the top of the `<script>` section.
Each player is an object like:

```js
{name:"THAHKYOU200", num:1, pos:"GK", robloxId:"4633121540", discord:"Couldn't Fetch", country:"Ukraine", flag:"🇺🇦", starter:true}
```

- `robloxId`: if you add a real numeric Roblox user ID, that player's card will show their real Roblox headshot.
- `discord`, `country`, `flag`: edit freely.
- `starter`: `true` = Starting XI, `false` = Reserve.
