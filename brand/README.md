# aWkward snail brand and Store artwork

Shared artwork for every aWkward snail app. Use these for new app packages and
Microsoft Store listings so all apps look the same.

## App icon (option A: "sn@" with a block cursor, green on black)

- `icon/icon-master.png`: the 2048 x 2048 master icon. Background `#0D0F0C`.
- `icon/generate-icons.ps1`: makes every MSIX logo, tile, splash screen and the
  `.ico` from the master (Windows PowerShell). Copy both files into an app's
  `packaging/` folder and run the script there. It was written for Chain Calc,
  so check the output paths (for example `src\ChainCalculator\app.ico`) for
  each app.

## Store listing artwork (brand)

- `store/tile-300.png`: 300 x 300 Store logo tile.
- `store/boxart-1080.png`: 1080 x 1080 box art with the "aWkward sn@ail" wordmark.
- `store/poster-720x1080.png`: 720 x 1080 poster with the wordmark.
- `store/alternatives/`: the options not chosen (amber, "@" only), kept for reference.

## Per-app Store art

- `apps/chain-calc/`: Chain Calc's box art (2160 x 2160) and poster
  (1440 x 2160): the icon with the app name and a one-line tagline under it.
  Use the same layout for each new app and add it here as `apps/<app>/`.

## Font

The lettering is VT323 (SIL Open Font Licence, see `VT323-font-licence-OFL.txt`).
