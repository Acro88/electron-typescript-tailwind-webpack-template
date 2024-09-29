# Electron TypeScript Tailwind Webpack Template

This template provides a basic structure for an Electron application using TypeScript, Tailwind CSS, and webpack.

## Features

- Electron
- TypeScript
- Tailwind CSS
- Webpack
- ESLint
- Hot Reloading

## Prerequisites

Before you begin, ensure you have the following installed:

- Node.js (LTS version recommended)
- npm (comes with Node.js)

## How to use this template

1. Click the "Use this template" button on the GitHub page of this repository.
2. Name your new project and create the repository.
3. Clone your new repository locally:

    git clone https://github.com/Acro88/electron-typescript-tailwind-webpack-template.git

4. Navigate to the project directory:

   cd your-project-name

5. Install dependencies:

   npm install

6. Run the application in development mode:

   npm start

## Project Structure

.
├── src/
│   ├── main/
│   │   └── index.ts          # Main process
│   ├── preload/
│   │   └── preload.ts        # Preload scripts
│   └── renderer/
│       ├── index.html        # HTML template
│       ├── renderer.ts       # Renderer process
│       └── styles.css        # Styles (including Tailwind)
├── .eslintrc.json            # ESLint configuration
├── .gitignore
├── forge.config.ts           # Electron Forge configuration
├── package.json
├── postcss.config.js         # PostCSS configuration
├── tailwind.config.js        # Tailwind configuration
├── tsconfig.json             # TypeScript configuration
├── webpack.main.config.ts    # Webpack configuration for main process
├── webpack.plugins.ts        # Webpack plugins
├── webpack.renderer.config.ts # Webpack configuration for renderer process
└── webpack.rules.ts          # Webpack rules

## Scripts

- `npm start`: Runs the app in development mode
- `npm run package`: Packages the app
- `npm run make`: Creates a distributable package
- `npm run publish`: Publishes the app
- `npm run lint`: Runs ESLint

## Customization

- Main process: Edit `src/main/index.ts` to add functionality to the main process.
- Renderer process: Modify `src/renderer/renderer.ts` and `src/renderer/index.html` to update the UI and renderer process functionality.
- Styles: Use `src/renderer/styles.css` for custom CSS and Tailwind classes.
- Electron Forge configuration: Adjust `forge.config.ts` for packaging and distribution options.

## Additional Resources

- [Electron documentation](https://www.electronjs.org/docs)
- [TypeScript documentation](https://www.typescriptlang.org/docs/)
- [Tailwind CSS documentation](https://tailwindcss.com/docs)
- [Webpack documentation](https://webpack.js.org/concepts/)

## License

[MIT](LICENSE)
