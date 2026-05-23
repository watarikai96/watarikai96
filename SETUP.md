# GitHub Profile README — Setup

This folder contains three files that, together, make your GitHub profile page light up. To activate them you need to create one special repository named after your username.

## Step 1: Create the magic repo

In your browser:

1. Go to [github.com/new](https://github.com/new)
2. **Repository name:** `watarikai96` (exact match with your username, this is the trick)
3. **Visibility:** Public
4. Tick **Initialize this repository with a README**
5. Click **Create repository**

GitHub will show a hint banner saying "watarikai96/watarikai96 is a special repository. Its README will appear on your profile."

## Step 2: Clone the new repo locally

Open Android Studio (or any IDE) and use **File > New > Project from Version Control...**, paste `https://github.com/watarikai96/watarikai96.git`, choose a folder, click Clone.

## Step 3: Copy these files into the new repo

Copy the contents of this `profile-readme/` folder into the cloned `watarikai96/` folder:

```
watarikai96/
├── README.md                                  (overwrite the initial one)
├── assets/
│   └── hero.svg
└── .github/
    └── workflows/
        └── snake.yml
```

Commit message:
```
feat: light up the profile with animated hero, stats, streak, snake
```

Push to main.

## Step 4: Trigger the snake animation

The snake-eating-your-contribution-grid is not a static image. It is generated daily by a GitHub Action you just added.

1. Visit `https://github.com/watarikai96/watarikai96/actions`
2. Click the **Generate contribution snake** workflow on the left
3. Click **Run workflow** > **Run workflow** (top-right of the file list)
4. Wait one to two minutes
5. Refresh `https://github.com/watarikai96` and the snake should be eating your contribution graph

After this first run the workflow auto-runs every 12 hours, so the snake stays current without any effort from you.

## Step 5: Confirm everything is alive

Open your profile page in a fresh tab and verify:

- The animated terminal hero with falling code rain renders at the top
- The "building TiME" badge row sits below
- Stats card, streak card, and language card render with the green theme
- Activity graph shows commits over time with the green line
- Trophy row renders without the boxy frame
- Snake eats the contribution grid (this is the unique flex, very few profiles have it)

If any image shows a broken icon, hard-refresh (Cmd+Shift+R). Third-party services occasionally cache; usually they recover within a minute.

## Updating the hero or copy

`assets/hero.svg` is a custom-built animated SVG (matrix-style code rain in green, blinking cursor, live pulse). Edit the file directly to change copy, swap colors, add streams. Commit and push. GitHub's image cache may take an hour to invalidate; force a refresh of the README to nudge it.

## Maintenance notes

- The snake workflow runs every 12 hours. If it ever turns red on the Actions tab, click in to see the error. Usually it is a transient rate limit; re-running fixes it.
- Stats cards are served by `github-readme-stats.vercel.app` and similar third-party services. If a card ever 502s, refresh; the service auto-recovers.
- The hero SVG is fully self-hosted in your own repo, so it never breaks for third-party reasons.

## What this profile is, what it is not

This profile is calibrated to show a serious solo founder at work. It is not a meme-collage of every badge ever. Three deliberate cards, one custom-built SVG, one rare snake animation. Keep it sparse. When TiME ships and gets users, the live stats will start to mean something on their own.
