# Getting markdown from GitHub API

`
query {
    repository(owner: "pyankoff", name: "markdown-app") {
      object(expression: "master:README.md") {
        ... on Blob {
          text
        }
      }
    }
  }
`
\n

## GraphQL and Apollo are 💯
![graphql+apollo](https://jslancer.com/wp-content/uploads/2017/08/GraphQL-Apollo.jpg)
