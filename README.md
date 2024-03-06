# Go Hello OpenAPI

A quick "Hello World" but for generating OpenAPI, using the Go web framework [Huma](https://huma.rocks/). 

## Introduction

This codebase is the combination of the two following guides:

1. [Huma > Your First API](https://huma.rocks/tutorial/your-first-api/)
2. [Bump.sh > Deploying docs from Huma](https://docs.bump.sh/guides/bump-sh-tutorials/huma/)

The goal is to show you how you can export OpenAPI from your Huma application, and deploy the OpenAPI as API Reference Documentation as [Bump.sh](https://bump.sh) hosted docs. 

## Usage

Clone the repository down to give it a try.

```
# Start the server
$ go run .

# Export the OpenAPI
$ go run . openapi > openapi.yaml
```

Preview how the API reference docs look [on Bump.sh](https://bump.sh/bump-examples/hub/code-samples/doc/go-hello-openapi).

## License

The contents of this repository are licensed under [CC BY-SA
  4.0](./LICENSE_CC-BY-SA-4.0).
