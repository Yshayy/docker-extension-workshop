---
theme: seriph
themeConfig:
  primary: rgb(183, 196, 255)
class: text-center
highlighter: shiki
background: ""
lineNumbers: false
info: |
  ## Slidev Starter Template
  Presentation slides for developers.

  Learn more at [Sli.dev](https://sli.dev)
drawings:
  persist: false
# transition: slide-left
title: Inflight collaboration using Livecycle Docker extension
fonts:
  # basically the text
  sans: 'Roboto'
  # use with `font-serif` css class from windicss
  serif: 'Roboto Slab'
  # for code blocks, inline code, etc.
  mono: 'Fira Code'
---

# Inflight collaboration using Livecycle Docker extension


<h2 class="m6">
Yshay Yaacobi  
</h2>

<img src="/assets/logo.png" class="mx-auto" />


⭐ https://github.com/livecycle/preevy

📄 https://github.com/livecycle/docker-extension

\# https://community.livecycle.io/

---
layout: cover
background: https://images.squarespace-cdn.com/content/v1/5e6542d2ae16460bb741a9eb/1603318636443-A846ACUKNYUBA0RPLJ94/marvin-meyer-SYTO3xs06fU-unsplash.jpg
---

# Hackathons are wonderful


---

# It's all about experimentation

- Learning new skills
- Trying new technologies
- Building new products

---

# Working in team require efficient communication

- No time for heavy processes
- Collaboration between developers, designers, PMs, etc...
- High visibility to WIP products and experiences
- Quick feedback loops and iterations
- Showcasing our work to the world

---
layout: two-cols
---

# Hi, I'm Yshay 👋

- CTO & Co-Founder of Livecycle
- Former Tech lead and Staff Engineer at Asurion
- +15 years of experience in software development
- Led development of OSS projects 
- Cloud development, architecture,   
functional programming, ux, dx, and more...
- Participated and co-organized several hackathons
- Love using Docker & Kubernetes

::right::

<img class="mt-8 mx-auto w-48 rounded-24" src="/assets/yshay.jpg" />
<div class="text-center">
<div class="mt-2 mx-auto">Yshay Yaacobi</div>
<div class="text-xs mx-auto">Yshay@livecycle.io</div>

</div>

<!-- 3m -->
<!-- Done (timing) -->

---

# About <img alt="Livecycle" class="inline-block ml-2" src="/assets/logo.png" />

- Founded in 2021
- Building the next generation of collaboration tools for product teams
- Embedding rich collaboration tools on top of ephemeral environments
- Enhancing PR workflows' more inclusive and efficient
- **Bridging gaps between developers, designers, product managers, and other stakeholders...**

<div style="background-image:url('/lc-background.png')" class="bg-cover bg-center absolute left-0 right-0 bottom-0 h-60"></div>

---

# Agenda

- Livecycle extension - sharing a docker application 
- Compose patterns - sharing different kind of apps
- Developer tools for debugging in-flight apps
- From local to remote environments
- Closing notes

---

# Livecycle extension

- Instantly share your docker application with anyone
- Support private/public environments
- Based on Preevy networking stack
- Demo

---
layout: statement
---

# Compose patterns

---

# Sharing a CLI application

- The problem - no web server for CLI apps
- The solution - adding ttyd magic to Compose
- Demo

---

# Sharing a multi-repo application

- The problem - multiple services in different repositories
- The solution - use docker git context in compose
- Demo

---

# Developer tools for debugging in-flight apps
- Demo

---

# From local to remote environments

- Let's not deal with production yet
- Under the hood, Livecycle's Docker extension is using Preevy
- Preevy is an open-source tool for provisioning ephemeral environments
- Demo

---

# Sharing your app across development pipeline

- Local development - docker extension
- Remote environment - preevy
- PR environments - preevy+CI (GH actions, circleCI orb, etc...)

---

# What's next?

- Taking collaboration to the next level
- Demo  
- Livecycle review tools are in private beta
- Join our Slack community to get early access

---
layout: end
---

# Thank you

Yshay Yaacobi

⭐ https://github.com/livecycle/preevy    
📄 https://github.com/Yshayy/preevy-at-civo  
\# https://community.livecycle.io/

<!--
<div class="text-center mx-auto w-24">

![Alt text](/image-9.png)

</div>
-->

<div class="absolute right-6 bottom-10 text-black bg-white px-6 py-10 rounded-8">

## Questions?

</div>
