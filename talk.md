---
# try also 'default' to start simple
theme: seriph
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: ./dev.png
# some information about your slides, markdown enabled
title: Welcome to Slidev
info: |
  ## Slidev Starter Template
  Presentation slides for developers.

  Learn more at [Sli.dev](https://sli.dev)
# apply any unocss classes to the current slide
class: text-center
# https://sli.dev/custom/highlighters.html
highlighter: shiki
# https://sli.dev/guide/drawing
drawings:
  persist: false
# slide transition: https://sli.dev/guide/animations#slide-transitions
transition: slide-left
# enable MDC Syntax: https://sli.dev/guide/syntax#mdc-syntax
mdc: true
---

# Chrome Dev Tools + React Profiler

<Toc />

---

## Elements

1. breakpoint on
2. $0 ($0.click dropdown)
3. force element state

---

## Console

```ts twoslash
console.table()
console.count()
console.group()
performance.mark('start')
// insert code here
for (let i = 0; i < 2000000; i++) {}
performance.mark('end')
performance.measure('entryName', 'start', 'end')

const measures = performance.getEntriesByName('entryName')
```

---

## Source

1. workspace
2. sources

---

## Network

1. request initiator and timing

### color coding

🟩 Waiting (TTFB)
Waiting for the first byte from the server

---

## Performance

1. recording

---

## Lighthouse

1. Auditing (project detail)

---

## Node Debugger

1. viewing annoucements

---

## React

1. Components
2. Profiler

---

## components

1. select
2. adjusting props
3. state
4. highlight updates when components render
5. setting to debug hooks

---

## profiler

1. running record
2. always parse hook names
