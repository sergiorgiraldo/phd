# phd

My journey

## Site

https://sergiorgiraldo.github.io/phd/

## Status

[![Deployment](https://github.com/sergiorgiraldo/phd/actions/workflows/jekyll.yml/badge.svg)](https://github.com/sergiorgiraldo/phd/actions/workflows/jekyll.yml)

## Project

https://github.com/users/sergiorgiraldo/projects/3 

## status

![Static Badge](https://img.shields.io/badge/Backlog-2-red?style=for-the-badge)

![Static Badge](https://img.shields.io/badge/Prioritized-1-yellow?style=for-the-badge)

![Static Badge](https://img.shields.io/badge/Doing-1-green?style=for-the-badge)

![Static Badge](https://img.shields.io/badge/Done-2-blue?style=for-the-badge)

---

## Howto

- There are a few helpers, use shell scripts `newpost`, `newreview`, `newtask` for new content

- Badges in readme and about pages are generated automatically running shell script `queryproject` in the pre-commit hook. 

- The pre-commit hook also bundles the Jekyll site into the `_site` folder. This is then picked by the github workflow and published in my GH pages.
