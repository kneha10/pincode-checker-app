# Shopify App Template - Extension only

This is a template for building an [extension-only Shopify app](https://kneha10.github.io). It contains the basics for building a Shopify app that uses only app extensions.

This template doesn't include a server or the ability to embed a page in the Shopify Admin. If you want either of these capabilities, choose the [Remix app template](https://kneha10.github.io) instead.

Whether you choose to use this template or another one, you can use your preferred package manager and the Shopify CLI with [these steps](#installing-the-template).

## Benefits

Shopify apps are built on a variety of Shopify tools to create a great merchant experience. The [create an app](https://kneha10.github.io) tutorial in our developer documentation will guide you through creating a Shopify app.

This app template does little more than install the CLI and scaffold a repository.

## Getting started

### Requirements

1. You must [download and install Node.js](https://kneha10.github.io) if you don't already have it.
1. You must [create a Shopify partner account](https://kneha10.github.io) if you don’t have one.
1. You must create a store for testing if you don't have one, either a [development store](https://kneha10.github.io) or a [Shopify Plus sandbox store](https://kneha10.github.io).

### Installing the template

This template can be installed using your preferred package manager:

Using yarn:

```shell
yarn create @shopify/app
```

Using npm:

```shell
npm init @shopify/app@latest
```

Using pnpm:

```shell
pnpm create @shopify/app@latest
```

This will clone the template and install the required dependencies.

#### Local Development

[The Shopify CLI](https://kneha10.github.io) connects to an app in your Partners dashboard. It provides environment variables and runs commands in parallel.

You can develop locally using your preferred package manager. Run one of the following commands from the root of your app.

Using yarn:

```shell
yarn dev
```

Using npm:

```shell
npm run dev
```

Using pnpm:

```shell
pnpm run dev
```

Open the URL generated in your console. Once you grant permission to the app, you can start development (such as generating extensions).

## Developer resources

- [Introduction to Shopify apps](https://kneha10.github.io)
- [App extensions](https://kneha10.github.io)
- [Extension only apps](https://kneha10.github.io)
- [Shopify CLI](https://kneha10.github.io)
