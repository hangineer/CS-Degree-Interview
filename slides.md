---
# You can also start simply with 'default'
theme: seriph
favicon: 'https://cdn-icons-png.flaticon.com/512/3320/3320960.png'

# Plugins
# addons:
#  - excalidraw
#  - '@slidev/plugin-notes'

# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
# background: https://cover.sli.dev
# some information about your slides (markdown enabled)
title: 國立臺北教育大學資訊科學系碩士在職專班
info: 面試簡報準備
# apply unocss classes to the current slide
class: text-center
# https://sli.dev/features/drawing
drawings:
  persist: false
# slide transition: https://sli.dev/guide/animations.html#slide-transitions
transition: slide-left
# enable MDC Syntax: https://sli.dev/features/mdc
mdc: true
layout: intro
# TODO
# qrcode


---

## 國立台北教育大學
114 學年度資訊科學系碩士在職專班

Hannah Wang 王涵
<br />
2025.02

<!-- <div @click="$slidev.nav.next" class="mt-12 py-1" hover:bg="white op-10">
  Press Space for next page <carbon:arrow-right />
</div> -->

<div class="abs-br m-6 text-xl">
  <a href="https://medium.com/@hanforwork896" target="_blank" class="slidev-icon-btn">
    <carbon:logo-medium />
  </a>
  <a href="https://github.com/hangineer" target="_blank" class="slidev-icon-btn">
    <carbon:logo-github />
  </a>
</div>

<!--
The last comment block of each slide will be treated as slide notes. It will be visible and editable in Presenter Mode along with the slide. [Read more in the docs](https://sli.dev/guide/syntax.html#notes)
-->

---
transition: fade-out
layout: center
class: text-center
---

# Outlines

- **經歷簡介**
- **作品介紹**
- **研究計畫介紹**
- **短中長期規劃**

<!--
You can have `style` tag in markdown to override the style for the current page.
Learn more: https://sli.dev/features/slide-scope-style
-->

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

<!-- 經歷簡介 -->
---
transition: slide-up
src: ./pages/intro-slides.md
---

<!-- 作品介紹 1 -->
---
layout: two-cols
layoutClass: gap-16
src: ./pages/projects-slides.md
---

<!-- 作品介紹 2 -->
---
layout: two-cols
layoutClass: gap-16
src: ./pages/projects-slides_2.md
---

<!-- 研究計畫介紹 -->
---
level: 2
src: ./pages/research-slides.md
---

<!-- 短中長期規劃 -->
---
layout: two-cols
layoutClass: gap-4
src: ./pages/plan-slides.md
---
