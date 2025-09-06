# Shopify CLI

## Installation

```bash
npm install -g @shopify/cli@latest
```



## Network proxy configuration

```bash
export SHOPIFY_HTTP_PROXY=http://127.0.0.1:7890
```


## Theme

```bash
shopify theme init
shopify theme dev --store {store-name}
shopify theme push --unpublished
```

```bash
shopify theme pull --store {store-name}
```

## Ref

* <https://shopify.dev/docs/api/shopify-cli>