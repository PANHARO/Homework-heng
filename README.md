# Der Lg Travel Website

A static travel website exercise with destination cards, a slideshow, and separate about and contact pages. Built with HTML, JavaScript, and Tailwind CSS.

## Preview

From the repository root, run:

```sh
python -m http.server 8000
```

Open [localhost:8000](http://localhost:8000). Use `python3` if that is your Python 3 command. The checked-in `src/output.css` can be served directly.

## Edit styles

With Node.js and npm installed:

```sh
npm ci
npm run dev
```

This watches `src/input.css` and rebuilds `src/output.css`; keep the preview server running separately. Images include local `Assets/trip.jpg` and external sources. Serve the repository as the web root so `/Assets/...` paths resolve correctly. Booking and contact pages are frontend demonstrations.
