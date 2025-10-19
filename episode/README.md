# Task 2: Fetch Specific Episode by ID

This directory contains GraphQL queries that retrieve details about specific episodes from the Rick and Morty GraphQL API.

## Endpoint
https://rickandmortyapi.com/graphql

## Objective
Fetch an episode by its ID using the `episode(id: ID!)` field and return the following fields:
- id
- name
- air_date
- episode

## Example Query
```graphql
query {
  episode(id: 1) {
    id
    name
    air_date
    episode
  }
}
```

## Example Output
```json
{
  "data": {
    "episode": {
      "id": "1",
      "name": "Pilot",
      "air_date": "December 2, 2013",
      "episode": "S01E01"
    }
  }
}
```

Each file below corresponds to a specific episode (IDs 1–4).
