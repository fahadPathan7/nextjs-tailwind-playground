# Tailwind Playground
This is a simple project to play around with Tailwind CSS.

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

**👉 file structure**
1. Create src & output folder.
2. Create a tailwind.css file in the src folder.

**👉 add the following to the tailwind.css file**
```css
@tailwind base;
@tailwind components;
@tailwind utilities;
```

**👉 add the following to the package.json file**
```json
  "scripts": {
    "build": "tailwindcss -i ./src/tailwind.css -o ./output/tailwind.css -w"
  }
```
here, -i is the input file, -o is the output file, and -w is to watch for changes.

**👉 add the following to the index.html file**
```html
<link rel="stylesheet" href="./output/tailwind.css">
```
this will link the tailwind.css file to the index.html file.

**👉 run the following command**
```bash
npm run build
```
to build the tailwind.css file. css file will be created in the output folder.

## 🚀 Topics Covered
**👉 Text:**
- class: text-<color> (text-red-500) - to change the text color.
- class: text-<size> (text-2xl) - to change the text size.