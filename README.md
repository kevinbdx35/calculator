# Calculator

A simple integer calculator built with vanilla HTML, CSS, and JavaScript. Supports addition, subtraction, multiplication, and division with a backspace key.

## Technologies

- HTML5
- CSS3
- JavaScript (vanilla)

## Getting Started

Open `index.html` directly in a browser — no build step required.

## Improvements

- Removed `X-UA-Compatible` meta tag
- Added `'use strict'`
- `innerText` → `textContent` (2 occurrences)
- Fixed bug: `previousOperator` initialized as `undefined` but compared with `=== null` → initialized to `null`
- `align-content: stretch` → `align-items: stretch` in `.calc-row` (`align-content` has no effect on single-line flex containers)

## License

MIT
