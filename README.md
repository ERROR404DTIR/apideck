# APIDeck

A responsive, local-first API workspace inspired by modern API clients. Build HTTP requests, inspect responses, organize collections and keep request history in your browser.

**Live:** https://error404dtir.github.io/apideck/

## Features
- GET, POST, PUT, PATCH, DELETE, HEAD and OPTIONS
- Query parameters and custom headers
- JSON, text and form URL-encoded request bodies
- Bearer token, Basic Auth and API Key authorization
- Response body, headers, status, duration and size
- Pretty/raw response display, copy and download
- Collections, saved requests and request history
- Environment variables with {{variableName}} interpolation
- Dark/light themes and responsive desktop/mobile layouts
- Local browser storage; no application backend

## Run locally
Open index.html, or run `python3 -m http.server 8080` and visit http://localhost:8080.

## Important notes
- Requests are sent directly from the browser with Fetch. The target API must allow browser requests through CORS. APIDeck does not proxy or bypass CORS.
- Browser security rules may limit which headers can be set or read.
- Data is stored in this browser profile. Do not save credentials on shared devices.

## License
MIT
