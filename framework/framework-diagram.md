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
SL[Skill Levels]
TLM[Tools / Languages / Methodologies]
LR[Learning Resources]
R[Roles]
Spec[Specialities]
CP[Career Profiles]
SP[Skill Profiles]

CD -- group --> C
C -- contain --> Sk
Sk -- build --> C
TLM -- demonstrate knowledge of --> Sk
LR -- help development of --> Sk
LR -- support learning --> TLM
CP -- contain --> R
CP -- contain --> Spec
R -- refer to --> CD
Spec -- refer to --> Sk

SL --> J{ }
Sk --> J
J -- build --> SP

```
