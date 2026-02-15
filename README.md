# Become an Agentic Architect – Capstone Projects

This repository hosts the public **Wall of Fame** for capstone projects built in Carmelo Iaria’s Maven course  
[“Become an Agentic Architect / Mastering Multiagent AI Systems with CrewAI”][course]. Each card in the gallery links to a full showcase page with screenshots, architecture, and the multi‑agent crew design behind the app.[web:11][web:65]

The site is published via GitHub Pages at:

> https://synaptic-ai-consulting.github.io/become-an-agentic-architect-projects/index.html

[course]: https://maven.com/carmelo-iaria/mastering-mas-crewai

---

## What this repo contains

- `index.html`  
  The main gallery page (Wall of Fame) that lists all capstone projects and links to their showcases. It reads from `projects.json` to render cards client‑side.[web:34][web:75]

- `projects.json`  
  A JSON file containing one entry per project, including title, author, cohort, hero image path, and link to the project’s showcase page.

- `projects/<slug>/`  
  One folder per project, where `<slug>` is a URL‑friendly identifier, for example:

  ```text
  projects/jan26-onboarding-crew-jane-doe/
    index.html      # project showcase page
    hero.png        # main thumbnail shown on the gallery card
    screen-1.png
    screen-2.png
    ...
