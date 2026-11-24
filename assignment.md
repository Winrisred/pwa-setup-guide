<!--
  ASSIGNMENT RULES: edit this file to change the page.
  On GitHub: click the pencil icon, make your changes, check the Preview tab,
  then click "Commit changes". The page updates in about a minute.

  Quick formatting:
    # Page title      ## Section        ### Smaller heading
    - Bullet          1. Numbered       **bold**       [link text](https://...)
    Tables: one row per line, cells between | bars, and a |---| line under
    the header row.

  TBC shows highlighted on the page: it marks what's still to fill in.
  Notes like this one, between the arrow brackets, don't appear on the page.
-->

# Build a PWA as a team

Your team will build a data product as a Progressive Web App (PWA): a website people can install on their phone like an app. Along the way, you'll learn to organise shared work, manage changes, test your decisions, and publish a working application. **The product and the process both count.**

## What counts

Your team's GitHub repository is where the work happens, from the first week to the last. Its history shows who changed what, how changes were reviewed, and how the app grew.

- **Counts:** an app built and changed through your team's repository, with commits and reviews from every member.
- **Doesn't count:** a ChatGPT site, Claude artifact or Lovable app submitted on its own, or finished files uploaded to GitHub at the end.

**Already built a prototype elsewhere?** Keep the ideas, analysis, designs and any code that works. Bring them into the repository and keep developing them there.

## Deliverables and deadlines

<!-- These milestones are suggestions: rename, add or delete rows. -->

| What | Who | When |
|---|---|---|
| Setup guide done on your own computer | Everyone | TBC |
| Team repository created, everyone added | Team | TBC |
| Everyone has merged at least one pull request | Everyone | TBC |
| First version live on Vercel | Team | TBC |
| Final version live | Team | TBC |

Submit on TBC:

- the link to your live app on Vercel
- the link to your GitHub repository

## Team workflow

1. **One public repository per team.** One member creates it on GitHub as a **public** repository and adds the others as collaborators. Public keeps Vercel's free plan working for the whole team, and lets your teacher follow your work.
2. **Connect it to Vercel once.** The same member imports the repository into Vercel. Then, in the Vercel project, they open **Settings → Deployment Protection** and turn off **Vercel Authentication**, so everyone can open preview links without logging in.
3. **Everyone uses their own account and computer.** Your commits are how your contribution shows. Don't share accounts or let one person push for everyone. The email from the setup guide's "Your git identity" step must be one of the emails on your GitHub account, or your commits won't show as yours.
4. **Plan in Issues.** Write each task as a GitHub Issue and assign it to someone, so the team can see who's doing what.
5. **Work on a branch.** Make changes on a branch, never directly on `main`.
6. **Open a pull request.** Say what you changed and why. Keep each one small: one feature or one fix.
7. **Another member reviews it.** They read the changes, try the app on the preview link that Vercel posts on the pull request (see below), and approve it or ask for changes. Nobody merges their own pull request.
8. **Merge to publish.** Merging into `main` updates the live app. If something breaks, fix it with a new pull request.
9. **Spread it out.** Everyone opens and reviews pull requests throughout the project, not just in the last week.

### How preview links work

Once your repository is connected to Vercel (rule 2), this happens by itself every time someone pushes a branch:

1. GitHub tells Vercel there's new code.
2. Vercel builds a separate copy of your app from that branch, with its own web address. This copy is a **preview**.
3. Vercel's bot posts a comment on the pull request with a **Visit Preview** link. It says *Building* at first, then *Ready*.
4. The reviewer clicks the link and tries the app with the proposed changes, on a laptop or a phone.

Push again, and Vercel builds a new preview and updates the same comment, so the link always shows the latest version.

- **`main` → the live app.** What users see. It only changes when a pull request is merged.
- **Any other branch → a preview.** For trying changes before they go live. Nobody sees it unless you share the link.

**No Vercel comment on your pull request?** The repository isn't connected to Vercel yet. **The link asks you to log in?** Vercel Authentication is still on. Both are fixed in rule 2.

## Using AI

AI assistants such as Claude, ChatGPT, Kiro or Antigravity can help you explore ideas, write code, understand errors and improve your app. Use them. Your team stays responsible for what you build.

- **Understand what you submit.** You should be able to explain any part of your code, whoever or whatever wrote it.
- **Check it like any other change.** AI-written code goes through a branch, a pull request and a review, like everything else.
- **Say where AI helped.** In the pull request description, add one line on which tool you used and what for.
- **Keep private things out.** Don't paste passwords, API keys or other people's personal data into an AI tool.

## Grading

<!-- Fill in the weights. They should add up to 100%. -->

| Part | What we look at | Weight |
|---|---|---|
| The product | A working app, live on Vercel, that does what your team set out to do | 30%|
| The process | How you organised the work, managed changes and tested your decisions, as the repository shows | TBC |
| Your contribution | Your own commits and reviews, and how well you explain them | TBC |

## By the end

Every team member should be able to:

- run the project on their own computer
- explain their contribution
- make a change through GitHub
- help test and publish an update

Start with the [setup guide](./). Everyone completes it on their own computer.
