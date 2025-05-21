[![Netlify Status](https://api.netlify.com/api/v1/badges/bedce933-9999-4745-910c-3f89133a4a00/deploy-status)](https://app.netlify.com/projects/0xtherealbatman/deploys)

# 📝 Personal Blog

This is my personal blog — a space where I write about whatever I’m curious about. It’s built with [Hugo](https://gohugo.io), a fast static site generator, and deployed on [Netlify](https://netlify.com).

Nothing here is final, but all of it is honest.


## 📦 Tech Stack

- **Hugo** — Static site generator
- **Markdown** — For content writing
- **Netlify** — For deployment and hosting
- **Custom Domain** — [yourdomain.com] (optional)


## 🚀 Build & Deploy

### Local Development

```bash
# Install Hugo (if you haven't)
brew install hugo

# Run the local dev server
hugo server -D
```

### Build for Production

```bash
hugo
```

The output will be in the `public/` folder.

### Deploying to Netlify

Netlify uses this build configuration:

```toml
# netlify.toml

[build]
  command = "hugo"
  publish = "public"

[build.environment]
  HUGO_VERSION = "0.147.4" # or whatever version you use
```

Push your changes to GitHub and connect the repo to Netlify. Set the correct Hugo version via UI or this file.


## 🧠 About This Blog

This blog is where I think in public. There’s no schedule, no niche, no branding strategy — just ideas worth exploring.

A lot of what I’ve worked on over the years hasn’t been documented. This blog is partly an attempt to change that.

Everything here is open source and free to use. Fork it, remix it, ignore it — up to you.

See [`/about`](https://0xtherealbatman.com/about/) for details.


## 🔗 License

[WTFPL](http://www.wtfpl.net/about/) — Do what you want.
