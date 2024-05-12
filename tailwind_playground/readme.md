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
- [Text Color](https://tailwindcss.com/docs/text-color)
- [Text Size](https://tailwindcss.com/docs/text-size)
- [Text Alignment](https://tailwindcss.com/docs/text-alignment)
- [Text Decoration](https://tailwindcss.com/docs/text-decoration)
- [Text Transformation](https://tailwindcss.com/docs/text-transform)
- [Text Overflow](https://tailwindcss.com/docs/text-overflow)

**👉 Font:**
- [Font Family](https://tailwindcss.com/docs/font-family)
- [Font Size](https://tailwindcss.com/docs/font-size)
- [Font Weight](https://tailwindcss.com/docs/font-weight)
- [Font Style](https://tailwindcss.com/docs/font-style)
- [Font Smoothing](https://tailwindcss.com/docs/font-smoothing)

**👉 Padding:**
- [Padding](https://tailwindcss.com/docs/padding)
- [Padding Top](https://tailwindcss.com/docs/padding-top)
- [Padding Right](https://tailwindcss.com/docs/padding-right)
- [Padding Bottom](https://tailwindcss.com/docs/padding-bottom)
- [Padding Left](https://tailwindcss.com/docs/padding-left)
- [Padding X](https://tailwindcss.com/docs/padding-left)
- [Padding Y](https://tailwindcss.com/docs/padding-top)
- [Space Between](https://tailwindcss.com/docs/space-between)
- [Space Around](https://tailwindcss.com/docs/space-around)

**👉 Margin:**
- [Margin](https://tailwindcss.com/docs/margin)
- [Margin Top](https://tailwindcss.com/docs/margin-top)
- [Margin Right](https://tailwindcss.com/docs/margin-right)
- [Margin Bottom](https://tailwindcss.com/docs/margin-bottom)
- [Margin Left](https://tailwindcss.com/docs/margin-left)
- [Margin X](https://tailwindcss.com/docs/margin-left)
- [Margin Y](https://tailwindcss.com/docs/margin-top)

**👉 Width:**
- [Width](https://tailwindcss.com/docs/width)
- [Min Width](https://tailwindcss.com/docs/min-width)
- [Max Width](https://tailwindcss.com/docs/max-width)

**👉 Height:**
- [Height](https://tailwindcss.com/docs/height)
- [Min Height](https://tailwindcss.com/docs/min-height)
- [Max Height](https://tailwindcss.com/docs/max-height)

**👉 Display:**
- [Display](https://tailwindcss.com/docs/display)
- [Visibility](https://tailwindcss.com/docs/visibility)
- [Overflow](https://tailwindcss.com/docs/overflow)
- [Object Fit](https://tailwindcss.com/docs/object-fit)
- [Object Position](https://tailwindcss.com/docs/object-position)
- [Float](https://tailwindcss.com/docs/float)
- [Clear](https://tailwindcss.com/docs/clear)

**👉 Position:**
- [Position](https://tailwindcss.com/docs/position)
- [Top](https://tailwindcss.com/docs/top)
- [Right](https://tailwindcss.com/docs/right)
- [Bottom](https://tailwindcss.com/docs/bottom)
- [Left](https://tailwindcss.com/docs/left)
- [Z Index](https://tailwindcss.com/docs/z-index)

**👉 Overflow:**
- [Overflow](https://tailwindcss.com/docs/overflow)
- [Overflow X](https://tailwindcss.com/docs/overflow-x)
- [Overflow Y](https://tailwindcss.com/docs/overflow-y)
- [Resize](https://tailwindcss.com/docs/resize)

**👉 Visibility:**
- [Visibility](https://tailwindcss.com/docs/visibility)
- [Opacity](https://tailwindcss.com/docs/opacity)
- [Mix Blend Mode](https://tailwindcss.com/docs/mix-blend-mode)

**👉 Shadow:**
- [Box Shadow](https://tailwindcss.com/docs/box-shadow)
- [Shadow Outline](https://tailwindcss.com/docs/shadow-outline)

**👉 Cursor:**
- [Cursor](https://tailwindcss.com/docs/cursor)
- [Pointer Events](https://tailwindcss.com/docs/pointer-events)
- [User Select](https://tailwindcss.com/docs/user-select)

**👉 Background:**
- [Background Color](https://tailwindcss.com/docs/background-color)
- [Background Opacity](https://tailwindcss.com/docs/background-opacity)
- [Background Size](https://tailwindcss.com/docs/background-size)
- [Background Position](https://tailwindcss.com/docs/background-position)
- [Background Repeat](https://tailwindcss.com/docs/background-repeat)
- [Background Attachment](https://tailwindcss.com/docs/background-attachment)
- [Background Image](https://tailwindcss.com/docs/background-image)
- [Background Gradient](https://tailwindcss.com/docs/background-gradient)

**👉 Border:**
- [Border Color](https://tailwindcss.com/docs/border-color)
- [Border Opacity](https://tailwindcss.com/docs/border-opacity)
- [Border Width](https://tailwindcss.com/docs/border-width)
- [Border Style](https://tailwindcss.com/docs/border-style)
- [Border Radius](https://tailwindcss.com/docs/border-radius)

**👉 Flexbox:**
- [Flex Direction](https://tailwindcss.com/docs/flex-direction)
- [Flex Wrap](https://tailwindcss.com/docs/flex-wrap)
- [Flex](https://tailwindcss.com/docs/flex)
- [Justify Content](https://tailwindcss.com/docs/justify-content)
- [Align Items](https://tailwindcss.com/docs/align-items)
- [Align Content](https://tailwindcss.com/docs/align-content)
- [Align Self](https://tailwindcss.com/docs/align-self)
- [Flex Grow](https://tailwindcss.com/docs/flex-grow)
- [Flex Shrink](https://tailwindcss.com/docs/flex-shrink)
- [Order](https://tailwindcss.com/docs/order)
- [Gap](https://tailwindcss.com/docs/gap)
- [Row Gap](https://tailwindcss.com/docs/row-gap)
- [Column Gap](https://tailwindcss.com/docs/column-gap)
- [Flexbox Utilities](https://tailwindcss.com/docs/flexbox)