# Neuera - marketing site

Responsive one-page marketing site built with React + Vite. Each block is its own
component, so sections can be reordered or removed without touching the rest.

## Sections (in render order)

`Header`, `TopSection`, `InfiniteScroll`, `Benefits`, `Points`, `Projects`,
`Slogan`, `Comments`, `PreFooter`, `Footer`.

## Run

```bash
git clone https://github.com/ErfanBagheri404/neuera-react.git
cd neuera-react
```

```bash
npm install
npm run dev
```

`npm run build` emits a static bundle to `dist/`.

## Stack

React 18 - Vite - CSS modules/plain CSS per component.

## Structure

| path | role |
|---|---|
| `src/App.jsx` | section order |
| `src/components/` | one file per section |
| `src/assets/` | images and logos |
