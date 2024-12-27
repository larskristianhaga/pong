# Pong

A simple API that responds with a pong message in different formats.

## Example usages

Basic usage:

```Bash
curl -L 'https://pongapi.fly.dev'
```

Advanced usage with custom type response:

```Bash
curl -L 'https://pongapi.fly.dev' -H 'Accept: application/json'
```

## Supported response types

- `text/plain`, default
- `application/json`
- `application/xml`