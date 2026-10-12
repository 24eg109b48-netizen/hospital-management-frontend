# Hospital Management Frontend

React and Vite frontend for the hospital management demo.

## Local development

```sh
npm ci
npm run dev
```

## Vercel

Set the project root to this repository root. Use `npm run build` and output directory `dist`. After the backend is deployed, set `VITE_API_BASE_URL` to its public HTTPS origin without a trailing slash. The frontend appends `/api` to this value.

This is a student demo. Use synthetic records only; do not enter real patient information.