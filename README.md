# GWA Calculator (installable app)

Add your subjects, units and grades. The app computes your General Weighted Average:

    GWA = sum(units x grade) / sum(units)

Your subjects are saved on your own phone. The app also works offline after the first visit.

## Put it online (one time, free)

Phones only allow installing a web app from a secure (https) address, so the folder
needs to live on a web host first. Any static host works:

- **Netlify Drop:** go to app.netlify.com/drop and drag this whole folder onto the page.
  You get an https link right away.
- **GitHub Pages:** upload these files to a repository and turn on Pages in its settings.
- **Cloudflare Pages:** create a project and upload the folder.

Keep all the files together in the same folder: index.html, manifest.webmanifest,
sw.js and the three .png icons.

## Install it on a phone

Open your https link on the phone, then:

- **Android (Chrome):** open the menu and choose "Install app" or "Add to Home screen".
- **iPhone (Safari):** tap the Share button, then "Add to Home Screen".

It then opens full screen from the home screen like any other app.
To share it, send people the same link and they can install it themselves.

## Updating

If you change any file, edit the version name at the top of sw.js
(for example gwa-calculator-v1 to gwa-calculator-v2) and upload the files again,
so phones pick up the new version.
