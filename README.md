# Markdown-Experiments
Testing different forms of stylings in Github markdown files

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
