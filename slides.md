---
# try also 'default' to start simple
theme: default
background: https://i.ibb.co/VWxv3s7/dojo.png
class: 'text-center'
highlighter: shiki
lineNumbers: false
info: |
  ## Digital Dojo - Planning Event

# persist drawings in exports and build
drawings:
  persist: false
fonts:
  # basically the text
  sans: 'Roboto'
  # use with `font-serif` css class from windicss
  serif: 'Robot Slab'
  # for code blocks, inline code, etc.
  mono: 'Fira Code'
---

# Planning

The what, why, and how of this Agile evemt

<div class="pt-8">
  <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
    Press Space for next page <carbon:arrow-right class="inline"/>
  </span>
</div>

<div class="abs-br m-6 flex gap-2">
  <button @click="$slidev.nav.openInEditor()" title="Open in Editor" class="text-xl icon-btn opacity-50 !border-none !hover:text-white">
    <carbon:edit />
  </button>
  <a href="https://github.com/slidevjs/slidev" target="_blank" alt="GitHub"
    class="text-xl icon-btn opacity-50 !border-none !hover:text-white">
    <carbon-logo-github />
  </a>
</div>

<!--
The last comment block of each slide will be treated as slide notes. It will be visible and editable in Presenter Mode along with the slide. [Read more in the docs](https://sli.dev/guide/syntax.html#notes)
-->

---
layout: image-right
image: https://www.invoicera.com/blog/wp-content/uploads/2021/12/Sprint-Planning-7-Best-Strategies-for-Successful-Project-Management.png
---

# What is Planning?

<br>
<br>
<br>

Planning is the event that kicks off the next increment of work within a team. 

Purpose: Come to an agreement on what can be completed in the next increment and how that work will be achieved. 

If done correctly, Planning creates an environment where the team is motivated, challenged, and <i>aligned together for success. </i>


---
layout: image-left
image: https://pmtips.net/Portals/0/EasyDNNNews/1892/700600p546EDNmainimg-the-art-of-negotiation.jpg
---

# Who participates?


<b>You cannot do planning without the Product Owner and the multidisiciplinary team.</b>

<br>
<br>

The Product Owner represents what we traditionally have called our clients, or the business. 

Their role is to describe the objective (or goal) of the next increment and what backlog items contribute to that goal.

The team's role is to determine what can be done in the coming sprint and what tasks they will do during the sprint to make that happen.

---
layout: center
font-size: 1em
---

# How does it work?


### Inputs

Increment Length - the amount of time you will have to work on the current increment (e.g. 2 weeks) [Sprint Length]

Product Backlog - a list of ‘stuff’ that could potentially be part of the current inrement.

### Outputs

Goals - your 'north star' for the increment, to help you know if you are working on the right things. [Sprint Goals]

Increment Backlog - the items from the Product Backlog that you will work on for this increment [Sprint Backlog]

Action Plan - a plan of how, as a team, you will work through the Increment backlog. 


