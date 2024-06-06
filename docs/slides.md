---
theme: signalwerk
title: Fonts with stylistic, contextual, and ‘random’ alternatives
---

```fm
style: negative
background: true
```

## Hello _👋_

# {{process.content.frontmatter.title}}

_Let's talk about Font-Technology…_

<footer>

2024 · Zurich · Stefan Huber

</footer>

--s--

```fm
style: image
background:
  image: https://portrait.signalwerk.ch/illustration/2020/rgb/w4000/stefan-huber.jpg
  position: 50% 40%
```

## Stefan

<div class="box box--w40p box--bottom box--white box--padding small">

- Developer @ Drupal ZH
- ❦ Typography

</div>

<footer class="footer--right">

Illustration by [Benjamin Güdel](http://www.guedel.biz/) · 2020

</footer>

--s--

## What's a font?

<div class="box box--w100p img--w100p">

![Lexicon](https://cdn.jsdelivr.net/gh/signalwerk/talk.fonts2019@6d66b94b7dd8bd143cae5c902761916ff0b2e60a/img/SVG/impression-lexicon.svg)

</div>

<footer>

Font: Lexicon · Bram de Does († 2015) · 1992

</footer>

--s--

## Traditional Typesetting

![Kerning Bleisatz](https://cdn.jsdelivr.net/gh/signalwerk/talk.fonts2019@c45cf9b95b03f1c597db1484072bcdb80a3524ed/img/kerning/IMG_9713_sh.png)

<footer>

Source: Stefan Huber · 2018

</footer>

--s--

```fm
style: negative
background: true
```

## Typography

# Not only character shapes

--s--

## Traditional Typesetting

![Kerning Bleisatz](https://cdn.jsdelivr.net/gh/signalwerk/talk.fonts2019@c45cf9b95b03f1c597db1484072bcdb80a3524ed/img/kerning/IMG_9862_sh.png)

<footer>

Source: Stefan Huber · 2018

</footer>

--s--

```fm
style: negative
background: true
```

## Technology

# OpenType Fonts

<footer>

Introduction OpenType · 1996

</footer>

--s--

## Webfonts are OpenType

```css
@font-face {
  font-family: "Open Sans";
  src: url("opensans.woff2") format("woff2"), /* Modern Browsers */
      url("opensans.woff") format("woff");
  font-weight: 400;
  font-style: normal;
}
```

--s--

## Digital Typesetting

![Polo](https://cdn.jsdelivr.net/gh/signalwerk/talk.fonts2019@6d66b94b7dd8bd143cae5c902761916ff0b2e60a/img/SVG/Kerning-Class-01.svg)

<footer>

Font: Paratype · PT Sans · Bold · kerning deactivated

</footer>

--s--

## Digital Kerning

![Polo](https://cdn.jsdelivr.net/gh/signalwerk/talk.fonts2019@6d66b94b7dd8bd143cae5c902761916ff0b2e60a/img/SVG/Kerning-Class-02.svg)

<footer>

Font: Paratype · PT Sans · Bold (OpenType) | <small>Digital Kerning since Adobe PostScript · 1984</small>

</footer>

--s--

## Group Kerning for global fonts

<div class="box box--w100p img--w100p">

![Polo](https://cdn.jsdelivr.net/gh/signalwerk/talk.fonts2019@6d66b94b7dd8bd143cae5c902761916ff0b2e60a/img/SVG/Kerning-Class-03.svg)

</div>

<footer>

Font: Paratype · PT Sans · Bold

</footer>

--s--

## Kerning

<div class="box box--w100p img--w100p">

![Polo](https://cdn.jsdelivr.net/gh/signalwerk/talk.fonts2019@6d66b94b7dd8bd143cae5c902761916ff0b2e60a/img/SVG/Kerning-01.svg) <!-- .element: class="pic" -->

</div>

<footer>

Font: Adobe · Garamond Premier Pro · Regular <!-- .element: class="footer" -->

</footer>

--s--

## Kerning

<div class="box box--w100p img--w100p">

![Polo](https://cdn.jsdelivr.net/gh/signalwerk/talk.fonts2019@6d66b94b7dd8bd143cae5c902761916ff0b2e60a/img/SVG/Kerning-02.svg) <!-- .element: class="pic" -->

</div>

<footer>

Font: Adobe · Garamond Premier Pro · Regular <!-- .element: class="footer" -->

</footer>

--s--

```fm
style: negative
background: true
```

## Ligatures and Alternates

# Now switch shapes

--s--

## Ligatures (liga)

<div spellcheck="false" contenteditable="true" style="font-size: 3rem; font-family: 'SourceSerifPro'; font-weight: 400;">

ff fi fl ffi ffl active

</div>

<div spellcheck="false" contenteditable="true" style="font-size: 3rem; font-family: 'SourceSerifPro'; font-weight: 400; font-kerning: none; font-feature-settings: 'kern' off;  text-rendering: optimizeSpeed;">

ff fi fl ffi ffl inactive

</div>

<footer>

Font: Source Serif Pro · liga default: `on`

</footer>

--s--

## Contextual alternates (calt)

<div spellcheck="false" contenteditable="true" style="font-size: 3rem; font-family: 'CaflischScriptPro'; font-weight: 400;">

bloom active

</div>

<div spellcheck="false" contenteditable="true" style="font-size: 3rem; font-family: 'CaflischScriptPro'; font-weight: 400; font-feature-settings: 'calt' off;">

bloom inactive

</div>

<footer>

Font: Caflisch Script Pro · calt default: `on`

</footer>

--s--

## Stylistic sets (ss01 – ss20)

<div spellcheck="false" contenteditable="true" style="font-size: 3rem; font-family: 'Roboto'; font-weight: 400;">

Hello ggg inactive

</div>

<div spellcheck="false" contenteditable="true" style="font-size: 3rem; font-family: 'Roboto'; font-weight: 400; font-feature-settings: 'ss01' on;">

Hello ggg active

</div>

<footer>

Font: Roboto · ss01 default: `off`

</footer>

--s--

```fm
style: negative
background: true
```

## How to find out?

# Use [Fontdrop](https://fontdrop.info/)

--s--

## ‘random’ alternatives

<div spellcheck="false" contenteditable="true" style="font-size: 3rem; font-family: 'BeowolfR22'; font-weight: 400;">

Hello ggg active

</div>

<div spellcheck="false" contenteditable="true" style="font-size: 3rem; font-family: 'BeowolfR22'; font-weight: 400; font-feature-settings: 'calt' off;">

Hello ggg inactive

</div>

<footer>

Font: Beowolf · calt default: `on`

</footer>

--s--

```fm
style: negative
background: true
```

## There's more…

# Special handling for numbers, fractions, …

--s--

```fm
style: negative
background: true
```

## exit 0; thx

# Questions?
