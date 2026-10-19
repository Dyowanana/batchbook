# Batchbook

A minimalist content calendar for planning posts in batches, across one or more brands and creators. The design is inspired by Notion.

**Live demo:** https://dyowanana.github.io/batchbook/

## What it does

- **Idea inbox.** Write an idea, paste a link to a post you want to remake, or paste a screenshot. One idea per line adds several at once.
- **Drag to schedule.** Drag ideas onto a day in the month or week view. Drag them back into the inbox to unschedule them.
- **Slide by slide.** Every idea has Slide 1, Slide 2 and so on, plus notes.
- **Read text from screenshots.** Paste a screenshot or drop a video and the on-screen text becomes slides. This runs in your browser with [Tesseract.js](https://github.com/naptha/tesseract.js), so nothing is uploaded.
- **Tags for each idea:** creator, brand, content pillar, goal (soft sell, hard sell or virality), format and status.
- **Multiple brands.** Add brands and their creators under **Brands & creators**.
- **Sorting and filters.** Sort by persona (A–Z), title, newest or post date. Filter by brand, creator or goal.
- **Right-click** any idea to open, duplicate, unschedule or delete it.

## Where your data lives

Everything is saved in your browser's local storage on the device you use. It stays when you close the tab, but:

- it doesn't sync between devices or browsers
- clearing your browser's site data erases it

Use **Brands & creators → Your data → Download backup** now and then. To move your calendar to another computer, restore that file there.

The first time you open it, the app loads demo content (two made-up brands and four made-up creators). Choose **Clear demo and start fresh** to begin your own plan.

## Run it yourself

The whole app is one file, `index.html`. It has no build step and no dependencies to install.

- **Open it:** double-click `index.html`, or run `npx serve .` and open the address it prints.
- **Host your own copy:** fork this repo, then go to **Settings → Pages** and set the source to *Deploy from a branch*, branch `main`, folder `/ (root)`. Your copy goes live at `https://<your-username>.github.io/batchbook/`.

Each person's copy starts with the demo content. Nobody sees anyone else's ideas.
