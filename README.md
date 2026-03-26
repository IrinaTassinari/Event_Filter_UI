# Event Filter UI

A small frontend project built with HTML, CSS, and vanilla JavaScript for displaying and filtering a list of events.

## Overview

The app renders a set of event cards and lets users filter them by:
- event type (`online` or `offline`)
- maximum distance
- category

Filtering happens instantly in the browser without any backend or external framework.

## Features

- Event list rendered from a local JavaScript data store
- Filtering by type, distance, and category
- Responsive card layout
- Empty-state message when no events match the selected filters
- Lazy-loaded event images

## Tech Stack

- HTML5
- CSS3
- Vanilla JavaScript (ES6)

## Project Structure

```text
sort_JS/
|-- index.html
|-- style.css
|-- script.js
|-- README.md
```

## How It Works

- `index.html` contains the filter controls and the container for event cards.
- `script.js` stores the sample events and implements the `EventFilter` class.
- `EventFilter` listens for changes in the select fields, applies active filters, and re-renders the cards.
- `style.css` defines the layout, card styles, badges, and responsive behavior.

## Run Locally

1. Clone or download the project.
2. Open `index.html` in your browser.

You can also run it with a simple local server, for example:

```bash
npx serve
```


## Notes

This project uses hardcoded demo data and is intended as a simple practice/example project for working with DOM rendering and client-side filtering.
