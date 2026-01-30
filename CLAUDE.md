# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Purpose

This is a GitHub Profile README repository for user `4iKZ`. When deployed to GitHub as a repository named `4iKZ` (must match the username), the README.md becomes the user's public profile page at `github.com/4iKZ`.

## Project Structure

```
.
├── README.md              # Main profile markdown (contains badges, stats, personal info)
├── assets/
│   ├── header-gradient.svg   # Top banner with username "4iKZ"
│   └── footer-gradient.svg   # Bottom banner with "GITHUB PROFILE" text
└── CLAUDE.md             # This file
```

## Design System

### Color Palette
- Primary Green: `#2f8d46` (used for stats icons, titles, accents)
- Navy Blue: `#1e3a5f` (header/footer gradient endpoints)
- Orange Accent: `#B8541E` (streak fire, activity graph points)
- Gray Text: `#4a5568` (body text, labels)
- White Background: `#ffffff` (stats cards)

### Badge Style
All badges use `flat-square` style for consistency.

### Typography
Font stack: Segoe UI, Roboto, Helvetica, Arial (sans-serif)

## User Information

| Field | Value |
|-------|-------|
| Username | 4iKZ |
| Email | syhaox@outlook.com |
| Blog | luminablog.cn |
| University | University of Science and Technology Liaoning (Class of 2025) |
| Technical Focus | Java Backend, Spring Framework, NLP, MySQL, Redis |

## External Services Used

The README integrates with several external services for dynamic content:

- **badges.pufler.dev** - Visitor counter
- **countapi.xyz** - Profile view counter
- **github-readme-stats.vercel.app** - Stats cards, top languages
- **github-readme-streak-stats.herokuapp.com** - Contribution streak
- **github-readme-activity-graph.vercel.app** - Activity graph

These services dynamically generate SVGs based on the GitHub username `4iKZ`.

## Important Constraints

1. **No emojis** - User explicitly requested no emoji decorations
2. **Username consistency** - All service URLs use `username=4iKZ`
3. **Asset paths** - SVG banners reference `main` branch: `.../4iKZ/main/assets/...`
4. **Badge links** - Language badges filter repos by language (e.g., `&language=java`)

## Deployment Notes

When deploying to GitHub:
1. Repository must be named exactly `4iKZ` (matches username)
2. Must be a public repository
3. Assets in `assets/` folder will be accessible at `.../main/assets/filename.svg`
4. Default branch should be `main` (update asset URLs if using a different branch name)
