# Six Cities

A rental listings web app built with React and TypeScript. Users can browse apartment offers in six cities, see them on an interactive map, read and post reviews, and save favorites.

## Features

- Offer list filtered by city, with sorting by price and rating
- Interactive map (Leaflet) with markers that highlight the selected offer
- Offer page with photos, details, reviews and nearby places
- User authentication; signed-in users can post reviews and add offers to favorites
- Favorites page grouped by city

## Tech stack

- **React 18** with **TypeScript**
- **Redux Toolkit** for state management, async thunks for API calls
- **React Router** for routing, including private routes
- **Axios** for working with the REST API
- **Leaflet** for the map
- **Vitest** and **React Testing Library** for tests
- **Vite** for building, **ESLint** for code quality

## Getting started

```bash
npm install
npm start
```

Other commands:

```bash
npm run build   # production build
npm test        # run tests
npm run lint    # check code style
```

## About

Built as the final project of the HTML Academy course "React. Development of complex client applications".
