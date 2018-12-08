# Getting markdown from GitHub API

## GraphQL and Apollo are 💯
![graphql+apollo](https://jslancer.com/wp-content/uploads/2017/08/GraphQL-Apollo.jpg)


```
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
