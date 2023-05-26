```mermaid
sequenceDiagram
    participant browser
    participant server

    browser->>server: POST https://studies.cs.helsinki.fi/example/new_note_spa
    activate server
    server-->>browser: {message: "note created"}
    deactivate server
```
