# CAR-T Cell Therapy For Autoimmune Diseases

[1. Overview](#Overview)<br />
[2. Steps](#Steps)<br />
[3. Antigens](#Antigens)<br />
[4. Dr. Lung-Ji Chang Paper Breakdown](#Dr-Lung-Ji-Chang-Paper-Breakdown)


### Overview

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


### Steps

- Summary Papers
    - https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4909095/
    - https://pubmed.ncbi.nlm.nih.gov/28652918/
    - https://www.cell.com/cancer-cell/fulltext/S1535-6108(20)30366-4

1. Isolate T cells from blood.
    - https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3153890/
2. Genetically engineer T cells to express chimeric antigen receptor (CAR).
3. Proliferate CAR T cells ex vivo.
4. Infuse back into patient. 


### Antigen Targets

1. CD19
2. CD20
3. CD22
4. CD30 (TNFRSF8) 
5. CD33
6. CD123 (IL3R)
7. CD135 (FLT3)
8. BCMA


### Dr. Lung-Ji Chang Paper Breakdown

**2015 - Blood <br /> First-in-man CD123-specific chimeric antigen receptor-modified T cells for the treatment of refractory acute myeloid leukemia** <br /> [Link](https://ashpublications.org/blood/article/126/23/3778/93119/First-in-Man-CD123-Specific-Chimeric-Antigen)

- Study type: Clinical case report
- CAR construct: 4SCAR123
    - Anti-CD123 ScFv-CD28-CD137-CD27-CD3ζ-2A-iCasp9
    - Costimulatory molecules: CD28, CD137, and CD27
    - iCasp9 suicide gene
        - Giving Rimiducid (AP1903) rapidly induces CAR-T apoptosis
    - 2A is a peptide to allow CAR construct and iCasp9 to be expressed separately
- Cancer: Acute myeloid leukemia (AML) - 1 patient - 47-year old male - post allogeneic HSCT
- Lymphodepletion: cyclophosphamide 250mg/kg/day for 3 days (if 50kg - 37.5g total)
- CAR-T count: 1.8 x 106/kg (if 50kg - 9.0 x 107)
- Adverse events: Severe CRS on day 4, given Tocilizumab (anti-IL6) and controlled
- Outcome: Achieved partial remission after 20 days


**2019 - Frontiers in Oncology <br /> CD19 and CD70 dual-target chimeric antigen receptor T-cell therapy for the treatment of relapsed and refractory primary central nervous system diffuse large B-Cell Lymphoma** <br /> [Link](https://www.frontiersin.org/articles/10.3389/fonc.2019.01350/full)

- Study type: Clinical case report
- Dual CAR construct: 4SCAR19 and 4SCAR70
    - Anti-CD19/CD70 ScFv-CD28-CD27-CD3ζ-2A-iCasp9
- Cancer: Primary central nervous system diffuse large B cell lymphoma (PCNS-DLBCL) - 1 patient - 67-year old male - post 2-relapses
    - Concern for this patient due to central nervous system lymphoma and the potential for CART-related encephalopathy syndrome (neurotoxicity) - PCNSL patients are almost always excluded from receiving CAR-T therapy
    - Worth noting the patient achieved remission before CAR-T with 6 rituximab cycles, ibrutinib, and high-dose methotrexate altogether
- Lymphodepletion: cyclophosphamide 300mg/m2/d and fludarabine 30mg/m2/d (~1.5-2g and ~150-200mg total for 50kg person)
- CAR-T count: 1.0 x 108 anti-CD19 CAR-T cells and 8.2 x 107 anti-CD70 CAR-T cells total 
    - Both given on day 0 
    - Expansion of 4SCAR19 and 4SCAR70 was ~2.28% and ~0.48% respectively of PBMCs
- Adverse events: No CRS or neurotoxicity, only slight hematological toxicity
- Outcome: complete remission at 17 month follow up
- Both CAR-T cell types were detectable 321 days after infusion


**2018 - Oral Oncology <br /> CD70 as a target for chimeric antigen receptor T cells in head and neck squamous cell carcinoma** <br /> [Link](https://www.sciencedirect.com/science/article/abs/pii/S1368837518300344)

- Study type: Preclinical (in vitro)
- CAR construct: 4SCAR70
    - Anti-CD70 scFv-CD27-41BB-CD3ζ
- Cancer: Head and neck squamous cell carcinoma (HNSCC)
- First, the authors screened for CAR-T targets of HNSCC using expression data from the Cancer Genome Atlas (TCGA) and CD70 was selected for further analysis because of the availability of a CD70-binding CAR construct used in other studies
    - CD70 was overexpressed in HNSCC five times more compared to controls
- They found that CD70 was overexpressed in tumor tissues vs controls and posed a viable CAR-T target for HNSCC
- The authors used T cells from 3 donors to create anti-CD70 CAR-T cells and showed they were able to kill cell lines that overexpressed CD70 at different effector:target ratios
- Lastly, they concluded that since some TCGA data did not show differences in CD70 expression between cancer and controls, anti-CD70 CAR-T therapy is not suitable for every HNSCC case


**2020 - Frontiers in Immunology <br /> Phase I Trial of Fourth-Generation Anti-CD19 Chimeric Antigen Receptor T Cells Against Relapsed or Refractory B Cell Non-Hodgkin Lymphomas** <br /> [Link](https://www.frontiersin.org/articles/10.3389/fimmu.2020.564099/full)

- Study type: Phase I trial single-arm with <ins>**no comparator**</ins>
- CAR construct: 4SCAR19
    - Anti-CD19 scFv-CD28-CD27-CD3ζ-2A-iCasp9
- Cancer: refractory/relapsed B-cell non-Hodgkin’s lymphoma
- Patient characteristics:
    - n=21 - 13 male | 8 female
    - Ages 31 to 77
    - Stage II (n=1), stage III (n=5), stage 4 (n=15)
- Lymphodepletion: cyclophosphamide 900mg/m2 once and fludarabine 25mg/m2/d for 3d (~1.5-2g and ~125-150mg total for 50kg person)
- CAR-T count: median of 8.9 x 105/kg (if 50kg - 4.45 x 107)
    - 1:1 ratio of CD4+ and CD8+ T cells
    - CAR-T persistence correlated with patient response
    - CAR-T expansion DID NOT correlate with patient response
- Adverse events: 3 cases of CRS, 1 case of CRES
    - CRS was grade 1 in all 3 patients and resolved in 2-10 days
        - Interestingly these 3 patients did not respond to the treatment
    - CRES was grade 3 on day 33 - cognitive impairment, aphonia, unresponsiveness, mild irritability, and headache
        - Resolved after dexamethasone and saline
        - Lymphoma progressed 29 days after partial response to the CAR-T
- Outcome: 43% complete remission and 24% with partial response
    - First documented remission was 58 days post-infusion with some taking months
    - 5 patients remained in remission 5-20 months post-infusion
    - 7 patients relapsed or progressed without antigen escape
    - 7 patients died of relapse or disease progression by the study cutoff time (22 months)
