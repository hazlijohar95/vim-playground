# vim.playground

> "How do I exit Vim?" — 6.2 million Stack Overflow views and counting.

An interactive Neovim playground that runs in your browser. No installation. No config files. No accidentally deleting your system32. Just click and start pressing keys.

Built for people who heard Vim is cool but have been too scared to open a terminal.

---

## The Problem

You want to learn Vim because:

- Some bearded developer on YouTube said it changed their life
- You accidentally opened `vi` on a server and had to restart the machine
- You saw someone code at the speed of light and wanted that power
- Your friend won't shut up about "modal editing"

But every tutorial starts with "first, let's configure your `.vimrc`..." and you close the tab.

## The Solution

**vim.playground** — a fake Neovim that runs in your browser. Real keybindings. Real modes. Zero consequences.

Delete a line? Who cares. It's not a real file.
Type random keys? Go wild. Nobody's watching.
Press `:q!` forty times? Therapeutic, honestly.

---

## "Installation"

```bash
# Option A: Just open it
open index.html

# Option B: If you're fancy
python3 -m http.server 3000
# then go to http://localhost:3000

# Option C: Deploy it (why not)
# Enable GitHub Pages → Settings → Pages → main branch
```

There is no `npm install`. There is no `node_modules`. There is no build step. It's one HTML file. Like the internet was meant to be.

---

## How It Works

### 1. Pick a lesson from the sidebar

Each one teaches a single shortcut. We're not animals — we go one at a time.

### 2. Read the task

Something like "Press `dd` to delete this line." Groundbreaking stuff.

### 3. Actually do it

Click the terminal. Press the keys. With your fingers. On your keyboard. The browser one, not the piano one.

### 4. Get a checkmark and confetti

Because dopamine is the best teacher.

---

## What You'll Learn

| Lesson | What It Does | How It Feels |
|--------|-------------|--------------|
| `i` | Enter INSERT mode | "Oh, NOW I can type" |
| `Esc` | Back to NORMAL mode | Pure relief |
| `v` | Select text | "I am a surgeon" |
| `h j k l` | Move cursor | Confused → enlightened |
| `w` / `b` | Jump by words | "Why did I ever use arrow keys" |
| `gg` / `G` | Top / bottom of file | Teleportation |
| `dd` | Delete a line | Violent satisfaction |
| `u` | Undo | "Thank god" |
| `yy` / `p` | Copy / paste | "They call it YANK??" |
| `o` | New line + type | Smooth |
| `:w` | Save | You feel responsible |
| `:q!` | Quit without saving | Freedom |

Then there's **Sandbox Mode** — no rules, no tasks, just you and a fake file. Go nuts.

---

## Features

- **Real keybindings** — `hjkl`, `dd`, `yy`, `p`, `u`, `o`, `w`, `b`, `:w`, `:q`, the whole crew
- **Live keystroke display** — see every key you press, so you know what you did (and what went wrong)
- **Mode-aware hints** — different tips for NORMAL, INSERT, VISUAL, and COMMAND modes
- **Progress tracking** — checkmarks, streak counter, progress bar
- **Confetti** — because completing a lesson should feel like winning the lottery
- **Zero dependencies** — one HTML file, two Google Fonts, zero npm packages, zero regrets

---

## Tech Stack

- **Frontend framework:** None
- **Build tool:** None
- **Package manager:** None
- **CSS framework:** None
- **State management:** A bunch of `let` statements
- **Database:** Your browser's RAM
- **CI/CD:** Opening the file
- **Design system:** Stolen with love from [OpenCode](https://github.com/anomalyco/opencode)

Font: IBM Plex Mono (terminal) + Inter (UI).
Colors: OpenCode's warm smoke palette. Because cold gray is for spreadsheets.

---

## FAQ

**Q: Is this a real Vim emulator?**
A: It covers the basics. If you need `:g/pattern/d` or macro recording, you're already too powerful for this tool.

**Q: Can I use this on my phone?**
A: You can try. You'll need a keyboard though. Vim without a keyboard is just staring at text.

**Q: Will this make me a 10x developer?**
A: No. But you'll be able to exit Vim, which puts you ahead of millions.

**Q: Why is it one HTML file?**
A: Because the last thing the world needs is another `create-react-app` with 847 dependencies to display some text.

**Q: I found a bug.**
A: That's not a question. But open an issue anyway.

---

## Contributing

Found a bug? Fork it and fix it yourself. No PRs. I don't have time to review your CSS opinions on a single HTML file. This is a free Vim trainer, not a startup.

Want to add a lesson? Fork it. Build your own. Ship it. That's the open source spirit.

The entire app is in `index.html`. Yes, all of it. HTML, CSS, JS. One file. It's beautiful and terrifying. You'll understand the whole codebase in 10 minutes. You don't need my approval.

---

## Credits

- Design system lovingly borrowed from [OpenCode](https://github.com/anomalyco/opencode) by [Anomaly](https://github.com/anomalyco)
- Inspired by the 6.2 million people who googled "how to exit vim"
- Built with [OpenCode](https://opencode.ai) in a Neovim + tmux session (yes, really)

---

## License

MIT — do whatever you want. Teach the world to `:wq`.
