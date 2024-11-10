# Markdown Previewer

This project is a simple **Markdown Previewer** built using **React** and **Vite**, inspired by [freeCodeCamp’s Markdown Previewer](https://markdown-previewer.freecodecamp.rocks/).

## Project Overview

The Markdown Previewer allows users to type in GitHub-flavored Markdown into a text area and see the rendered HTML instantly. The app uses `marked.js` for Markdown parsing.

### Live Demo

Check the app live [here](https://bakdavid.github.io/markdown-previewer/).

## Features

-   Supports GitHub-flavored Markdown.
-   Parses and renders elements like headings, lists, images, links, code, and blockquotes.
-   Instant preview of the Markdown text.
-   Customizable CSS for styling.

## User Stories

The project meets the following user stories:

1. Text area with `id="editor"` to type Markdown.
2. Preview area with `id="preview"` to display HTML.
3. Instant updating of the preview on typing.
4. Default Markdown includes headings, links, lists, images, and more.
5. Uses the `marked` library for Markdown parsing.

## Built With

-   [React](https://reactjs.org/) - UI framework.
-   [Vite](https://vitejs.dev/) - Development and build tool.
-   [Marked.js](https://marked.js.org/) - Markdown parser.
-   [GitHub Pages](https://pages.github.com/) - For hosting.

## Installation

To run the project locally, follow these steps:

1. Clone the repository:

```
git clone https://github.com/bakdavid/markdown-previewer.git
cd markdown-previewer
```

2. Install dependencies:

```
npm install
```

3. Run the development server:

```
npm run dev
```

4. Open `http://localhost:5173/` in your browser to view the app.

## Deploying to GitHub Pages

This project is set up for GitHub Pages deployment:

1. Build the project:

```
npm run build
```

2. Deploy to GitHub Pages:

```
npm run deploy
```

The app will be available at `https://bakdavid.github.io/markdown-previewer/`.

## License

This project is licensed under the MIT License.
