# css-widows

Functional CSS for widows

## Filesize

| File | Size |
|------|------|
| `dist/widows.css` | 1413 bytes |
| `dist/widows.min.css` | 967 bytes (221 Gzipped) |

## Install

```sh
npm install css-widows
```

## Usage

### Import

```css
@import "css-widows";
```

### CDN

```html
<link rel="stylesheet" href="https://unpkg.com/css-widows/dist/widows.min.css">
```

### Direct

```html
<link rel="stylesheet" href="path/to/css-widows/dist/widows.min.css">
```

## Classes

| Class   | Value                    |
|---------|--------------------------|
| `.widow1` | `widows: 2;` |
| `.widow2` | `widows: 3;` |
| `.widow3` | `widows: 4;` |
| `.widow-inherit` | `widows: inherit;` |
| `.widow-initial` | `widows: initial;` |
| `.widow-revert` | `widows: revert;` |
| `.widow-revert-layer` | `widows: revert-layer;` |
| `.widow-unset` | `widows: unset;` |
| `.widow1-s` | `widows: 2;` |
| `.widow2-s` | `widows: 3;` |
| `.widow3-s` | `widows: 4;` |
| `.widow-inherit-s` | `widows: inherit;` |
| `.widow-initial-s` | `widows: initial;` |
| `.widow-revert-s` | `widows: revert;` |
| `.widow-revert-layer-s` | `widows: revert-layer;` |
| `.widow-unset-s` | `widows: unset;` |
| `.widow1-m` | `widows: 2;` |
| `.widow2-m` | `widows: 3;` |
| `.widow3-m` | `widows: 4;` |
| `.widow-inherit-m` | `widows: inherit;` |
| `.widow-initial-m` | `widows: initial;` |
| `.widow-revert-m` | `widows: revert;` |
| `.widow-revert-layer-m` | `widows: revert-layer;` |
| `.widow-unset-m` | `widows: unset;` |
| `.widow1-l` | `widows: 2;` |
| `.widow2-l` | `widows: 3;` |
| `.widow3-l` | `widows: 4;` |
| `.widow-inherit-l` | `widows: inherit;` |
| `.widow-initial-l` | `widows: initial;` |
| `.widow-revert-l` | `widows: revert;` |
| `.widow-revert-layer-l` | `widows: revert-layer;` |
| `.widow-unset-l` | `widows: unset;` |

### Responsive

Responsive variants are available for each class with the following suffixes:

| Suffix | Media Query              |
|--------|--------------------------|
| `-s`   | `min-width: 32em`        |
| `-m`   | `min-width: 48em`        |
| `-l`   | `min-width: 96em`        |

Example: `.widow1-m` applies the property at the medium breakpoint and above.

## Building

```sh
npm run build
```

Processes `src/widows.css` with [Lightning CSS](https://lightningcss.dev) and outputs to `dist/`.

- `dist/widows.css` — formatted
- `dist/widows.min.css` — minified

## License

MIT
