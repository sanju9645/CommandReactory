# CommandReactory
 Like a cheat sheet, but for React wizards in training!

Bits 'n' Bytes Bliss: My React Nerd Cookbook

## Initializing a new project with Vite
```
npm create vite@latest . --template react
```
initializes the project in the current directory, keeping the setup at the root level of wherever you've navigated to

```
npm create vite@latest {project name} -- --template react
```
creates a new subdirectory (named {project name} in this example) and initializes the project inside it, keeping the parent directory uncluttered with project files


## Installing Tailwind CSS as a PostCSS plugin
```
npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init -p
```

https://tailwindcss.com/docs/installation/using-postcss
```
/** @type {import('tailwindcss').Config} */
export default {
  content: [
    "./index.html",
    "./src/**/*.{js,ts,jsx,tsx}",
  ],
  theme: {
    extend: {
    },
  },
  plugins: [
  ],
}
```

