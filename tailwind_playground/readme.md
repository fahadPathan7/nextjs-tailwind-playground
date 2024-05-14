# <p align='center'> Tailwind Playground</p>
<p align='center'>This is a simple project to play around with Tailwind CSS.</p>

## 🚀 Documentation
For more information, check out the [Tailwind CSS documentation](https://tailwindcss.com/docs/installation).

## 🚀 Tutorial
For a step-by-step tutorial, check out the [Tailwind CSS tutorial](https://www.youtube.com/watch?v=X7XbjwD6fVY&list=PLHiZ4m8vCp9P23SqlHL0QAqiwS_oCofV2&index=1).

## 🚀 Getting Started
**👉 initial setup**
```bash
npm init -y
```
to create a package.json file.

**👉 install tailwindcss**
```bash
npm i -D tailwindcss
```
to install tailwindcss as a dev dependency.

**👉 create a tailwind.config.js file**
```bash
npx tailwindcss init
```
to create a tailwind.config.js file.

**👉 link the html files in tailwind.config.js file**
```js
/** @type {import('tailwindcss').Config} */
module.exports = {
  content: [
    './pages/*.html',
  ],
  darkMode: "media", // or 'media' or 'class
  theme: {
    extend: {},
  },
  plugins: [],
}
```

**👉 file structure**
1. Create src & output folder.
2. Create a tailwind.css file in the src folder.

**👉 add the following to the tailwind.css file**
```css
@tailwind base;
@tailwind components;
@tailwind utilities;
```
this will include the base, components, and utilities styles in the tailwind.css file. (semi-colon is important)

**👉 add the following to the package.json file**
```json
  "scripts": {
    "build": "tailwindcss -i ./src/tailwind.css -o ./output/tailwind.css -w"
  }
```
here, -i is the input file, -o is the output file, and -w is to watch for changes.

**👉 link the css file to the html files**
```html
<link rel="stylesheet" href="../output/tailwind.css">
```
this will link the tailwind.css file to the index.html file.

**👉 run the following command**
```bash
npm run build
```
to build the tailwind.css file. css file will be created in the output folder. <br>
❌ (don't kill the terminal. new changes will be automatically updated in the output folder.)