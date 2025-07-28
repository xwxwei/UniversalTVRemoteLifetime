# UniversalTVRemoteLifetime

This repository contains a simple static website for the **Universal TV Remote Lifetime** app. The site includes:

- `index.html` &ndash; the home page describing the app.
- `terms.html` &ndash; a basic user agreement.
- `privacy.html` &ndash; the privacy policy.

Open `index.html` in your browser to view the site locally.

## Deploying to Cloudflare Pages

You can host this static site on **Cloudflare Pages** by connecting the
repository to a new Pages project:

1. Sign in to Cloudflare and create a new Pages project.
2. Select this repository and use the default build settings (no build command;
   output directory `/`).
3. After the first deployment finishes, Cloudflare will provide a URL where the
   site is accessible.

Connecting the repository allows each commit to trigger a new build on
Cloudflare Pages automatically.

For convenience, a simple `wrangler.toml` file is included. It sets
`pages_build_output_dir` to `.` so you can deploy the project using the
`wrangler pages` commands if preferred.
