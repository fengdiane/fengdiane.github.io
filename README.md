# Dandan (Diane) Feng's Personal Website

## Getting Started

1. [Install Ruby](https://www.ruby-lang.org/en/documentation/installation/)
1. [Install Jekyll](https://jekyllrb.com/docs/installation/)
1. Run `start.sh`. If your environment cannot run bash scripts, run

    ```ps1
    bundle exec jekyll serve
    ```

## Adding blogs

Create a Markdown (`.md`) file in the `_posts` folder. The filename format should be:

```
YEAR-MONTH-DAY-title.md
```

for example

```
2022-07-12-some-multiword-title.md
```

For Jekyll to do its magic, every post should start with the following two lines

```
---
---
```
