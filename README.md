# SeMple1 — GitHub Hub

A dark, responsive GitHub developer dashboard designed to match the supplied reference image.

## Features
- Profile sidebar with GitHub avatar, account details and follow link
- Live public repositories, total stars, followers and account age from GitHub's public API
- Contribution heatmap for the last 52 weeks via the public [GitHub Contributions API](https://github.com/grubersjoe/github-contributions-api)
- Tech-stack pills and language doughnut chart calculated from public repository language data
- Notable projects with working GitHub links and sorting (stars / activity / name)
- Responsive desktop and mobile layout, accessible markup and reduced-motion support

Private repositories are never queried or displayed. The public GitHub API can rate-limit anonymous requests, so the dashboard displays an unavailable state instead of invented data.

## Run
Open index.html in a browser. Hosting on Vercel or GitHub Pages uses the same file without a build step.

## GitHub profile integration
GitHub does not allow arbitrary HTML/CSS to replace the native github.com/SeMple1 profile layout. Link to this dashboard from the profile's website field or a special public repository named SeMple1/SeMple1 with README.md.
