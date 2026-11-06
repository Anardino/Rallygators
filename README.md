# rallygators.com

The small public site in front of the Racquet Events Hub web app: it shows the hub full screen and gives phones an icon and a name ("gators") when the page is saved to the home screen. It holds no code of the hub and no player data.

- `index.html`: the hub in a full screen frame. A personal link is `https://rallygators.com/#me=<key>`; `?me=<key>` works too, and `go=<id>` opens a card. The manifest has no start address on purpose: the home screen icon opens the exact link it was saved from, so a player who saves their personal link gets their own page (an iPhone home screen app does not share Safari's storage, so the key kept on the phone is only a backup).
- `apple-touch-icon.png` (iPhone), `icon-192.png`, `icon-512.png` (Android), `favicon.png`: the mascot on the hub's dark green.
- `site.webmanifest`: the name, colors and icons for Android.
- `CNAME`: the custom domain for GitHub Pages.

The source lives in the private hub repository (folder `site/`) and is published to the public repository Anardino/rallygators.
