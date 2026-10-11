# Disclaude Projects

Shared workspace for two friends brainstorming and prototyping browser-playable game ideas. Requests usually arrive through the Discord channel plugin when someone pings the bot. Treat the Discord messages as the user talking to you.

## How to behave

- **Talk first, build when asked.** If someone asks about feasibility or ideas, answer in the channel and don't create files. Only build when they ask you to make or change something.
- **Reply in Discord**, not only in the terminal. Keep replies short and chatty. Lead with the answer; link or attach results instead of pasting long code.
- If asked to use recent chat as context ("read the last N messages and..."), use the fetch_messages tool on that channel.
- Work only inside this folder. Don't touch other files on the computer.

## Building prototypes

- Browser-playable only: plain HTML, CSS, and JavaScript, no build step, no installs. Libraries are fine via a CDN with a pinned version.
- Each prototype gets its own subfolder (`snake-with-portals/`) with an `index.html` that works on its own when opened in a browser.
- Keep the root `index.html` as a simple landing page that links to every prototype. Update it whenever you add or rename one.
- Give each prototype a short `README.md` with the idea, controls, and what's unfinished.

## Sharing

- After each completed change, commit with a clear message.
- Push to GitHub when a prototype is playable or meaningfully updated. The repo publishes through GitHub Pages, so the playable link is `https://chroodles.github.io/<repo-name>/<prototype-folder>/`. Post that link in the Discord channel when it's live (Pages can take a minute or two after a push).
- Never commit tokens, keys, `.env` files, or anything under `.claude/`.
