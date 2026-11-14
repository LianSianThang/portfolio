# Lian Sian Thang — Portfolio

A responsive personal portfolio in green and grey. Built with HTML, CSS, and vanilla JavaScript; no framework, build step, or package installation is required.

## Run

Open `index.html`, or run `python -m http.server 8080 --bind 127.0.0.1` from this folder and visit `http://127.0.0.1:8080`. Use the same server address to test saved theme preferences.

## Features

- 23 project entries across five categories, rendered from objects in `js/main.js`.
- Category filters with selected states and live result counts.
- Light and dark themes with optional localStorage persistence; light is the default.
- Responsive navigation with keyboard support and Escape to close.
- Labeled demo contact form, trimmed validation, inline errors, focus management, and a live character count. It does not send or store messages.

## Content and limitations

Project links and the list of 19 public GitHub repositories were supplied by the user. The portfolio combines those with six supplied website destinations. ContextLens website/releases are grouped in one card; Agentic Data website/releases are also grouped, producing 23 entries. The Agentic Data grouping is inferred from the shared name. All-in-One Card and Poker/Rummy/Uno remain separate until their relationship is confirmed. Similarly named finance projects have not been merged without evidence.

Network restrictions prevented reading READMEs or confirming site availability. Descriptions are based on supplied names, categories, and previously inspected local files where applicable. No technologies or completion claims have been inferred from repository names. GitHub links use exact supplied repository spelling and omit tracking parameters.
An email address has not been supplied; contact currently uses the supplied phone number and GitHub profile. Add a verified `mailto:` link before submitting against the email requirement. Projects with no verified public source or demo currently link to contact, rather than a guessed URL.

The supplied assignment also requires a GitHub pull request and merge. Local work is on a feature branch; the online PR and hosting steps require working GitHub/Vercel access.

## Assets and credits

Website cards request real screenshots from Thum.io using only the public project URL. This is an external service dependency; no user credentials or form data are sent. Screenshots can be delayed, stale, or unavailable.

GitHub-only cards fetch the actual README through GitHub's public API, on demand as cards approach the viewport. Requests are cached for this page visit and reused across category changes. The README is shown as scrollable original text, not interpreted HTML. GitHub API rate limits, missing READMEs, or network restrictions show an explanatory fallback with Retry and the original repository link. No concept illustrations remain in project cards.

The site still runs without a build step. Project previews require internet access; all project links and the rest of the portfolio remain usable when previews fail. The favicon is an original SVG.

Agent instructions, assistant configuration, secrets, and Vercel local configuration are excluded by `.gitignore`. Always stage intended files explicitly and review staged files before pushing.

## Deployment

This is a static site. Import the repository into Vercel using the Other framework preset, no build command, and the repository root as the output directory. `vercel.json` supplies clean URLs and basic response headers.
