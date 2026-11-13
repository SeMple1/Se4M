# SeMple1 — GitHub Hub

[**Open the live GitHub Dashboard**](https://semple1-github-hub.vercel.app/)

A dark, responsive GitHub developer dashboard based on the supplied screenshot: circular avatar sidebar, four statistics cards, 52-week contribution heatmap, technology stack, language doughnut and highlighted repositories.

## Live features
- Real GitHub profile, public-repository count, stars, followers and account age
- 52-week contribution heatmap from the [public contributions API](https://github.com/grubersjoe/github-contributions-api)
- Tech-stack chips and language percentages from public repository language statistics
- Notable public repositories, sortable by stars, latest activity or name
- Responsive desktop/mobile design; no packages, build, cookies, secrets or API token required

**Privacy:** Only public GitHub data is requested. Private repositories are not displayed. If an API is unavailable, affected data shows an unavailable state rather than invented values. Third-party contribution data is cached by its provider.

## Source and deployment
- Main website source: [index.html](./index.html)
- Live URL: https://semple1-github-hub.vercel.app/
- Hosting: Vercel, production linked to this GitHub repository
- Editable local copy: C:\Users\Guoba\Documents\GitHub-Hub\

## Show it on your native GitHub profile
GitHub does not support custom HTML/CSS in the native GitHub profile. Create a **public** repository named exactly **SeMple1** under your account, with a README.md. GitHub displays that README on https://github.com/SeMple1. Include this link:

[Explore my interactive GitHub Dashboard](https://semple1-github-hub.vercel.app/)

You can also add the live URL under GitHub profile Edit profile → Website.
