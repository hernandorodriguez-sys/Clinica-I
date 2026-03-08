```mermaid
mindmap
flowchart TD

A[Start ITF Data Collection] --> B[Define Inventory Scope]

B --> C[Apply Inclusion Criteria]
C --> D[Verify INVIMA Health Registration]

D --> E{Registration Valid}

E -->|Yes| F[Risk Classification per Resolution 4816]

E -->|No| G[Flag for Regulatory Review]
G --> G1[Notify Authority]
G --> G2[Restrict Use]
G --> F

F --> H[Collect Technical Variables T C E]

H --> I[Calculate MinSalud Obsolescence Index]

I --> J[Complete ITF Field Form]

J --> K[ITF Record Completed]
