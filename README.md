# Yi Li: Personal Website

The source for **<https://1iiiiii.github.io/Personal-Website/>**, a [Quarto](https://quarto.org) website hosting my blog posts for *AEDS 6400 Computational Methods for Economists* (University of Pennsylvania, Fall 2026).

The site only contains the **writing**. Posts that involve a coding project keep their analysis code, data and replication instructions in a **separate repository**, linked below and at the end of each post.

## Posts

| # | Post | Source in this repo | Code and replication |
|---|---|---|---|
| 1 | [Understanding the Nonfarm Payroll Data](https://1iiiiii.github.io/Personal-Website/blog/posts/post1/)
| 2 | [How Feasible is Sweetgreen's Expansion Goal?](https://1iiiiii.github.io/Personal-Website/blog/posts/post2/) | `blog/posts/post2/` | [Web-Scraping-in-R](https://github.com/1iiiiii/Web-Scraping-in-R) |
| 3 | [Decomposition of Differences between CES and CPS Employment Data](https://1iiiiii.github.io/Personal-Website/blog/posts/post3/) | `blog/posts/post3/` | [Data-Visualization-in-R](https://github.com/1iiiiii/Data-Visualization-in-R) |

Folders `post4` onward are still ongoing and will be updated as the semester goes. 

## Layout

```
_quarto.yml          site settings: navbar, theme, output to docs/
theme.scss           site styling
index.qmd            home page
about.qmd            about page
resume.qmd           CV page
blog/
  index.qmd          the "Writing" listing page
  posts/
    _metadata.yml    defaults shared by every post (TOC, figure size, freeze)
    _template.qmd    starting point for a new post
    postN/           one folder per post: index.qmd plus its figures
images/, files/      site images and the CV PDF
_freeze/             cached results of post code chunks (see below)
docs/                the rendered site, which GitHub Pages serves. Do not edit by hand.
```
