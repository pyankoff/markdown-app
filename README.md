#Getting markdown from GitHub API

```graphql
query {
    repository(owner: "pyankoff", name: "markdown-app") {
      object(expression: "master:README.md") {
        ... on Blob {
          text
        }
      }
    }
  }
```

##GraphQL and Apollo are 💯
![graphql+apollo](https://jslancer.com/wp-content/uploads/2017/08/GraphQL-Apollo.jpg "image")

