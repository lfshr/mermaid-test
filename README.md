```mermaid
sequenceDiagram
    participant Customer
    participant Website
    participant API

    Customer->>+Website: Navigates
    Note right of Customer: /weather

    Website->>+API: Requests Weather
    Note right of Website: /api/weather
    API->>-Website: Returns Weather

    Website->>-Customer: Displays Weather
```
