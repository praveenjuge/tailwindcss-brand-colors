# Tailwindcss Brand Colors

Tailwind plugin for adding brands colors as background, border and text colors.

## Installation

Add this plugin to your project:

```sh
npm install tailwindcss-brand-colors --save
```

## Usage

Add it to the plugins array of your Tailwind config:

```js
// tailwind.config.js
plugins: [require("tailwindcss-brand-colors")],
```

[See the list of all brand colors available here](https://github.com/praveenjuge/tailwindcss-brand-colors/blob/master/index.js)

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
<p class="text-reddit">Hello World</p>
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
