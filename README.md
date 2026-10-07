# Application-Manager

A simple, elegant job application tracker. A single page (`index.html`), with no server, no accounts and nothing to install.

Built to keep track of applications quickly: what I've sent, what has been viewed, where I had interviews, where I was rejected and where I'm still waiting.

## Features

- **Stage-based flow**: Applied → Application viewed → Interview → Offer → Accepted. At each stage only the relevant buttons appear (move forward or *Rejected*), plus **↩ Go back** to fix mistakes.
- **Closed listings**: mark jobs that are no longer accepting applications. A rejected application closes the listing automatically.
- **Awaiting response**: a gold button that shows everything that isn't closed, rejected or accepted, with a notice of how many days you've been waiting.
- **Notes and interviews** for each application, with type (HR, Technical, Final) and dates, including scheduled interviews.
- **Editable application date**.
- **Filters**: search, status, interaction and open/closed listing.
- **Numbers at the top**: applications, with interaction, rejected, with interview, with offer and awaiting response.
- Automatic light/dark mode and smooth animations.

## How to use

Open `index.html` in your browser (double-click) or use the GitHub Pages version:

`https://fpmota.github.io/Application-Manager/`

### Where is the data stored?

In your browser's `localStorage`, meaning **only on the device and browser where you use the page**. Nothing is sent to any server.

Because of that:

- Use **Export backup** from time to time (it generates a `.json` file).
- Use **Import backup** to restore your data or move it to another device.
- Clearing your browsing data deletes your applications if you don't have a backup.

### Personal data outside the repository

The optional `seed-data.js` file is used to load initial applications and is listed in `.gitignore`, so it is **not published**. Without it, the app starts empty.
