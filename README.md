# mtarngcyber.org website

the Hugo repository for our website

## Config

- Running on Cloudflare Pages
- Built using Hugo and the [Ananke theme](https://github.com/theNewDynamic/gohugo-theme-ananke)

## How to post article updates

- Clone the repo `git clone https://github.com/mtguardcyber/website.git`
- Make a branch for your content
- Start a Markdown file in the `content/articles` folder, e.g. `2025-event.md`
- Copy the front matter from one of the other `.md` files and update for your data (keep the banner line so the banner shows properly)
- Once ready, commit your branch and push it up
- ping @awilmo8 for merging, or if a maintainer, merge it yourself
- Cloudflare will automatically pick up the updates and rebuild the site

- For development you can use Hugo locally on the repo to build and test