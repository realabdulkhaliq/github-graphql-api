# GitHub GraphQL API
How to Use GitHub GraphQL API

The GraphQL Explorer is the recommended tool for communicating with the GraphQL API. The GraphQL Explorer is a "graphical interactive in-browser GraphQL IDE". The Explorer is an instance of [GraphiQL App](https://github.com/skevy/graphiql-app).

After downloading the GraphiQL app, follow these instructions to configure it:

1. Get a properly configured OAuth token.
2. Open GraphiQL.
3. In the upper-right corner of GraphiQL, select Edit HTTP Headers.
4. In the Key field, enter 'Authorization'. In the Value field, enter Bearer <token>, where <token> is your generated OAuth token.
5. Select the checkmark to the right of the token to save it.
6. To return to the editor, select outside of the Edit HTTP Headers modal.
7. In the GraphQL Endpoint field, enter https://api.github.com/graphql.
8. In the Method drop-down, select **Post**.


## CodeQL Action Release
https://github.com/github/codeql-action/releases

[CodeQL Documentation GitHub](https://github.com/github/codeql/blob/main/docs/query-metadata-style-guide.md)

[CodeQL Documentation Detailed](https://codeql.github.com/docs/ql-language-reference/about-the-ql-language/)
