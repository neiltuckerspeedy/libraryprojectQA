#flowchart
```mermaid
flowchart LR
  A[Original Files] --> B[Bronze lake] --> C[Silver file.Clean IBSN number format date format do not pass personal info names etc only memberid remove nulls remove duplications] --> D[Gold Aggregated Reporting tables by location by book length of borrow ]
B --> E[Failed to clean - alert sent to user]
```
