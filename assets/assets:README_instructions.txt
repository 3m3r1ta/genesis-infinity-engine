
Genesis Infinity Engine – Asset Pack Instructions
=================================================

1) Create an `assets` folder at the root of your GitHub repo and upload:

  genesis-logo.png
  genesis-logo.svg
  genesis-verified-badge.png
  genesis-verified-badge.svg
  genesis-banner.png
  genesis-banner-wide.png
  genesis-favicon.ico
  genesis-favicon-32.png
  genesis-favicon-64.png
  genesis-qr.png

2) In /site:

  - Upload genesis-favicon.ico to /site
  - Inside <head> of index.html add:

      <link rel="icon" href="genesis-favicon.ico" type="image/x-icon" />

  - (Optional) For dark/light toggle:
      • Upload dark-light-toggle.js into /site
      • Add a button with id="theme-toggle"
      • Add <script src="dark-light-toggle.js"></script> before </body>

3) README usage examples:

  Banner:
    ![Genesis Infinity Engine](assets/genesis-banner.png)

  Verified badge:
    ![Genesis Verified](assets.genesis-verified-badge.png)

  Crest logo:
    <img src="assets/genesis-logo.png" width="120" alt="Genesis Crest" />

  QR:
    ![Genesis Repo QR](assets/genesis-qr.png)
