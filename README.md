# The Plain v3.0

The Plain is a minimalist Jekyll theme, designed to focus on writing that really matters to you and your audience. Everything else is just a distraction. Nothing more other than useful and understandable information sharing. I have made a final update to this theme. This theme is suit best for personal blog type, but not limited to. P/S: This theme is originally inspired from Leonard Lamprecht's original [Jekyll theme](https://github.com/leo/leo.github.io) (thanks!).

# Theme Documentary

**NOTE:** This markdown cheatsheet is a typography demo for this theme. Check out this post to learn more about this markdown usage when you want to get started with this theme. Enjoy!

## Typography Elements in One

Let's start with a informative paragraph. **This text is bolded.** But not this one! _How about italic text?_ Cool right? Ok, let's **_combine_** them together. Yeah, that's right! I have code to highlight, so `ThisIsMyCode()`. What a nice! Good people will hyperlink away, so [here we go](#) or [http://www.example.com](http://www.example.com).

<div class="divider"></div>

## Headings H1 to H6

# H1 Heading

## H2 Heading

### H3 Heading

#### H4 Heading

##### H5 Heading

###### H6 Heading

<div class="divider"></div>

## Footnote

Let's say you have text that you want to refer with a footnote, you can do that too! This is an example for the footnote number one [^1]. You can even add more footnotes, with link! [^2]

<div class="divider"></div>

## Blockquote

> Start by doing what's necessary; then do what's possible; and suddenly you are doing the impossible. --Francis of Assisi

**NOTE:** This theme does NOT support nested blockquotes.

<div class="divider"></div>

## List Items

1. First order list item
2. Second item

* Unordered list can use asterisks
- Or minuses
+ Or pluses

<div class="divider"></div>

## Code Blocks

```javascript
var s = "JavaScript syntax highlighting";
alert(s);
```

```python
s = "Python syntax highlighting"
print s
```

```
No language indicated, so no syntax highlighting.
But let's throw in a <b>tag</b>.
```

<div class="divider"></div>

## Mathematics

The theme comes ready with [mathjax](https://www.mathjax.org/) support built in, allowing for both simple inline equations like $$ax^2 + bx + c = 0$$ and much more complex mathematical expressions such as equation $$\eqref{eq:sample}$$ below.

$$
\begin{align}
\nabla \times \vec{\mathbf{B}} -\, \frac1c\, \frac{\partial\vec{\mathbf{E}}}{\partial t}  &= \frac{4\pi}{c}\vec{\mathbf{j}} \\   
\nabla \cdot \vec{\mathbf{E}} &= 4 \pi \rho \tag{2} \label{eq:sample}\\
\nabla \times \vec{\mathbf{E}}\, +\, \frac1c\, \frac{\partial\vec{\mathbf{B}}}{\partial t}  &= \vec{\mathbf{0}} \\
\nabla \cdot \vec{\mathbf{B}}  &= 0\\
\end{align}
$$

<div class="divider"></div>


## Table

### Table 1: With Alignment

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

### Table 2: With Typography Elements

Markdown | Less | Pretty
--- | --- | ---
*Still* | `renders` | **nicely**
1 | 2 | 3

<div class="divider"></div>

## Horizontal Line

The HTML `<hr>` element is for creating a "thematic break" between paragraph-level elements. In markdown, you can create a `<hr>` with any of the following:

* `___`: three consecutive underscores
* `---`: three consecutive dashes
* `***`: three consecutive asterisks

renders to:

___

---

***

<div class="divider"></div>

## Media

### Video Embedded Iframe

- Youtube
```
{% include helpers/video.html url="https://www.youtube.com/embed/fy7q0klb0yI" width="560" height="315" %}
```

- Vimeo
```
{% include helpers/video.html url="https://player.vimeo.com/video/244683457" width="560" height="315" %}
```

### Image

```
{% include image.html name="IMAGE FILE" caption="CAPTION" %}
```

## Credit
- [Easily install Jekyll on Windows with 3 command prompt entries and Chocolatey](https://davidburela.wordpress.com/2015/11/28/easily-install-jekyll-on-windows-with-3-command-prompt-entries-and-chocolatey/)
- [How to make your Jekyll site show up on social](http://aramzs.github.io/jekyll/social-media/2015/11/11/be-social-with-jekyll.html)
- [Including And Managing Images in Jekyll](https://eduardoboucas.com/blog/2014/12/07/including-and-managing-images-in-jekyll.html)
- [Dynamic navigation for Jekyll](https://codegaze.github.io/2015/08/08/how-to-create-a-dynamic-navigation-menu-in-jekyll/)
- [Creating responsive Video Embeds in Jekyll](https://eduardoboucas.com/blog/2016/12/21/responsive-video-embeds-jekyll.html)

[^1]: Footnote number one yeah baby! Long sentence test of footnote to see how the words are wrapping between each other. Might overflowww!
[^2]: A footnote you can link to - [click here!](#)

