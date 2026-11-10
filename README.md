# Fairfield University Microplastics Lab

This is a self-contained static website. Open `index.html` in a browser to explore the two lab rooms, current project interactions, Dr. Walker's office, the past-project cabinet, article shelf, and protocol views.

## Updating the content

The project and equipment text lives in the `data` object in `index.html`. The article and protocol lists are in the `openModal` function, and the cabinet entries are in the `archives` list. Replace the clearly marked prompts with lab-approved summaries and methods as the team provides them.

The archive links to `assets/river-otters-poster.pdf`, a copy of the supplied river otter behavior poster draft. Confirm its archive status and public sharing approval before publishing it. It is not automatically linked to the current otter microscope project.

## Publishing

The site uses plain HTML, CSS, and JavaScript. In the repository, open **Settings → Pages**, choose **Deploy from a branch**, then select `main` and `/(root)` to publish it through GitHub Pages.
