---
title: Markdown Experiments
authors: 
- Edson Ayllon
---

# Markdown-Experiments

Testing different forms of stylings in Github markdown files

## YAML frontmatter

YAML-formatted metadata goes at the beginning of a document. Converts to a horizontal table

```
---
title: Markdown Experiments
authors: 
- Edson Ayllon
---
```

## Link references

```markdown
![cat][id]

[id]: https://octodex.github.com/images/dojocat.jpg
```

![cat][id]

[id]: https://octodex.github.com/images/dojocat.jpg

## Figure captions

Workaround for now. 

```markdown
![cat][id]
<p align="center">
  <b>Figure 1.</b> A cat
</p>
```

![cat][id]
<p align="center">
  <b>Figure 1.</b> A cat
</p>

## Mixed blockqoute styles

```markdown
> # Heading 1
> ## Heading 2
> ### Heading 3
> **Bold** *Italic* ~~Strike~~
```

> # Heading 1
> ## Heading 2
> ### Heading 3
> **Bold** *Italic* ~~Strike~~

## Comments

```
<!-- html comment -->

[//]: # (Unused variable as a comment)
```

<!-- html comment -->

[//]: # (Unused link reference as a comment)


## Collapsible sections

```html
<details>
<summary>"Click text to expand"</summary>
Hidden details
</details>
```


<details>
<summary>"Click text to expand"</summary>
Hidden details
</details>
  
## Badges

See https://github.com/badges/shields.

```
![version](https://img.shields.io/badge/version-1.2.3-blue)
```

![version](https://img.shields.io/badge/version-1.2.3-blue)

## Footnotes

```
## Footnotes

Inline text.<sup id="a1">[1](#f1)</sup>

[<b id="f1">1.</b>](#a1) Footnote content here. 

Inline text [[1]](#Footnotes).

[1] Footnote content here. 
```

Inline text.<sup id="a1">[1](#f1)</sup>

[<b id="f1">1.</b>](#a1) Footnote content here. 

Inline text [[1]](#Footnotes).

[1] Footnote content here. 

## Latex Equations

See [Online LaTeX Equation Editor](https://www.codecogs.com/latex/eqneditor.php) or [Quick Latex](https://www.quicklatex.com/).

```
![equation](https://latex.codecogs.com/gif.latex?F_n%20%3D%20F_%7Bn-1%7D%20&plus;%20F_%7Bn-2%7D)
```

![equation](https://latex.codecogs.com/gif.latex?F_n%20%3D%20F_%7Bn-1%7D%20&plus;%20F_%7Bn-2%7D)
