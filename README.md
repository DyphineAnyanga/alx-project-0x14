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
