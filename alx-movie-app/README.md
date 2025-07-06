<<<<<<< HEAD
This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/pages/api-reference/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `pages/index.tsx`. The page auto-updates as you edit the file.

[API routes](https://nextjs.org/docs/pages/building-your-application/routing/api-routes) can be accessed on [http://localhost:3000/api/hello](http://localhost:3000/api/hello). This endpoint can be edited in `pages/api/hello.ts`.

The `pages/api` directory is mapped to `/api/*`. Files in this directory are treated as [API routes](https://nextjs.org/docs/pages/building-your-application/routing/api-routes) instead of React pages.

This project uses [`next/font`](https://nextjs.org/docs/pages/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn-pages-router) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/pages/building-your-application/deploying) for more details.
=======
# CineSeek - Movie Discovery Application

## Project Overview

CineSeek is a modern movie discovery application built with **Next.js**, **TypeScript**, and **Tailwind CSS**. It allows users to browse and search for movies using the MoviesDatabase API. The application features dynamic filtering by year and genre, a clean and responsive layout, reusable components, and server-side data fetching using Next.js API routes.

---

## API Overview

The MoviesDatabase API is a RESTful API offering access to detailed movie data. It allows developers to retrieve lists of movies, filter results by genre and year, access individual movie details, and implement pagination for efficient data browsing.

### Key Features:
- Search movie titles
- Filter by genre and year
- Fetch detailed movie information
- Supports pagination

---

## API Version

**v1**

---

## Available Endpoints

| Endpoint            | Description                                           |
|---------------------|-------------------------------------------------------|
| `/titles`           | Fetch a list of movies with optional filters         |
| `/titles/:id`       | Get detailed info for a specific movie               |
| `/genres`           | List all available movie genres                      |
| `/years`            | List available release years for filtering           |

---

## Request and Response Format

### Example Request:

### Example Response:
```json
{
  "results": [
    {
      "id": "tt123456",
      "title": "Movie Title",
      "year": 2023,
      "genres": ["Action", "Adventure"]
    }
  ],
  "page": 1,
  "total_pages": 10
}
>>>>>>> 5b0635181fa80f45891bf641881743ff5f2d57b7
