# ReHive Frontend

This repository contains the frontend code for the ReHive application. It's a React application structured with a focus on component-based architecture.

## Project Structure

The project is structured as follows:

- `src/` - Contains the main application code.
  - `App.jsx` - The main application component.
  - `assets/` - Contains static assets like images.
  - `components/` - Contains reusable components.
  - `container/` - Contains container components like the NavBar.
  - `layouts/` - Contains layout components.
  - `lib/` - Contains utility code like API and validation logic.
  - `pages/` - Contains page components.
  - `router/` - Contains routing logic.
  - `scss/` - Contains SCSS stylesheets.
  - `store.jsx` - Contains Redux store configuration.
  - `toolkit/` - Contains Redux toolkit slices.
- `public/` - Contains public assets like favicons.
- `index.html` - The main HTML file.
- `package.json` - Defines scripts and dependencies.
- `vite.config.js` - Configuration for Vite.
- `tailwind.config.js` - Configuration for Tailwind CSS.

## Getting Started

To get started with development:

1. Clone the repository.
2. Install dependencies with `npm install`.
3. Start the development server with `npm run dev`.

## Building

To build the application, run `npm run build`. This will create a production-ready build in the `dist/` directory.

## Linting

To lint the code, run `npm run lint`.

## Backend

The backend for this application is located in a separate repository. You can find it [here](https://github.com/anonys6/rehive-backend).

## Live Application

The frontend of the application is hosted on Vercel and can be accessed [here](https://rehive-frontend.vercel.app/). The backend is hosted on Heroku.

## Contributing

Contributions are welcome. Please make sure to lint your code before making a pull request.

## License

This project is licensed under the MIT License.