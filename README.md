# VibeOptimizer documentation

This repository hosts the generated VibeOptimizer documentation:

**https://pgusto34.github.io/VibeOptimizer-docs/**

`site/` is generated output. Updates are published automatically from the private
source repository after its documentation checks pass on `main`. Make content
changes in that source repository; edits to `site/` are overwritten on publication.

Only the static website and downloadable configuration examples are published
here. This repository does not contain the application source or its Git history.

GitHub Pages deploys `site/` through `.github/workflows/pages.yml`. Publishing must
be configured under **Settings → Pages → Source → GitHub Actions**. The workflow
can also be run manually on `main` to redeploy the current site.
