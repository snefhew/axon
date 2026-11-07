# Axon Automatiseringen

Schoolproject: concept voor AI-chatbots op maat voor het mkb. [Demo](https://snefhew.github.io/axon/)

## Stack

- Statische HTML en JavaScript, GitHub Pages
- Claude API (Haiku) via een Cloudflare Worker als proxy

## Opzet

```
browser -> Cloudflare Worker (API-sleutel) -> Claude API
```

Vier chatbots, één per branche, elk met een eigen systeemprompt. De demo is verlopen: de koppeling is verwijderd en de chat reageert niet meer.
