# MS ITM Readiness Bootcamp

Free 6-week online prep for admitted MS ITM students: Python, OOP and SQL foundations for MIS 6382 and BUAN 6320. Lessons run Python in the browser (Pyodide), so students install nothing to start.

## Files

| File | What it is |
|---|---|
| `index.html` | Home page: week list and Week 0 setup |
| `week01.html` | Week 1: Python Basics |
| `week02.html` | Week 2: Functions and Strings |
| `week03.html` | Week 3: Collections, Errors and Files |
| `week04.html` | Week 4: Objects and Classes, plus the Python readiness check |
| `week05.html` | Week 5: SQL Queries |
| `week06.html` | Week 6: SQL Design, plus the database readiness check |
| `notebooks/` | Optional Jupyter versions for students who prefer notebooks |
| `.nojekyll` | Tells GitHub Pages to serve files as-is |

Answer keys are intentionally **not** in this repository. Keep them in a private location for lab managers.

## Publish with GitHub Pages

1. Create a repository (for example `itm-bootcamp`) and upload every file in this folder, including `.nojekyll`.
2. Go to **Settings > Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, branch `main`, folder `/ (root)`, then **Save**.
4. After a minute or two, the site is live at `https://<your-username>.github.io/itm-bootcamp/`.

## Student progress

Each week page saves progress in the student's browser and has a **Submit my progress** button that opens the MS ITM Weekly Progress Microsoft Form, pre-filled. Responses collect in the form's Excel sheet for lab managers.

## Adding a week

Add the new `weekNN.html`, then on `index.html` change that week's card from a `div` with the "Coming soon" tag to an `a` link with the "Open" tag.
