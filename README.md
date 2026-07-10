# Trove

A free, community curated directory of learning resources. Pick a topic, get a short list of the best free things to learn it from, instead of digging through search results for an hour.

Live site: https://bits232.github.io/Trove/

## What this is

Trove started as a simple idea: every community has someone asking "does anyone have a good resource for X" on repeat. This is meant to be the answer, kept in one place and kept honest. Every resource listed is checked to actually be free before it goes up.

Right now it covers things like computer basics, programming, design, electronics, drawing, music production, and more. The list grows as people add to it.

## How it works

It's a single static page. All the resource data lives in `resources.json`, and `index.html` reads that file and renders it. No backend, no database, no build step. Open `index.html` on a real server (not by double clicking the file) and it works.

## Adding a resource

Two ways to do this, pick whichever you're comfortable with.

**No git needed:**
1. Open `resources.json` in this repo
2. Click the pencil icon in the top right to edit it in your browser
3. Add your resource inside the right category, matching this shape:

```
{ "title": "Name", "format": "video", "desc": "One sentence on what it teaches and why it's good", "url": "https://example.com", "tag": "example.com" }
```

4. `format` has to be one of: video, course, book, interactive
5. Scroll down and GitHub will offer to open a pull request for you. Submit it.

**If you use git normally:**
Fork the repo, add your resource to `resources.json`, commit, open a PR.

Either way, it gets reviewed before merging. A few ground rules:
- Has to be genuinely free. If part of it is paid, say so in the description instead of listing it as free.
- Real, working link.
- One resource per entry. No dumping a huge list in one PR.

## Community

There's a Discord for this too, mostly for discussing what to add and just talking about learning stuff in general. https://discord.gg/MHgmzgEqFE

