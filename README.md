# Debug-CSS

Debug-CSS is a simple CSS file that helps you debug CSS alignment issues in your web projects. It highlights elements on your page, making it easier to spot layout problems and inconsistencies.

## Usage

To use Debug-CSS in your project, simply include the following line in your HTML file:

```html
<link rel="stylesheet" href="[https://raw.githubusercontent.com/yourusername/Debug-CSS/main/debug.css](https://github.com/GoliathReaper/Debug-CSS/raw/refs/heads/main/debug.css)">
```

Or, you can copy the contents of `debug.css` into your own stylesheet.

## How it works

Debug-CSS applies a semi-transparent background color and outline to all elements on the page (except for SVG elements). This makes it easy to see the boundaries and spacing of your elements.

## CSS Code

\`\`\`css
/*! debug.css | MIT License | zaydek.github.com/debug.css */
*:not(path):not(g) {
    color:                    hsla(210, 100%, 100%, 0.9) !important;
    background:               hsla(210, 100%,  50%, 0.5) !important;
    outline:    solid 0.25rem hsla(210, 100%, 100%, 0.5) !important;

    box-shadow: none !important;
}
\`\`\`

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is open source and available under the [MIT License](LICENSE).

