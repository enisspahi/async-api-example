# AsyncAPI Example

This repository contains an AsyncAPI specification.

The spec is converted into a static html page to be served on [github pages](https://enisspahi.github.io/async-api-example/).

## Below are some examples of publishing single page API Docs with multiple tools:

### Publishing API Docs as a single page API Doc using [AsynAPI Generator](https://www.asyncapi.com/tools/generator)

1. Ensure `asyncapi` CLI tool and `@asyncapi/html-template` template are installed. Instructions: https://www.asyncapi.com/tools/generator
2. Run cli to generate single page API Doc
   `asyncapi generate fromTemplate src/main/resources/async-api.yaml @asyncapi/html-template -o docs/`
3. Observe generated `docs/index.html` page

**[github-actions job](https://github.com/enisspahi/async-api-example/actions/workflows/api-docs-with-asyncapi-generator.yml)** can trigger the API Docs generation and publishes the generated docs to github pages.
