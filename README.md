# elr-scss-lists

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![npm](https://img.shields.io/npm/dm/elr-scss-lists.svg?style=flat)](https://npmjs.com/package/elr-scss-lists)

a library of sass mixins

## Installation

Download node at [nodejs.org](http://nodejs.org) and install it, if you haven't already.

```sh
npm install elr-scss-lists --save
yarn add elr-scss-lists
```

```scss
.unstyled-list {
  @include elr-unstyled-list;
}
```

```scss
.border-list {
  @include elr-border-list(
    $config: (
      border-color: #333,
    )
  );
}
```

```scss
.inline-list {
  @include elr-inline-list;
}
```

```scss
.bullet-list {
  @include elr-bullet-list(
    $config: (
      icon: "\2705",
      icon-font-size: 70%,
    )
  );
}
```

```scss
.icon-list {
  @include elr-icon-list(
    $config: (
      icon-color: #1976d2,
      icon-font-size: 70%,
    )
  );
}
```

## License

SEE LICENSE IN LICENSE.md
