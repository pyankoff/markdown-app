# Getting markdown from GitHub API

![graphql+apollo](https://jslancer.com/wp-content/uploads/2017/08/GraphQL-Apollo.jpg "image"){'\n'}

GraphQL and Apollo are 💯

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
