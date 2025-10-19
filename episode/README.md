# Task 3 – Paginated Episodes

**Query:** Fetches episodes from the Rick and Morty API using pagination.

## Example Query
```graphql
query GetPaginatedEpisodes($page: Int!) {
  episodes(page: $page) {
    info {
      count
      pages
      next
      prev
    }
    results {
      id
      name
      air_date
      episode
    }
  }
}
```

## Example Outputs
- `episodes-page-1-output.json` → Page 1 (first 2 episodes)
- `episodes-page-2-output.json` → Page 2 (next 2 episodes)

Use this as a reference for building and testing pagination queries.
