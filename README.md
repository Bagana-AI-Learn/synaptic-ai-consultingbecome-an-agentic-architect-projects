# Become an Agentic Architect – Capstone Projects

This repository hosts the public **Wall of Fame** for capstone projects built in Carmelo Iaria’s Maven course  
[“Become an Agentic Architect / Mastering Multiagent AI Systems with CrewAI”][course]. Each card in the gallery links to a full showcase page with screenshots, architecture, and the multi‑agent crew design behind the app.

The site is published via GitHub Pages at:

> https://bagana-ai-learn.github.io/synaptic-ai-consultingbecome-an-agentic-architect-projects/

**Note:** To enable GitHub Pages, go to Repository Settings → Pages → Source: select `main` branch and `/ (root)` folder, then click Save. The site will be available at the URL above after deployment (typically 1-2 minutes).

[course]: https://maven.com/carmelo-iaria/mastering-mas-crewai

---

## What this repo contains

- `index.html`  
  The main gallery page (Wall of Fame) that lists all capstone projects and links to their showcases. It reads from `projects.json` to render cards client‑side.

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
  ```

---

## Contributing

Students must:

1. **Use the provided Cursor prompt** when building the capstone.
2. **Add a unique `projects/<slug>/` folder** (e.g. `projects/jan26-onboarding-crew-jane-doe/`) with the showcase page and assets.
3. **Append a valid JSON object to `projects.json`** so the project appears on the Wall of Fame.
4. **Commit & push to `main`** to submit the project.
