# Department Notice Board - Client

React + TypeScript frontend built with Vite.

## Run
```bash
npm install
npm run dev
```
Open `http://localhost:5173`. The Vite dev server forwards `/api` requests to the Express server on `http://localhost:5000`, so start the server first.

## Scripts
| Command | Description |
|---|---|
| `npm run dev` | Start the development server |
| `npm run build` | Type-check and build for production |
| `npm run lint` | Run oxlint |
| `npm run preview` | Preview the production build |

## Structure
- `src/App.tsx` - notice form, notice list and API calls
- `src/components/NoticeCard.tsx` - reusable component that displays one notice
- `src/assets/` - images
- `public/` - static files
