# 🧩 Task 1: Get a List of All Characters

## Objective
Write a GraphQL query using the **`characters(page: Int)`** field to fetch a paginated list of all characters from the Rick and Morty API.

## Instructions
For each page (1–4), the query should select the following fields:
- `id`
- `name`
- `status`
- `image`

### Example Query
```graphql
query {
  characters(page: 1) {
    results {
      id
      name
      status
      image
    }
  }
}
```

## Example Output
Each JSON file contains an example structure of the expected response.

### Files Included
- `characters-page-1.graphql`
- `characters-page-1-output.json`
- `characters-page-2.graphql`
- `characters-page-2-output.json`
- `characters-page-3.graphql`
- `characters-page-3-output.json`
- `characters-page-4.graphql`
- `characters-page-4-output.json`

### Endpoint
```
https://rickandmortyapi.com/graphql
```
