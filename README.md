# NextJS Intro

This is a simple Next.js project that demonstrates the basic features of Next.js, including routing, server-side rendering, and API usage.

## Project Structure

- `pages`: This directory contains all the pages of the application. Each file corresponds to a route based on its name.
- [components](https://github.com/mochafreddo/nextjs-intro/blob/main/pages/about.js#1%2C20-1%2C20): This directory contains reusable React components.
- `public`: This directory contains static files like images.
- [styles](https://github.com/mochafreddo/nextjs-intro/blob/main/pages/_app.js#2%2C12-2%2C12): This directory contains global CSS styles.

## Key Files

- `pages/index.js`: The home page of the application. It fetches movie data from an API and displays it.
- `pages/about.js`: A simple about page.
- `pages/404.js`: A custom 404 error page.
- `pages/movies/[...params].js`: A dynamic route that displays details for a specific movie.
- `components/NavBar.js`: A navigation bar component.
- `components/Seo.js`: A component for setting the page title using Next.js's Head component.
- `components/Layout.js`: A layout component that wraps all pages and includes the navigation bar.

## Setup

1. Clone the repository.
2. Install the dependencies using `npm install`.
3. Start the development server using `npm run dev`.

## Scripts

- [dev](https://github.com/mochafreddo/nextjs-intro/blob/main/package.json#6%2C6-6%2C6): Starts the development server.
- [build](https://github.com/mochafreddo/nextjs-intro/blob/main/package.json#7%2C6-7%2C6): Builds the application for production.
- [start](https://github.com/mochafreddo/nextjs-intro/blob/main/package.json#8%2C6-8%2C6): Starts a production server.
- [lint](https://github.com/mochafreddo/nextjs-intro/blob/main/package.json#9%2C6-9%2C6): Runs ESLint on the project.

## Environment Variables

- [API_KEY](https://github.com/mochafreddo/nextjs-intro/blob/main/next.config.js#3%2C7-3%2C7): Used to authenticate requests to the movie API.

## Dependencies

- [react](https://github.com/mochafreddo/nextjs-intro/blob/main/package.json#12%2C6-12%2C6): A JavaScript library for building user interfaces.
- [react-dom](https://github.com/mochafreddo/nextjs-intro/blob/main/package.json#13%2C6-13%2C6): React package for working with the DOM.
- [next](https://github.com/mochafreddo/nextjs-intro/blob/main/package.json#6%2C13-6%2C13): A framework for building React applications with server-side rendering.

## Dev Dependencies

- [eslint](https://github.com/mochafreddo/nextjs-intro/blob/main/package.json#17%2C6-17%2C6): A tool for identifying and reporting on patterns in JavaScript.
- [eslint-config-next](https://github.com/mochafreddo/nextjs-intro/blob/main/package.json#18%2C6-18%2C6): ESLint configuration for Next.js projects.

## Note

This project uses the latest JavaScript standards and follows the Conventional Commits specification for commit messages.
