# go.siketyan.dev
Shorten URLs forwarding via ZEIT

## Routing definition
```js
{
  "routes": [
    {
      "src": "/shorten/path",
      "status": 302,
      "headers": {
        "Location": "https://really.long-long.url/"
      }
    },
    // Another routes...
  ]
}
```
