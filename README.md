# PWA Setup Guide

A one-page guide for students: what to install on a Mac or Windows computer before building PWAs, and why. It has a Mac / Windows switch at the top.

**Live site:** https://winrisred.github.io/pwa-setup-guide/

Everything is in a single file, `index.html`. There's nothing to install or build.

## Changing the wording

1. Open `index.html` in VS Code.
2. Press `⌘F` and search for a few words of the sentence you want to change.
3. Edit only the words, not the `<...>` tags around them.
4. Save (`⌘S`).

Tips:
- Turn on word wrap (`⌥ Option + Z`) so long lines fit the window.
- The Mac and Windows guides are separate blocks in the file. If a sentence appears in both, change it in both.

## Previewing before publishing (optional)

To check changes before they go live, run a local server from this folder:

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000.

- It works **only while the server is running**. Stopping it (`Ctrl+C`), closing the Terminal window, or shutting down the Mac turns it off.
- Only you can see it. `localhost` means "this computer."
- While it runs, that Terminal tab is busy. Use a second tab (`⌘T`) for git commands.
- After saving a change, refresh the browser to see it.

For small wording changes you can skip this, publish, and check the live site instead.

## Publishing

```bash
git commit -am "Describe what changed"
```

```bash
git push
```

The live site updates in about a minute. If it doesn't, refresh with `⌘ Shift R`.

## localhost vs the live site

|                          | localhost                    | GitHub Pages                          |
|--------------------------|------------------------------|---------------------------------------|
| Needs a server running?  | Yes, start it each time      | No, always online                     |
| Who can see it?          | Only you, on your Mac        | Anyone with the link                  |
| Shows changes            | As soon as you save and refresh | After commit, push and about a minute |
| Use it for               | Checking before publishing   | Sharing with students                 |

## Hosting

Served by GitHub Pages from the `main` branch, root folder (repo **Settings → Pages**). Leave the **Custom domain** field empty.
