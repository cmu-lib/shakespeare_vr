## Shakespeare VR

Source code for the static site developed for Stephen Wittek's "Shakespeare VR" project.

Development funded as part of the 2019 A.W. Mellon Digital Humanities Seed Grant.

## Editing and Deployment

During the editorial phase of this project, a preview build of the site has been deployed to <https://cmu-shx-vr.netlify.com/>.
Netlify builds the static site with each commit, and supplies a [client-side CMS](https://www.netlifycms.org/) for authorized editors of the site.

The production site is deployed to <http://dh-web.hss.cmu.edu/shakespeare_vr> via a webhook.

## Build

To build site assets from the source code:

1. Install ruby >= 2.6.3
2. Install bundler via `gem install bundler`
3. Install all gem dependencies via `bundler install`
4. Run `bundle exec jekyll build` to generate the site to the `_site` directory.

## Colophon

This Jekyll site is forked from the [Type On Strap](https://github.com/sylhare/Type-on-Strap) theme.

## Contact

[Matthew Lincoln](mailto:mlincoln@andrew.cmu.edu)
