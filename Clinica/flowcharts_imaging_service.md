flowchart TD

A[Start Diagnostic Imaging Service] --> B[Physical Technical Inventory ITF]
B --> C[Equipment Life Records and INVIMA Verification]
C --> D[Technological Obsolescence Evaluation]

D --> E{V Index Score}

E -->|90-100| F[Immediate Replacement]
F --> F1[Initiate RAEE Disposal]
F1 --> F2[Acquire Replacement Immediately]

E -->|40-89.99| G[Technology Renewal < 1 Year]
G --> G1[Plan Replacement Acquisition]
G --> G2[Intensify Preventive Maintenance]
G --> G3[Monthly Follow-up]

E -->|11-39.99| H[Evaluate in 1 Year]
H --> H1[Active Monitoring]
H --> H2[Reevaluate in 12 Months]

E -->|1-10.99| I[No Evaluation Required]
I --> I1[Continue in Service]
I --> I2[Standard Preventive Maintenance]

F2 --> J[Update Institutional ITF]
G3 --> J
H2 --> J
I2 --> J

J --> K[Technology Park Consolidation]
K --> L[Cycle Complete]
