---
date: 2025-03-05T14:00:00
---

# How did I do this?

Let's start this thing with a technical writeup about how this very blog got setup in detail.

## A list of tools

I used a few things on this little journey and I will try to show all of them. Let's start with a simple list:

- [MkDocs](https://www.mkdocs.org/user-guide/deploying-your-docs/)
- [Material for MkDocs](https://github.com/squidfunk/mkdocs-material)
- [Github Repo](https://github.com/neuromancer10/blog)
- For testing and preview purpose I used: [Docker Desktop](https://www.docker.com/products/docker-desktop/)[^1]
- For editing I am using [VS Code](https://code.visualstudio.com)

[^1]: Yes, I am working on windows most of time and I am ashamed of it

### MkDocs

Mkocs is a `Static Site Generator` that entirly based around markdown files. Since I am more of a developer than a designer, that was exactly what I was looking for. I do know markdown and have used it quite a bit in the past.
With `MkDocs` I not only found a site generator that uses markdown but also a tool that is really easy to configure and fast to setup. Also it looks good.

#### Configuring MkDocs

As I said it is quite easy to get results and for the full documentation you should look at the original at 
- [MkDocs Vanilla Docs](https://www.mkdocs.org)
- [MkDocs Material Docs](https://squidfunk.github.io/mkdocs-material/)

The setup I used here looks like this:

1. Creating the basic folder structure for a blog project

```bash
blog # this is the root folder, the name is not important
 ├───── docs
 │        ├───── blog
 │        │        ├───── posts
 │        │        │        ├──── post1.md
 │        │        │        ├──── post1.md
 │        │        │        └──── post1.md
 │        │        └───── index.md
 │        └───── index.md
 └────── mkdocs.yml
```

