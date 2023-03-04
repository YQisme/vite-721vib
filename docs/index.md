---
layout: doc

hero:
  name: VitePress
  text: Vite & Vue powered static site generator.
  tagline: Simple, powerful, and performant. Meet the modern SSG framework you've always wanted.
  actions:
    - theme: brand
      text: Get Started
      link: /Example
    - theme: alt
      text: View on GitHub
      link: https://github.com/vuejs/vitepress
---

## [test1:lowercase-source-anchor to lowercase-destination-anchor](./Example#lowercase)

`./Example#lowercase` to `lowercase`

succeed

## [test2:lowercase-source-anchor to UPPERCASE-destination-anchor](./Example#uppercase)

`./Example#uppercase` to `UPPERCASE`

succeed

## [test3:UPPERCASE-source-anchor to lowercase-destination-anchor](./Example#LOWERCASE)

`./Example#LOWERCASE` to `lowercase`
<font color="red">faild</font>

## [test4:UPPERCASE-source-anchor to UPPERCASE-destination-anchor](./Example#UPPERCASE)

`./Example#UPPERCASE` to `UPPERCASE`
<font color="red">faild</font>
