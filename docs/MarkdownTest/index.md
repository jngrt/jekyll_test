---
layout: minimal 
what: this is the yaml front matter which can be used for configuration, for example
auth_level: 2
that: would specify a certain authentication level you need to access this file.
---

# The tutorial tutorial

- Intro
- Github and content management
  - adding new item
- Markdown
  - headings
  - code blocks
  - links
  - links within tutorial
  - links to other documentation items
  - images / assets
- YAML
  - config options
  - version indication
  - sidebar order
- Advanced
  - splitting up larger documents
- Publishing 
  - draft / published

## Intro
This tutorial provides guidelines on how to write content for the developers portal. The developer portal is setup in such a way that content and layout are nicely separated. The content will solely consist of [Markdown](http://daringfireball.net/projects/markdown/) files with some [YAML](http://www.yaml.org/) configuration added to it (and maybe some images).

## Github and content management
To be able to easily modify and add to the documentation we chose to make it into a github repo. 
[Link to github repo](http://TODO)

### Adding a new documentation item
To add a new documentation item just clone the repository. Create a new directory in the right place or copy the template directory
```Shell
git clone https://TODO
git cd TODO
etc
```

### Committing new items
New items can all be added on the master branch. I don't think there will be many conflicts, because each item will live in it's own directory. So committing will just be as easy as:
```Shell
git add .
git commit -am "added documentation item <title>"
git push origin master
```
See the information on publishing (below) for more info.

## Markdown
The syntax chosen to write all content is Markdown. Mostly because it's easily readible in plain text, it offers all necessary content structuring 

## Headings used 

Documentation items would use a 

### A third level heading: Code 

Adipiscing elit. Nullam placerat mi.  Velit nibh egestas libero, vitae pellentesque elit augue ut massa. Nulla consequat.

When using blocks of code in your document use the following backtick notation

```Language
Some code $"#"%^! 
with crazy symbols that will show up correct
```

At some point we might add nice highlighting for [these languages](https://github.com/github/linguist/blob/master/lib/linguist/languages.yml)

Another way to include code is by adding a link to a gist:
<script src="http://gist.github.com/118964.js"></script>

### Another third level 

Sem. Pellentesque tellus augue, tempus nec, laoreet at, porttitor blandit, leo. Phasellus in odio. Duis lobortis, metus eu laoreet tristique, pede.

## Second level

Vestibulum eu, elementum et, gravida quis.

- In ligula dapibus egestas. Donec.
- Et ligula vel quam.
- Porttitor quam odio at est. Proin eleifend nisi et.
- Tempus neque. Duis tincidunt commodo elit. Aenean pellentesque.


