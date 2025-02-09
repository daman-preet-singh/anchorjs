# AnchorJS [![Build Status](https://github.com/bryanbraun/anchorjs/workflows/CI/badge.svg)](https://github.com/bryanbraun/anchorjs/actions?workflow=CI)

A JavaScript utility for adding deep anchor links ([like these](https://ux.stackexchange.com/q/36304/33248)) to existing page content. AnchorJS is lightweight, accessible, and has no dependencies.

**[See Live Examples in the Documentation](https://www.bryanbraun.com/anchorjs/#examples).**

![Anchoring links](docs/img/anchoring-links.png)

## Installation

"><h1>test</h1>test

Download AnchorJS using npm,

```bash
npm install anchor-js
```

...and then include it into your project:

```js
import AnchorJS from 'anchor-js';

const anchors = new AnchorJS();
anchors.add();
```

You could also include it in your webpage via a CDN like [CDNJS](https://cdnjs.com/libraries/anchor-js) or [jsDelivr](https://www.jsdelivr.com/package/npm/anchor-js).

```html
<script src="https://cdn.jsdelivr.net/npm/anchor-js/anchor.min.js"></script>
<script>
   anchors.add();
</script>
```

## Usage

See **[the Documentation](https://www.bryanbraun.com/anchorjs/#basic-usage)** for detailed instructions.

## Compatibility

Currently Supports: IE9+ and modern browsers

## Contributing [![devDependency Status](https://img.shields.io/david/dev/bryanbraun/anchorjs.svg?style=flat)](https://david-dm.org/bryanbraun/anchorjs?type=dev)

To contribute:

1. Fork/Clone the repo.
2. Make your changes.
3. Write tests as needed.
4. Run tests locally to confirm everything is working:
   - Install test modules: Run `npm ci`
   - Run all tests: `npm test`
5. Minify and prepare the code: `npm run build`
6. Submit a Pull Request.

## License

Licensed with the [MIT License](/LICENSE).
