# CSS-TOKENS
CSS-Tokens is a curated collection of reusable CSS variables

## 🦄 Introduction

After realizing I was repeatedly setting up and employing the same variables across numerous projects, I had the idea to create this collection of CSS variables. It enhances efficiency, improves coherency, and elevates the overall developer experience when working on projects with custom css.


## 📦 Installation

Getting started with CSS-Tokens is straightforward:

1. Use npm:
```bash
npm install css-tokens
```

2. Use a CDN
```html
<link rel="stylesheet" href="https://unpkg.com/css-tokens/dist/css-tokens.css">
```

3. If you prefer manual integration, copy the variables from our [GitHub repository](https://github.com/boguz/css-tokens) and integrate them into your stylesheet.

## 🚀 Usage

Integrating CSS-Tokens into your project is simple:

1.1 In your CSS, import the CSS Tokens by including:
```css
@import 'css-tokens';
```
1.2 or add a link in your html with
```html
<link rel="stylesheet" href="https://unpkg.com/css-tokens/dist/css-tokens.css">
```

2. **Utilize Variables**: Harness the power of these variables by referencing them in your styles. For example, `color: var(--color-primary);`.

## 🎨 Customization

CSS Tokens encourages flexibility. Should you wish to personalize the variables, simply overwrite any variable with your desired value.
```css
:root {
    --space-base: 14px;
}
```

## 👷 Get Involved

Your insights, ideas and contributions are invaluable. If you encounter issues or have suggestions, please participate by opening issues on our [GitHub repository](https://github.com/boguz/css-tokens). Your involvement drives the growth of this resourceful tool. 😊


##  📣 Used by
If you find CSS Tokens valuable for your projects, I'd love to hear about it! I'm excited to showcase a list of projects where CSS Tokens is making a difference...
