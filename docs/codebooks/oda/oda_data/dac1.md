---
tags:
    - oda
    - dac1
---


# DAC1
The DAC1 presents ODA data as reported by donor countries, with each row containing a contribution aggregated by aid type.

DAC1 helps answer questions like:

How much ODA do DAC countries provide?
What is the share of bilateral and multilateral ODA for country X?
How much ODA does Country X provide to UN agencies?
In addition to broad aid types such as bilateral and multilateral, DAC1 breaks down contributions into smaller categories that are useful for more in-depth analysis. The following diagram gives a rough overview of how DAC1 breaks down contributions:


```bash
├── Official Development Assistance
    ├── Bilateral ODA
    │   ├── Project-type interventions 
    │   │   ├── Investment projects 
    │   │   └── ...
    │   ├── Experts and other technical assistance 
    │   ├── Scholarships and student costs in donor countries
    │   └── ...
    └── Multilateral ODA (Contributions to:)
        ├── UN Agencies
        ├── EU Institutions
        ├── IDA
        ├── Other World Bank
        └── ...
```