# css-hyphens

Functional CSS for hyphens

## Filesize

| File | Size |
|------|------|
| `dist/hyphens.css` | 621 bytes |
| `dist/hyphens.min.css` | 445 bytes (142 Gzipped) |

## Install

```sh
npm install css-hyphens
```

## Usage

### Import

```css
@import "css-hyphens";
```

### CDN

```html
<link rel="stylesheet" href="https://unpkg.com/css-hyphens/dist/hyphens.min.css">
```

### Direct

```html
<link rel="stylesheet" href="path/to/css-hyphens/dist/hyphens.min.css">
```

## Classes

| Class   | Value                    |
|---------|--------------------------|
| `.hyphen-none` | `hyphens: none;` |
| `.hyphen-manual` | `hyphens: manual;` |
| `.hyphen-auto` | `hyphens: auto;` |
| `.hyphen-none-s` | `hyphens: none;` |
| `.hyphen-manual-s` | `hyphens: manual;` |
| `.hyphen-auto-s` | `hyphens: auto;` |
| `.hyphen-none-m` | `hyphens: none;` |
| `.hyphen-manual-m` | `hyphens: manual;` |
| `.hyphen-auto-m` | `hyphens: auto;` |
| `.hyphen-none-l` | `hyphens: none;` |
| `.hyphen-manual-l` | `hyphens: manual;` |
| `.hyphen-auto-l` | `hyphens: auto;` |

### Responsive

Responsive variants are available for each class with the following suffixes:

| Suffix | Media Query              |
|--------|--------------------------|
| `-s`   | `min-width: 32em`        |
| `-m`   | `min-width: 48em`        |
| `-l`   | `min-width: 96em`        |

Example: `.hyphen-none-m` applies the property at the medium breakpoint and above.

## Building

```sh
npm run build
```

Processes `src/hyphens.css` with [Lightning CSS](https://lightningcss.dev) and outputs to `dist/`.

- `dist/hyphens.css` — formatted
- `dist/hyphens.min.css` — minified

## License

MIT
