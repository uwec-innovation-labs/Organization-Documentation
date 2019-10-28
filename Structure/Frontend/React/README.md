# React Project Structure

With React, we want to focus on modularity and reusability. We will be taking a page from Chemistry by following something called Atomic Design Methodology.

Resources for this can be found here: http://atomicdesign.bradfrost.com/chapter-2/

## Basic Understanding

Here is a breakdown of how React components will be organized. This may change as we find better ways of organizing.

```
- frontend
    - public
    - components
        - 1-atoms
        - 2-molecules
        - 3-organisms
        - 4-templates
        - 5-pages
    - scripts
    app.js
    app.css
    index.js
    index.css
```

The frontend will consist of other files and folders as part of React, but we want to focus on this components folder (which you will have to create in a new project, along with the folders within it!).

## Important Notes and Tips

- Within **Atoms**, do not set any margins and positions
- Only **Organisms** and **Molecules** can set margins and positions
- **Templates** have only one purpose, to set the grid of pages, but never the positions of specific elements
- Pages only purpose is to give the information to the **Templates**
- For Atoms, try to keep things organized, dynamic, and modular
- Take the time to evaluate and refactor components to fit into this methodology. Its important to evaluate and question the engineering choices made to ensure the most optimal solution
- There might not be a perfect place for a new component. Try to find a place that makes the most sense.
- When using frameworks like Bootstrap or Material-UI, decide if you want to break it down to atoms, or not. If you are not sure, its always safe have them as atoms. If you want something done faster, than opt to not do that and just integrate those components as if they are already atoms
