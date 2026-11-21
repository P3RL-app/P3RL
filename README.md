# P3RL – Social Stats

A personal, offline-friendly phone app in the style of the Persona 3 Reload social-stats screen.
Log real-life activities and level up **Charm**, **Courage** and **Academics**.

Everything is one page: `index.html`, plus the three sound effects in `snd/`.

## Put it on GitHub Pages

1. Create a new repository on GitHub (private is recommended, see the note below).
2. Upload **all** files from this folder, keeping the `snd` folder:
   - `index.html`
   - `snd/rankbetter.mp3`, `snd/rankbig.mp3`, `snd/rank1.mp3`
   - `README.md`
3. Go to **Settings → Pages**, set **Source** to *Deploy from a branch*, choose `main` and `/ (root)`, and save.
4. After a minute your app is live at `https://<your-username>.github.io/<repo-name>/`.

> GitHub Pages on a *private* repository needs a paid GitHub plan. On a free plan the repository
> has to be public for Pages to work.

## Use it like an app on your phone

Open the link on your phone, then:
- **iPhone (Safari):** Share → *Add to Home Screen*
- **Android (Chrome):** ⋮ menu → *Add to Home screen* / *Install app*

## Your data

Points, history and custom activities are saved in the phone's browser storage and stay after you close the app.
They are per browser and per device. To move them, use **Owner tools → Data → Export**, then **Import** on the other device.
(The Claude-account sync from the claude.ai version is not available on GitHub Pages; it simply turns itself off.)

## Owner tools

Tap the **top-left corner of the stat panel 6 times** and enter your passkey.
The passkey is not written anywhere in the code, only a salted fingerprint of it is.
Tap the corner 6 times again (or use *Hide owner tools*) to lock it.

## Note

Visual elements and sound effects are recreated from / taken from *Persona 3 Reload* (© ATLUS © SEGA) for personal,
non-commercial use. Keep that in mind before making the repository public.
