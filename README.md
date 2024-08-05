# Jay's blog

I believe that successful content is attributed to context

## Documentation

* Demo: https://myblog.github.io/

## Screenshot

![Jekyll Curate Theme screenshot](https://www.zerostatic.io/theme/jekyll-curate/jekyll-curate-screenshot.png)

## Install

### Install Jekll

Make sure you have Ruby & Jekyll installed - For a step-by-step guide, read Jekyll docs [installation](https://jekyllrb.com/docs/installation/)

### Install Theme

Extract the theme .zip file to your local computer. Navigate to the project root (it contains the README.md)

Run `bundle install` to install gems.

Then run `bundle exec jekyll serve` to start the Jekyll local development server.

To build the Jekyll site run `bundle exec jekyll build`

## Deploy

### Deploy to Netlify

This theme is pre-configured to deploy with [Netlify](https://docs.netlify.com/site-deploys/create-deploys/).

> 💡 If you experience bundle install issues during the Netlify deployment, deleting the Gemfile.lock can sometimes help

### Deploy to GitHub Pages

This theme has been tested to work with GitHub Pages. If you are creating a GitHub Pages "Project site" then your site will be in a sub-folder ie `http://username.github.io/repository` You will need to update the `baseurl` in the `_config.yml` for the asset paths to work correctly.

```yaml
# _config.yml
baseurl: "/my-repo-name" # replace this with the name of your repo
url: ""
```

> 💡 Github pages can be tricky to configure correctly. While we have tested this theme with Github pages, we do not provide support for deploying on this platform. If you continue to experience problems we recommend trying Netlify.

## Credits

This theme uses open-source libraries and assets.

- **Bootstrap 5.3.2** https://unsplash.com/license
- **Font Awesome 6 Free:** https://fontawesome.com/
- **Unsplash Images** https://unsplash.com/
