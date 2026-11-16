# Writing Ionic Formulas Lab

An interactive chemistry lab for high school students. For each of 18 ion pairs, students:

1. Drag (or click) ion tiles onto a bench until the net charge is zero, using the fewest ions.
2. Build the compound's formula with symbol and subscript boxes, adding parentheses around polyatomic ions when needed.
3. Type the compound's name.
4. Press **Check my work** for feedback on the bench, the formula, and the name.

Students record their final answers on a paper lab sheet; the page is for practice and feedback.

## Running it

The whole lab is one static file, `index.html`. There is no build step and nothing to install. Open the file in a browser, or host it on any static web server (for example GitHub Pages).

The only external request is to Google Fonts for the typefaces; the page falls back to system fonts if that is unavailable.

## Student data

Progress is saved only in the browser's `localStorage` on the device the student is using. Nothing is sent anywhere: there are no accounts, no analytics, and no server. Clearing the browser's site data, or switching to a different browser or device, starts the lab over.

## Credit

The problem set is taken from the original "Writing Ionic Formulas Lab" (2005 DY, teacher-friendly chemistry). This page is an interactive adaptation of that paper lab.
