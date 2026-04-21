# To-Be Process

```mermaid
flowchart LR
    A[Requester submits vendor form] --> B[System checks required fields]
    B --> C[Vendor admin reviews documents]
    C --> D{Documents complete?}
    D -- No --> E[Request missing information]
    E --> C
    D -- Yes --> F[Operations manager approval]
    F --> G[Finance review]
    G --> H{Approved?}
    H -- No --> I[Reject with reason]
    H -- Yes --> J[Vendor record created]
    J --> K[Status and audit history saved]
```

## How the Improved System Helps

The improved flow gives each request a clear stage, owner, due date, and document status. Instead of asking around, operations and finance can see where the request is stuck and what needs to happen next.
