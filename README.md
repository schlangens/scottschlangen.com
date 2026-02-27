# scottschlangen.com

Personal portfolio and resume site for Scott Schlangen, built with [Hugo](https://gohugo.io/) and the [Coder](https://github.com/luizdepra/hugo-coder) theme.

## Structure

- `content/` - Markdown content files (About, CV, Tools)
- `config.toml` - Hugo site configuration
- `assets/scss/` - Custom SCSS styles
- `static/img/` - Images and logos
- `themes/` - Hugo theme (hugo-coder-forked)

## Development

```bash
# Clone with submodules
git clone --recurse-submodules https://github.com/schlangens/scottschlangen.com.git

# Run local dev server
hugo server -D

# Build for production
hugo --minify --gc
```

## Deployment

Deployed to [Cloudflare Pages](https://pages.cloudflare.com/) via GitHub Actions on push to `main`.
