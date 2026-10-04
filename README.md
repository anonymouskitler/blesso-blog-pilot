# Blesso Blog publishing pilot

Status: Disposable integration fixture.

## TL;DR

This repository is a synthetic Astro blog for verifying Blesso repository publishing with GitHub and Vercel. Articles are discovered from Markdown files; publishing does not edit a post registry. Only this repository and its test deployment may be changed during the pilot. No customer content or credentials belong here.

Article files live in `src/content/blog/`, with `title`, `description`, and `pubDate` frontmatter. Images belong under `public/images/<article-slug>/`. The production branch is `main`; `npm run build` creates `dist/`. Individual posts render at `/blog/<article-slug>/`.
