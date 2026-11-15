# leaven-labs.github.io

The home page of [Leaven Labs](https://github.com/Leaven-Labs): free, open-source software for churches.

It is one plain page with no build step:

- `index.html` holds the page, its styles and its script.
- `assets/` holds the logo (`icon.svg`), each app's icon and the screenshots.

GitHub Pages publishes the `main` branch as it is. To see a change before it is published, open
`index.html` in a browser.

## Adding a project

Public repositories of the organization appear on the page by themselves, as a plain card with the
repository's description. The page also asks GitHub for the newest version of each app.

To give a project a full card with an icon, a screenshot and its own words, copy one of the
`<article class="project" data-repo="...">` blocks in `index.html`, set `data-repo` to the
repository's name, and put its pictures in `assets/`.
