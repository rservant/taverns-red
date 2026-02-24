# Red Taverns Portal

The front door to all Red Taverns projects — a static landing page at [taverns.red](https://taverns.red).

## Projects

- **[Toastmasters District Stats](https://ts.taverns.red)** — Real-time district rankings and analytics
- **Speech Evaluator** — AI-powered speech evaluation (coming soon)

## Development

Open `index.html` directly in a browser — no build step required.

## Deployment

Hosted on Firebase under the `toast-stats-prod-6d64a` project as a multi-site target.

```bash
firebase deploy --only hosting:portal
```

## Stack

- Pure HTML + CSS + vanilla JS
- Firebase Hosting (multi-site)
- Outfit font via Google Fonts
