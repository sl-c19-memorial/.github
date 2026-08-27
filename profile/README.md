# Sri Lanka COVID-19 Digital Memorial

A living archive of the people Sri Lanka lost to COVID-19.

**Website: <https://sl-c19-memorial.github.io/>**

## The site has moved to a static archive

The memorial was previously a Next.js application hosted on Netlify, with
serverless form handlers and a scheduled build hook. To make sure the archive
survives long-term with no runtime and no paid services, it has been rebuilt as a
single self-contained static site (Hugo) that deploys straight to GitHub Pages.

- **New site:** <https://sl-c19-memorial.github.io/> — built and deployed by
  GitHub Actions on every push.
- The custom domain **srilankac19memorial.org** will point here once DNS is
  updated.
- The data still refreshes automatically: a daily workflow pulls the latest
  upstream snapshots into the repo, so the archive stays current without any
  hosted infrastructure.
- The old `memorial-web` application is retained for history but is no longer the
  live site.

## Repositories

| Repo | Purpose |
| --- | --- |
| [`sl-c19-memorial.github.io`](https://github.com/sl-c19-memorial/sl-c19-memorial.github.io) | The live static site (Hugo). Deployed to GitHub Pages. |
| [`memorial-dataset`](https://github.com/sl-c19-memorial/memorial-dataset) | Curated dataset of documented deaths. |
| [`scraped-dgi-reports`](https://github.com/sl-c19-memorial/scraped-dgi-reports) | Database of COVID-19 deaths scraped from DGI press releases. |
| [`memorial-web`](https://github.com/sl-c19-memorial/memorial-web) | Previous Next.js site. Archived; kept for history. |

## Contributing a name

If someone you knew is missing or their details are incomplete, use the submission
form linked from the site. Every entry is reviewed before it is published.
