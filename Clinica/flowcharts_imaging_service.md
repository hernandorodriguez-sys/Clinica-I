graph TD
    A[START - Diagnostic Imaging Service <br> Clínica Reina Isabel S.A.S.] --> B[Physical Technical Inventory (ITF/EI) <br> Decree 4725/2005]
    B --> C[Equipment Life Records & INVIMA Verification <br> Risk classification (Res. 4816/2008) - Technical files]
    C --> D[Technological Obsolescence Evaluation <br> Normalization: T= (IT/46)x100 + C=(CZ/20)x100 + E=(EE/24)x100 <br> V = 0.45xT + 0.30xC + 0.25xE (MinSalud Methodology)]
    D --> E{V Index Score}
    E -->|V 90-100| F[IMMEDIATE <br> REPLACEMENT <br> 90-100 <br> Initiate RAE/EE Disposal (D3) <br> Acquire replacement <br> Immediately]
    E -->|V 40-89.99 <br> 2-1 YEAR| G[RENEWAL <br> Plan acquisition of <br> replacement (D4/DB) <br> Initiate preventive <br> maintenance <br> Monthly Follow-up]
    E -->|V 11-39.99 <br> 1 YEAR| H[EVALUATE IN <br> 1 YEAR <br> Active monitoring <br> Re-evaluate in <br> 12 months <br> Explore renewal <br> options]
    E -->|V 1.10-99 <br> NO EVALUATION REQUIRED| I[NO EVALUATION <br> REQUIRED <br> Continue in service <br> Standard preventive <br> maintenance per <br> manufacturer (D8)]
    F --> J[Update Institutional ITF & Technology Park Consolidation <br> Close cycle. Process fully replicable across all hospital departments]
    G --> J
    H --> J
    I --> J
    J --> K[CYCLE COMPLETE]
