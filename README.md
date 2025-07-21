# fso-part0

## Exercise 4

```mermaid
    sequenceDiagram

        participant browser
        participant server

        browser->>server: GET https://studies.cs.helsinki.fi/exampleapp/notes
        activate server
        server-->>browser: HTML document 
```