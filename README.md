# Tailwindcss Brand Colors

Tailwind plugin for adding various brands as background, border and text colors. This plugin requires **Tailwind CSS 1.6** or later.

## Installation

Add this plugin to your project:

```sh
npm install tailwind-brand-colors --save
```

## Usage

For background color:

```html
<div class="bg-google">Hello World</div>
```

For border color:

```html
<div class="border-twitch border">Hello World</div>
```

For text color:

```html
<div class="text-reddit">Hello World</div>
```

## Add your own colors

```js
// tailwind.config.js
module.exports = {
  theme: {
    extend: {
      colors: {
        tailwind: "#00b4b6",
      },
    },
  },
};
```
