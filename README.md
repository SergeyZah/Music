Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

# SkyMusic

The SkyMusic app is Next.js for listening and searching for music

## Features

- User login and registration
- Collections of tracks
- Filtering tracks by artist, genre, and year of release
- Adding tracks you like to your playlist
- Search for the desired track

## Stack

- Next.js 16
- React 19
- TypeScript
- Redux Toolkit
- CSS Modules
- jest

## Requirements

- Node.js 20+
- npm 10+

## Installation

```bash
npm install
```

## Run Locally

Development mode:

```bash
npm run dev
```

Production build:

```bash
npm run build
npm run start
```

Lint:

```bash
npm run lint
```

Tests:

```bash
npm test
```

## Environment

The app uses `BASE_URL` for API requests.

Example:

```env
BASE_URL=https://wedev-api.sky.pro
```
