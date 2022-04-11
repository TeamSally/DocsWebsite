


# Team Sally Documentation Website

This site is built with [Zola](https://www.getzola.org/), a static site generator, and hotsed on GitHub Pages.

# Setup

Follow the instructions on Zola's site for [installing Zola](https://www.getzola.org/documentation/getting-started/installation/).

Once installed, `cd` into the repo and run `zola serve`. It'll give you a URL you can visit locally!

# Deploying

The `main` branch is [monitored](.github/workflows/zola.yml) for any commits, and will re-trigger a push to the live site once it sees any new commits.

# Adding Content

Add a `title.md` file into the `content/`folder, with the following header in the file:

```markdown
+++
title = "Hello, World!"
date = 2021-12-09
+++
```

(Of course, fill in those fields with your actual title and date.)

Then, add any markdown content below! This includes HTML, so you can put YouTube embeds and the like.

For any images, create a `media/` folder and reference them with a relative path.
