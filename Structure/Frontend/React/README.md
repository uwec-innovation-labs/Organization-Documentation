# React Project Structure

With React, we want to focus on modularity and reusability.

A very interesting way to organize your projects is with Atomic Design, which can be found here: http://atomicdesign.bradfrost.com/chapter-2/

We are using a simple version of this by seperating our pages and their components up. We don't want to go too crazy with this and we think this is a simple way of organizing the frontend. We will probably change this over time.

## Basic Understanding

Here is a breakdown of how React components will be organized. We are

```
- frontend
    - public
    - components
        - pages
            - ExamplePage
                - components
                - ExamplePage.js
        - reusableComponents
    - scripts
    app.js
    app.css
    index.js
    index.css
```

The frontend will consist of other files and folders as part of React, but we want to focus on this components folder (which you will have to create in a new project, along with the folders within it!).

## Important Notes and Tips

- While this may sound like a strict structure for projects, its not. Feel free to split things up in a friendlier way if you have good reason to do so.
- Its important for the Page.js file to just be a template of components found within that pages components folder or using the components in the resuableComponents folder
- Again, this is one way to organize it, so if you think you can use a better structure, do so.
