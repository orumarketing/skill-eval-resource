# Front-End Developer — Practical Exercise

## Team Member Cards

Thanks for taking the time to do this. The exercise below is a small, real-world-style
task similar to work you would do on the job. We're more interested in **how you think and the
decisions you make** than in pixel-perfect polish — please read the "How we'll evaluate"
section before you start, because it will change how you spend your time.

---

### The scenario

Our site already has a **three-column card module** (provided in the starter files). An editor
now wants a variation with more of an "about page" feel: a grid of **team members** —
think faculty, staff, or residence-hall RAs — shown as cards.

Your job is to build that new variant.

---

### What you'll build

A responsive **team-member card grid**, delivered as **standalone HTML, CSS, and JavaScript**.
It does not need to run inside any CMS — assume that integration would be handled later. Build
it as a self-contained page we can open in a browser.

The grid should present the team using **four columns on desktop**. Build it to live in our
**full-width page template** — you can see that template, and the rest of our components, in our
component library: https://oru.edu/component-library/ . Everything else about how it behaves is
up to you.

Each card draws from these six fields:

- **Photo**
- **Name**
- **Title**
- **College / Department**
- **Phone**
- **Email**

---

### The data

Below is a realistic export from the directory. Use **all eight** of these people in your build.
For photos, use any placeholder/headshot image service you like (e.g. a generic avatar service).

| Name | Title | College / Department | Phone | Email | Photo |
|------|-------|----------------------|-------|-------|-------|
| Maya Chen | Lecturer | Department of Art | (918) 555-0142 | maya.chen@example.edu | yes |
| Bartholomew Throckmorton-Whitfield III | Associate Professor of Mechanical and Aerospace Engineering | College of Science, Engineering & Technology | (918) 555-0177 | bartholomew.throckmorton-whitfield@example.edu | yes |
| James Okafor | Resident Assistant | Wesley Residence Hall | (918) 555-0163 | james.okafor@example.edu | yes |
| Sofía Reyes | Adjunct Instructor | Department of Music | (918) 555-0119 | — | yes |
| Daniel Kim | Professor | Department of Theology | — | daniel.kim@example.edu | yes |
| Grace Abara | Department Chair | Department of Biology | — | — | yes |
| Robert Williams | Director of Undergraduate Admissions & Enrollment Services | Office of Admissions | (918) 555-0188 | robert.williams@example.edu | yes |
| Li Wei | Postdoctoral Research Fellow | Department of Chemistry & Biochemistry | (918) 555-0150 | li.wei@example.edu | yes |

---

### Starter files

You'll receive a small repository containing:

- **`root-variables.css`** — the design system's root variables (color, spacing, typography, etc.).
- **`three-column-styles.css`** and **`three-column-comp.html`** — our existing three-column card.

These represent the look and feel of the rest of the site. We would like the new component to feel
like it belongs alongside them. The starter files are yours to read, reuse, and build on however
you see fit.

---

### Deliverables

Please send back two things:

1. **The component** — your HTML, CSS, and JS files, runnable by opening the page in a browser.

2. **A short decisions log** (a `DECISIONS.md` or similar — a half-page is plenty). In it, note
   any points where the brief was unclear or where you had to make a judgment call, what you
   decided, and why. Also feel free to note anything you would do with more time, and what you chose
   *not* to do. This document matters to us as much as the code.

---

### How we'll evaluate

We care more about your **reasoning, judgment, and how you handle the realities of the data**
than about visual flourish. A robust, plain component with a thoughtful decisions log will score
better than a beautiful one that falls apart on the edges. Specifically, we're looking at:

- How well the component fits the existing design system and website.
- How it holds up across the full set of data, not just the easy cases.
- The quality of the thinking in your decisions log.

You're welcome to use whatever tools you normally use, including AI assistants. Just make sure
the result is something you understand and can explain and modify — see the next section.

---

### Time

Please aim for about **2–3 hours**, and don't spend more than four. This is deliberately more than
you can perfect in the time given; prioritizing well is part of the exercise. If you run out of
time, just note what you would tackle next in your decisions log.

To be clear about where to put that time: **functionality and thought process matter more than
design "wow factor."** We want the component to feel on-brand, but a polished animation is no
substitute for a component that holds up across all eight people and has a sensible plan for the
basics — spacing, alignment, and how rows and columns behave. Solid and well-reasoned beats
flashy-but-fragile every time.

---

### What happens next

In a follow-up conversation, we'll ask you to walk us through your component and make a few small
changes to it live, together. Nothing to prepare for — just keep your code in a state you can
navigate and talk through comfortably.

---

### Submitting

Please send us **two things**:

1. **A link to a GitHub repository** with your HTML, CSS, JS, and decisions log. You're welcome to
   keep the repo **private** — just add **`orumarketing`** as a collaborator so we can read the code.

2. **A live link to the component running**, so we can see it in a browser. The easiest way is to
   deploy it for free with a service like **Vercel, Netlify, or Cloudflare Pages** (all of which can
   publish from a private GitHub repo at no cost) and send us the preview URL. If you would rather, you
   can instead build and share it from an online editor like **CodeSandbox** or **StackBlitz** — a
   shared link there shows both the running component and the code, and covers both items above.

If anything about the brief is unclear, it's completely fine to ask — though note that *what* you
choose to ask about is something we find interesting too.

Good luck, and have fun with it.
