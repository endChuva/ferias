# 404 Error Page

A minimalist 404 error page with a horizontal gradient background, designed to match the style of [endchuva's Profile](https://endchuva.github.io/Profile/).

## Features

- **Minimalist Design**: Clean and modern layout.
- **Gradient Background**: Smooth gradient from dark gray (`#333`) to light gray (`#ccc`).
- **Responsive**: Works on all screen sizes.

## How to Use

1. Replace the image `sad.jpg` with your own image.
2. Customize the colors in the `style` section of the `index.html` file.
3. Deploy to GitHub Pages by enabling it in your repository settings.

## Customization

- **Change Gradient**: Edit the `background` property in the `body` section:
  ```css
  body {
      background: linear-gradient(to right, #333, #ccc);
  }
  ```
- Replace Image: Update the src attribute in the img tag:
  ```html
  <img src="your-image.jpg" class="image">
  ```
