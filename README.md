# My personal website

This repository contains the source code of my personal website.
It is powered by `hugo` ( [https://gohugo.io/](https://gohugo.io/) ).
The idea is to express the content using the Markdown format, then use hugo to generate the actual html and CSS content.
It uses dev ops to automatically build the server and deploy the new website whenever there is a content update.

## Code structure

This is the structure of the folder if I ever need to update it later

```text
.
├── archetypes
├── assets
│   └── css
│       ├── awards.css
│       ├── contact.css
│       ├── custom.css
│       ├── fix_research.css
│       ├── justify.css
│       └── projects.css
├── content
│   ├── awards
│   │   └── <award>.md
│   ├── home
│   │   ├── about.md
│   │   ├── contact.md
│   │   └── hero.md
│   ├── main-research
│   │   └── <paper>.md
│   └── projects
│       └── <project>.md
├── layouts
│   ├── _default
│   ├── partials
│   │   └── sections
│   └── index.html
├── static
│   ├── files
│   └── images
├── themes
├── hugo.toml
└── README.md
```

While this is the explanation of each single folder:

| Directory                 | Purpose                                                                     |
| ------------------------- | --------------------------------------------------------------------------- |
| `content/home`              | Markdown content for homepage single sections: hero, about, contacts.       |
| `content/main-research`     | Research highlight entries shown in the custom Research Highlights section. |
| `content/awards`            | Award entries rendered as cards in the Awards section.                      |
| `content/projects`          | Project entries rendered as clickable project cards.                        |
| `layouts/partials/sections` | Custom homepage section templates overriding/extending the theme.           |
| `layouts/_default`          | Custom base layout overrides to load CSS.                                               |
| `assets/css`                | Custom CSS processed by Hugo Pipes.                                         |
| `static/images`             | Static images used by the site.                                             |
| `static/files`              | Static downloadable files, such as PDFs or CVs.                             |
| `themes`                    | Hugo theme source, currently `hugo-profile`.                                |

## How to run it locally to test it

```bash
hugo --minify --gc --cleanDestinationDir --baseURL "http://localhost:1313" server
```
