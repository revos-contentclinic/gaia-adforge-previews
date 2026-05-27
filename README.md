# gaia-adforge-previews

Ad-preview HTML output from the `/gaia-adforge` skill (RevUP).

## Structure

```
/
├── index.html                              ← navigation index
└── <client>/
    └── <campaign>/
        └── <variant>.html                  ← preview at exact ad dim
```

## How it works

1. `/gaia-adforge` builds HTML preview at exact ad dimension
2. Pushed to this repo from local Claude Code workspace
3. Vercel auto-deploys on push
4. Preview URL viewable in any browser
5. Aliz / Claude.ai (browser) can edit via GitHub integration → push back → Vercel redeploys

## Active clients

- **Preschooler.sg** — `/preschooler/`
