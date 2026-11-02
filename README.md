# jfbonder.github.io

Personal academic website of [Julián Fernández Bonder](https://github.com/jfbonder) (Department of Mathematics, FCEN, Universidad de Buenos Aires, and Instituto de Cálculo, UBA–CONICET).

**Live site:** <https://jfbonder.github.io>

## Pages

| File | Content |
|---|---|
| `index.html` | Home page: bio, publication summary, teaching, grants and collaborators, students, contact |
| `publications.html` | Complete publication list (preprints and published papers) |
| `teaching.html` | Current and past courses, with links to the course websites |
| `photo.jpg` | Profile photo used on the home page |

It is a static site: plain HTML and CSS, no build step. The `.nojekyll` file tells GitHub Pages not to run Jekyll.

## Updating the content

Everything is in the HTML files. In `index.html`, search for `course-current` (current course), `student-group` (students) and `scholar-stat-block` (publication and citation counts). New papers go in the `Preprints` or `Published papers` lists of `publications.html`, whose subtitle and the counts on the home page are updated by hand.

## Deployment

GitHub Pages, from the `main` branch, root folder (Settings → Pages → Deploy from a branch). Every push to `main` updates the site within about a minute.

## Related repositories

Course material: [analisis1](https://github.com/jfbonder/analisis1), [imc](https://github.com/jfbonder/imc), [transporte-optimo](https://github.com/jfbonder/transporte-optimo), [fundamentos-aprendizaje-profundo](https://github.com/jfbonder/fundamentos-aprendizaje-profundo). Research code: [pxlaplace](https://github.com/jfbonder/pxlaplace), [PINN-eigenvalues-v2](https://github.com/jfbonder/PINN-eigenvalues-v2), [universe25-abm](https://github.com/jfbonder/universe25-abm).

## License

All rights reserved: the texts, publication list and photo are personal content, and the site has no open license.
