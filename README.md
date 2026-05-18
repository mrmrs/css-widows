# css-widows

Functional CSS for widows

## Filesize

| File | Size |
|------|------|
| `dist/widows.css` | 649 bytes |
| `dist/widows.min.css` | 419 bytes (144 Gzipped) |

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
| `.widow0` | `widows: 0;` |
| `.widow2` | `widows: 2;` |
| `.widow3` | `widows: 3;` |
| `.widowi` | `widows: inherit;` |
| `.widow0-s` | `widows: 0;` |
| `.widow2-s` | `widows: 2;` |
| `.widow3-s` | `widows: 3;` |
| `.widowi-s` | `widows: inherit;` |
| `.widow0-m` | `widows: 0;` |
| `.widow2-m` | `widows: 2;` |
| `.widow3-m` | `widows: 3;` |
| `.widowi-m` | `widows: inherit;` |
| `.widow0-l` | `widows: 0;` |
| `.widow2-l` | `widows: 2;` |
| `.widow3-l` | `widows: 3;` |
| `.widowi-l` | `widows: inherit;` |

### Responsive

Responsive variants are available for each class with the following suffixes:

| Suffix | Media Query              |
|--------|--------------------------|
| `-s`   | `min-width: 32em`        |
| `-m`   | `min-width: 48em`        |
| `-l`   | `min-width: 96em`        |

Example: `.widow0-m` applies the property at the medium breakpoint and above.

## Building

```sh
npm run build
```

Processes `src/widows.css` with [Lightning CSS](https://lightningcss.dev) and outputs to `dist/`.

- `dist/widows.css` — formatted
- `dist/widows.min.css` — minified

## License

MIT
