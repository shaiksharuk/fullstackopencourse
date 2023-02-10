```mermaid

sequenceDiagram
    participant browser
    participant server

    Note right of browser: The browser sends notes to server

    browser->>server: Post https://studies.cs.helsinki.fi/exampleapp/spa
    activate server
   
    deactivate server

    

    Note right of browser: The browser re-draws the notes


```
