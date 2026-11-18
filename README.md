# ZIFT GIFT – Grand Launch

A cinematic curtain-reveal inauguration page for the launch of **ziftgift.in**.
It's a single static `index.html` with no build step.

## Deploy on Vercel
1. Import this repo in Vercel and choose **Framework Preset: Other**. Leave the build command empty and keep the output directory as the root.
2. Add `logo.png` next to `index.html`. If it's missing, a gold "ZIFT GIFT" wordmark is shown instead.

## Customise
In `index.html`, the `CONFIG` object at the top of the `<script>` holds these settings:
- `TARGET_URL`: where visitors are sent (default `https://ziftgift.in`)
- `REDIRECT_DELAY`: milliseconds after the text reveal starts (default `10000`)
- `CURTAIN_DURATION`: how long the curtains take to open (default `3000`)
- `LOGO_SRC`: path to the logo (default `logo.png`)

Colours and sizes are CSS variables in `:root` at the top of the `<style>` block.
