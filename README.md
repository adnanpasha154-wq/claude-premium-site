# Premium Site in One Paste

You paste one line into Claude Code. It asks you three questions. Then it builds a
landing page that doesn't look AI-generated.

Four things, one repo. No build step, no dependencies to install here.

---

## The one line

It's in [`ONE-LINE.txt`](ONE-LINE.txt). Copy the whole thing — it's a single line.

---

## Four steps

**1. Install Claude Code**
https://claude.com/download

**2. Add the design skill** — once, takes five seconds:

```
claude plugin install frontend-design@claude-plugins-official
```

**3. Get this repo into an empty folder**

```
git clone https://github.com/adnanpasha154-wq/claude-premium-site.git my-site
cd my-site
```

No git? Click the green **Code** button above → **Download ZIP** → unzip it.

**4. Open Claude Code in that folder, paste the line from `ONE-LINE.txt`.**

That's it.

---

## What happens next

Claude will **not** start writing code. It asks you three questions first:

1. What does this business actually sell?
2. Who buys it, and what do they already know when they land on the page?
3. What is the ONE action this page should produce?

Answer them. Then it states the palette, the type pairing, the layout and the one
signature element — and only then writes the site. Vite + React + Tailwind +
Framer Motion.

---

## What's in here

| file | what it does |
|---|---|
| `ONE-LINE.txt` | the single line you paste |
| `CLAUDE.md` | the brief Claude reads before writing anything — including the six bans |
| `HERO-SOURCES.md` | where to pull a real hero section from |
| `README.md` | this |

---

## Why the output doesn't look AI-made

Most AI-built pages fail in the same six ways — the cream-and-terracotta palette,
the one italic word in the headline, the fade-up on every section, the row of big
numbers. `CLAUDE.md` bans all six up front, so you never have to notice them
yourself. The full list is in that file.

---

## A note on the hero

`HERO-SOURCES.md` points at [21st.dev](https://21st.dev) for a hero section you can
drop in. Those components belong to the people who made them — check the licence on
anything you ship.

---

Built by [@itsadnanai](https://instagram.com/itsadnanai).
If you make something with it, send it to me — I want to see it.
