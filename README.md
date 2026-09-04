# Premium Site in One Paste

Four things, one repo. Paste one line into Claude Code and it builds a landing page
that doesn't look AI-generated.

## What's inside

| file | what it does |
|---|---|
| `ONE-LINE.txt` | the single line you paste into Claude Code |
| `CLAUDE.md` | the design brief Claude reads before it writes a single line of code |
| `HERO-SOURCES.md` | where to pull a real hero section from |

## How to use it

1. **Install Claude Code** — https://claude.com/download
2. **Add the design skill** (once, takes 5 seconds):
   ```
   claude plugin install frontend-design@claude-plugins-official
   ```
3. **Clone this repo** into an empty folder and open Claude Code there.
4. **Open `ONE-LINE.txt`, copy the line, paste it into Claude Code.** That's it.

Claude reads `CLAUDE.md`, scaffolds Vite + React + Tailwind + Framer Motion,
pulls a hero pattern, and builds the page.

## Why the output doesn't look AI-made

Most AI-built pages fail in the same six ways. `CLAUDE.md` bans all six up front,
so you never have to notice them yourself. The list is in that file.
