# CAR-T Cell Therapy For Autoimmune Diseases

[1. Overview](#Overview)<br />
[2. Steps](#Steps)<br />
[3. Antigens](#Antigens)<br />
[4. Clinical Papers for Autoimmune Diseases](#Clinical-Papers-for-Autoimmune-Diseases)<br />

[DIY](DIY/)

## Overview

Chimeric antigen receptor T cell (CAR-T) therapy is a novel treatment for cancer, and more recently, autoimmunity. T cells of the adaptive immune system are engineered to give them the ability to target a particular antigen (a protein) of the body. The word “chimeric” is used since the engineered receptor has both antigen-binding and T cell activating functions. CAR-T therapy is generally a 6-step process: leukapheresis, T cell isolation, CAR gene transduction, CAR-T cell expansion, lymphodepletion, and infusion. 

<p align="center">
    <img src="docs/car-t-overview.jpg" />
</p>

Leukapheresis is the process of separating white blood cells (WBCs) from the blood of a patient. After this, T cells are isolated from the WBCs usually by CD3 magnetic beads. CD3 is a protein expressed on the surface of T cells and these beads are able to bind to CD3 allowing for the separation using a magnet.

<p align="center">
    <img src="docs/cd3-magnetic-beads.jpg" />
</p>

The CAR construct is introduced into the isolated T cells by transfecting them with a retrovirus, typically a lentiviral vector. This viral vector contains the gene which encodes for the chimeric antigen receptor that the T cells utilize to recognize and attack their target. The vector is able to incorporate the gene into the genome of the T cell, which allows for expression of the CAR protein. When the CAR protein is made inside the T cell, it is then naturally brought to the surface of the cell so that it can interact with its target antigen.

The CAR protein itself needs to have at least 5 main components: the single-chain variable fragment (scFv), the hinge region, the transmembrane domain, a costimulatory domain, and the intracellular signaling domain. The scFv is the part of the protein that recognizes and binds to the specific antigen. The hinge region provides flexibility to the CAR protein, allowing it to move and bind to the antigen more efficiently. The transmembrane domain anchors the CAR protein to the surface of the T cell membrane. The co-stimulatory domain helps the T cell become activated when the scFv binds to its antigen, and there are several types, including CD28, 4-1BB, CD137, CD127, and OX40. This can impact the potency and durability of the CAR-T. There can also be multiple costimulatory domains as part of the CAR construct. Finally, the intracellular signaling domain, almost always CD3ζ, initiates the signaling cascade that makes the T cell ultimately activate and either kill its target or release cytokines. Over time, several generations of CAR constructs have been developed.

<p align="center">
    <img src="docs/car-constructs.jpg" />
</p>

The transfected T cells containing the CAR gene are then expanded ex vivo. This is typically done by stimulating the CD3 and CD28 domains on the T cell, causing them to activate and proliferate while also exposing them to growth-promoting cytokines. These cytokines include IL-2, IL-7, and IL-15. 

Once enough T cells are expanded, they are infused back into the patient so that they can recognize and target the cells, typically B cells, for death. The CAR-T cells will bind to the cell and, either directly kill the cell via cytotoxic effects (like granzyme B), or release cytokines, recruiting other components of the patient’s immune system to effectively destroy them. This leads to the desired outcome of either a reduction in cancer or mitigation of autoimmune diseases, improving the patient's condition and quality of life.


## Steps

- Summary Papers
    - https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4909095/
    - https://pubmed.ncbi.nlm.nih.gov/28652918/
    - https://www.cell.com/cancer-cell/fulltext/S1535-6108(20)30366-4

1. Leukapheresis - Separate white blood cells from blood of patient.
2. T cell isolation - Isolate T cells from WBCs using CD3 magnetic beads.
3. CAR gene transduction - Transfect T cells with retrovirus containing CAR gene.
4. CAR-T cell expansion - Stimulate T cells to proliferate and expand.
5. Lymphodepletion - Administer chemotherapy to deplete lymphocytes.
6. Infusion - Infuse CAR-T cells back into patient.


## Antigen Targets

B cell antigens:
- CD10
- CD19
- CD20
- CD22
- CD23
- CD30
- CD37
- CD52
- CD70
- CD79b
- CD123
- CD138
- ROR1 (Receptor tyrosine kinase-like orphan receptor 1)
- Light chain kappa/lambda

Plasma cell antigens:
- CD38
- CD56
- CD138
- CD229
- BCMA (B-cell maturation antigen)
- CS1
- FcRH5
- GPRC5D

T cell antigens:
- CD1a
- CD5
- CD7
- CD30
- TRBC1 (T-cell receptor beta constant 1)

Myeloid cell antigens:
- CD33
- CD38
- CD44
- CD70
- CD96
- CD117 (KIT)
- CD123
- CD135 (FLT3)
- Lewis Y antigen
- NKG2D ligands
- CLL-1 (C-type lectin-like molecule-1)
- TIM-3 (T-cell immunoglobulin and mucin-domain containing-3)
- PR1/HLA-A2 (Proteinase 3 or PR1 antigen)


## Clinical Papers for Autoimmune Diseases

**2022 - Nature Medicine <br /> Anti-CD19 CAR T cell therapy for refractory systemic lupus erythematosus** <br /> [Link](https://www.nature.com/articles/s41591-022-02017-5)

- Study type: Clinical case series
- CAR construct: CAR19
    - Anti-CD19 ScFv-4-1BB-CD3ζ
- Disease: Systemic lupus erythematosus (SLE)
    - Previous treatments: Glucocorticoids, Hydroxychloroquine, Mycophenolate mofetil, Azathioprine, Cyclophosphamide, Rituximab, Belimumab, Tacrolimus, Methotrexate, Leflunomide
- Number of patients: 5
    - 4 female | 1 male
    - Ages 18-23
    - Stage III/IV lupus nephritis
    - Disease duration: 1-9 years
- Lymphodepletion: cyclophosphamide (1000mg/m2/d) on day -3 and fludarabine (30mg/m2/d) on days -5, -4, and -3
- CAR-T cell count: 1x10<sup>6</sup>/kg
    - Peak expansion: 11.48% to 59.12% of CD3+ T cells
- Adverse events: 3 patients had grade 1 CRS (fever) which was resolved with metamizole (3 patients) and tocilizumab (1 patient)
- Outcome: complete drug-free remission in all 5 patients, no recurrence after 12 months

---

**2023 - The Lancet <br /> CD19-targeted CAR T cells in refractory antisynthetase syndrome** <br /> [Link](https://www.nature.com/articles/s41591-021-01387-0)

- Study type: Clinical case report
- CAR construct: CAR19
    - Anti-CD19 ScFv-4-1BB-CD3ζ
- Disease: Antisynthetase syndrome - 41-year old male
    - Previous treatments: Rituximab x3, IVIg, Tacrolimus, Cyclophosphamide
- Lymphodepletion: cyclophosphamide (1000mg/m<sup>2</sup>/d) on day -3 and fludarabine (30mg/m<sup>2</sup>/d) on days -5, -4, and -3
- CAR-T cell count: 1x10<sup>6</sup>/kg
    - Peak expansion: 3.5% of CD3+ T cells
- Adverse events: grade 1 CRS (fever) which was resolved with paracetamol and tocilizumab
- Outcome: complete remission including resolution of myositis, interstitial lung disease, creatine kinase, and anti-Jo-1 antibodies
    - No follow-up for this patient reported

---

**2023 - Annals of the Rheumatic Disease <br />Treatment of a patient with severe systemic sclerosis (SSc) using CD19-targeted CAR T cells** <br /> [Link](https://ard.bmj.com/content/early/2023/05/04/ard-2023-223952)

- Study type: Clinical case report
- CAR construct: CAR19
    - Anti-CD19 ScFv-4-1BB-CD3ζ
- Disease: Systemic sclerosis - 60-year old male
    - Previous treatments: Methotrexate and mycofenolate mofetil
- Lymphodepletion: cyclophosphamide (500mg/m<sup>2</sup>/d) on day -3 and fludarabine (12.5mg/m<sup>2</sup>/d) on days -5, -4, and -3
- CAR-T cell count: 1x10<sup>6</sup>/kg
    - Peak expansion: 66.4% of CD3+ T cells
- Adverse events: grade 1 CRS (fever) which resolved after 24 hours
- Outcome: pulmonary and cardiac functions remained stable, arthritis significantly improved, skin fibrosis improved, Raynaud's phenomenon improved
    - No follow-up for this patient reported

---

**2023 - Annals of the Rheumatic Disease <br /> POS1134 NOVEL APPROACH TO TREAT SYSTEMIC LUPUS ERYTHEMATOSUS, BY TARGETING THE “ROOT CAUSE”, B CELLS AND PLASMA CELLS, USING BCMA-CD19 COMPOUND CAR** <br /> [Link](https://ard.bmj.com/content/82/Suppl_1/895.1)

- Study type: Clinical case series
- CAR construct:
    - Unknown, but CD19/BCMA bivalent CAR-T (T cells have both CAR constructs)
- Disease: Systemic lupus erythematosus (SLE)
- Number of patients: 12
    - 10 female | 2 male
    - Ages 20-58
- Lymphodepletion: unknown
- CAR-T cell count: 1.5-3.0x10<sup>6</sup>/kg
- Adverse events: no CRS above grade 1
- Outcome: all 12 patients achieved complete drug-free remission with no recurrence. Longest follow-up is 3 years
