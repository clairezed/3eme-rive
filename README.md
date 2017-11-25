# 3ème rive, café associatif Epinal - website

## How to use

Shared config (used both in production and development) is in `_config.yml`.

The file `_config.dev.yml` is used only in dev, in addition to `_config.yml`, to override specific data.

Launching development server :

```bash
bundle exec jekyll serve --config _config.yml,_config.dev.yml
```
You should reach your website at [localhost:4000](localhost:4000)


## Specificities

- One config file per environnement (see above, "How to Use")
- All pages are in `_pages` folder. You may need to specify page permalink in page file frontmatter.
- Agenda module with [openagenda](https://openagenda.com/3eme-rive)


## Ressources

### Netlify

- [CMS](https://www.netlifycms.org/)
- [Netlify docs](https://www.netlify.com/docs/)


## Credits

This website is based on the [Made Mistakes](http://mademistakes.com)  theme [Skinny Bones](http://mmistakes.github.io/skinny-bones-jekyll/).
