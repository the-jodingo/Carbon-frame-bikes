[![CI](https://github.com/the-jodingo/Carbon-frame-bikes/actions/workflows/ci.yml/badge.svg)](https://github.com/the-jodingo/Carbon-frame-bikes/actions/workflows/ci.yml)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![Netlify](https://img.shields.io/badge/Netlify-live-00C7B7?logo=netlify&logoColor=white)](https://dynamic-speculoos-5bfe02.netlify.app/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
# Velox Carbon — Bicycle Landing Page

A single-page product site for a fictional carbon-frame bicycle brand. Plain HTML and CSS.

## Table of contents

- [Requirements](#requirements)
- [Usage](#usage)
- [Deployment](#deployment)
- [Accessibility](#accessibility)
- [License](#license)

## Requirements

A modern web browser. No build step, no dependencies, no server required.

## Usage

```bash
git clone https://github.com/the-jodingo/Carbon-frame-bikes.git
cd Carbon-frame-bikes
python3 -m http.server 8000
```

Open <http://localhost:8000>. You can also open `index.html` directly.

## Deployment

Any static host works — Netlify, GitHub Pages, Cloudflare Pages, S3, or nginx.
The page is a single file with no build step, so you can drag the folder in.

## Accessibility

- semantic landmarks and a logical heading order
- all text meets WCAG AA contrast
- keyboard-navigable, with visible focus states
- responsive layout, usable from 320 px wide
- CI runs an axe-core scan and HTML validation on every push

## License

[MIT](LICENSE) © Joash Odingo
