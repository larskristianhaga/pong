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

Default response type is `text/plain`.

- `application/json`
- `application/xml`
- `text/plain`
- `text/html`
- `text/csv`
- `text/yaml`
- `text/toml`
- `text/vcard`
- `text/vcalendar`
- `text/ics`
- `text/x-sh`