# @nteract/octicons

This package contains a set of React icon components used within nteract applications (and your applications too!). These icons are based on the [GitHub Octicons icon set](https://octicons.github.com/).

## Installation

```
$ yarn add @nteract/octicons
```

```
$ npm install --save @nteract/octicons
```

## Usage

The example below shows how to use the icons in this package to render a save button.

```javascript
import { DownArrow } from "@nteract/octicons";

export default () => {
  return (
    <button>
      <DownArrow /> Save
    </button>
  );
};
```

## Support

If you experience an issue while using this package or have a feature request, please file an issue on the [issue board](https://github.com/nteract/octicons/issues).

## License

[BSD-3-Clause](https://choosealicense.com/licenses/bsd-3-clause/)
