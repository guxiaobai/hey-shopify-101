# 资源加载

```
{{ "bootstrap.min.css" | asset_url | stylesheet_tag }}
<script src="{{  'bootstrap.bundle.min.js' | asset_url}}" defer="defer"></script>
```

## Ref

* [`asset_url`](https://shopify.dev/docs/api/liquid/filters/asset_url)
* [`stylesheet_tag`](https://shopify.dev/docs/api/liquid/filters/stylesheet_tag)
* [`script_tag`](https://shopify.dev/docs/api/liquid/filters/script_tag)