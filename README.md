# Cobalt2 Pygments.css Theme

A [Pygments](https://pygments.org/) CSS theme inspired by [Wes Bos’ Cobalt2](https://github.com/wesbos/cobalt2) color scheme.

Perfect for code highlighting in static sites, blogs, and documentation.

## Preview

![Cobalt2 Theme Preview](https://raw.githubusercontent.com/joshmcarthur/cobalt2-pygments/main/preview.png)
*Note: This is a representative image - actual appearance may vary slightly.*

If you'd like to see it in action, check out my [blog](https://joshmcarthur.com/).

## Installation

1. **Download** the [`cobalt2.css`](./cobalt2.css) file.
2. **Include** it in your project’s CSS or SCSS build process.
   - For Jekyll/Sass: Place in your `_sass` directory and import in your main stylesheet:
     ```scss
     @import "vendor/highlighter-themes/cobalt2";
     ```
   - For plain CSS: Link it in your HTML.

## Usage

This theme is designed for use with Pygments-generated HTML.
Make sure your code blocks use the `.highlight` class, e.g.:

```html
<pre class="highlight"><code>def hello_world():
    print("Hello, world!")</code></pre>
```

## Colors

| Element      | Color      | Hex       |
|--------------|------------|-----------|
| Background   | Blue       | #193549   |
| Foreground   | White      | #ffffff   |
| Comment      | Blue       | #0088ff   |
| Keyword      | Purple     | #c792ea   |
| String       | Green      | #a5ff90   |
| Number       | Yellow     | #ffe484   |
| Error        | Red        | #ff637b   |
| Operator     | Cyan       | #39e9f9   |
| ...          | ...        | ...       |

See the CSS file for the full mapping.

## Credits

- **Original Cobalt2 Theme:** [Wes Bos](https://wesbos.com)
- **Pygments CSS Adaptation:** [Josh McArthur](https://github.com/joshmcarthur)

## License

MIT (see [LICENSE](./LICENSE) for details)
