# Santosh H. Mokashi — Research Website

Jekyll site for GitHub Pages. The layout is adapted from
[eugenielai.github.io](https://github.com/eugenielai/eugenielai.github.io)
(orderedlist "minimal" theme): a fixed sidebar with photo, contact links, and news, plus a content column.

Live URL (after enabling Pages): https://santoshmokashi86.github.io/Portfolio/

## Publishing
1. Repo **Settings → Pages → Build and deployment**: Source = *Deploy from a branch*, Branch = `claude/gracious-wright-skx7f2`, folder `/ (root)`. Every push to that branch rebuilds the site.
2. To serve at `https://santoshmokashi86.github.io/` instead, rename the repo to `santoshmokashi86.github.io` and set `baseurl: ""` in `_config.yml`.

## Updating content (no HTML needed)
| What | File |
|------|------|
| Name, email, links, photo, Google Scholar URL | `_config.yml` |
| Bio, interests, experience, honours, skills | `index.md` |
| Papers | `_data/publications.yml` |
| Projects + GitHub repo links | `_data/projects.yml` (`research:` / `engineering:`; `featured: true` shows on home page) |
| News items (sidebar shows latest 4) | `_data/news.yml` |
| Blog posts | `_posts/YYYY-MM-DD-title.md` |
| CV PDF | `docs/cv/Santosh_Mokashi_CV.pdf` |

Profile photo: drop an image at `assets/img/profile.jpg` and set `avatar: "/assets/img/profile.jpg"`.

## Local preview
```bash
bundle install
bundle exec jekyll serve
```
