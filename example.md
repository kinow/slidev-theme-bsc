---
theme: ./
class: text-center
highlighter: shiki
lineNumbers: false
info: |
  Presentation from the BSC about Containers.
drawings:
  persist: false
transition: slide-left
venue: Online
date: 'yes'
hideInToc: true
layout: cover
fonts:
  sans: 'Calibri'
  fallback: false
slides-title: Slidev BSC Theme
slides-date: '14/08/2023'
slides-venue: 'BSC-CES - MWT'
---

# Slidev BSC Theme

---
layout: default
hideInToc: true
---

<div class="center1">

# Bruno P. Kinoshita

Research Engineer

<p>
Computational Earth Sciences | Earth Sciences Department<br />
Barcelona Supercomputing Center - Centro Nacional de Supercomputación<br />
Address: C/ Jordi Girona, 31, 08034 Barcelona | Torre Girona, 2nd Floor<br />
BSC Website: https://www.bsc.es/<br /></p>

</div>

---
layout: default
hideInToc: true
---

# Agenda

<Toc :maxDepth="2" />

---
layout: intro
hideInToc: true
---

# Your title goes here

---
layout: default
---

# What is Slidev?

Slidev is a slides maker and presenter designed for developers, consist of the following features

- 📝 **Text-based** - focus on the content with Markdown, and then style them later
- 🎨 **Themable** - theme can be shared and used with npm packages
- 🧑‍💻 **Developer Friendly** - code highlighting, live coding with autocompletion
- 🤹 **Interactive** - embedding Vue components to enhance your expressions
- 🎥 **Recording** - built-in recording and camera view
- 📤 **Portable** - export into PDF, PNGs, or even a hostable SPA
- 🛠 **Hackable** - anything possible on a webpage

<br>
<br>

Read more about [Why Slidev?](https://sli.dev/guide/why)


---

# Navigation

Hover on the bottom-left corner to see the navigation's controls panel

### Keyboard Shortcuts

|     |     |
| --- | --- |
| <kbd>space</kbd> / <kbd>tab</kbd> / <kbd>right</kbd> | next animation or slide |
| <kbd>left</kbd>  / <kbd>shift</kbd><kbd>space</kbd> | previous animation or slide |
| <kbd>up</kbd> | previous slide |
| <kbd>down</kbd> | next slide |

---
layout: image-right
image: 'https://source.unsplash.com/collection/94734566/1920x1080'
---

# Code

Use code snippets and get the highlighting directly!

```ts
interface User {
  id: number
  firstName: string
  lastName: string
  role: string
}

function updateUser(id: number, update: Partial<User>) {
  const user = getUser(id)
  const newUser = { ...user, ...update }
  saveUser(id, newUser)
}
```

---
layout: center
class: "text-center"
---

# Learn More

[Documentations](https://sli.dev) / [GitHub Repo](https://github.com/slidevjs/slidev)

---
layout: thank-you
slides-email: ENTER_YOUR_EMAIL_ID_HERE
---
