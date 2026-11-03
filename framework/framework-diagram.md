---
config:
  theme: base
  themeVariables:
    background: "#edf1f5"
    primaryColor: "#CEE398"
    secondaryColor: "#F6F9FC"
---

## DIRECT competency framework diagram

```mermaid
flowchart TD
CD[Competency Domains]
C[Competencies]
Sk[Skills]
SL[Skill Level]
TLM[Tools / Languages / Methodologies]
LR[Learning Resources]
R[Roles]
Spec[Specialities]
CP[Career Profiles]
SP[Skill Profile]


CD -- group --> C
C -- contain --> S
Sk -- build --> C
Sk -- proficiency --> SL
TLM -- demonstrate --> Sk
LR -- help develop --> Sk
LR -- support learning of --> TLM
CP -- contains --> R
CP -- contains --> Spec
R -- refers to --> CD
Spec -- refers to --> Sk
SP -- contains --> Sk
SP -- contains SL
```
