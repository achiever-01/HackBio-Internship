**EPIDERMAL GROWTH FACTOR RECEPTOR**

**Authors (@slack):** Rukayat Jimoh (@Justjpearl), Ameenat Oloko (@Ameenat), Popoola Opeyemi Emmanuel (@Emmanuel), Adesina Damilola Victoria (@Victoria63) and Deborah Abolarinwa (@Achiever01).

**Introduction**

The Epidermal Growth Factor Receptor (EGFR) is a crucial tyrosine kinase receptor that regulates cell proliferation, differentiation, and survival. It is activated by binding ligands like epidermal growth factor (EGF), leading to receptor dimerization and autophosphorylation of tyrosine residues. Dysregulation of EGFR signalling is linked to various malignancies, making EGFR a key cancer treatment target.

**Important Features of EGFR Protein Structure**

Ø  **Active Site**: The active site of the EGFR is in the tyrosine kinase domain, which is responsible for phosphorylating tyrosine residues and activating downstream signalling (Hynes & Lane, 2005).

Ø  **Binding Sites**: EGFR contains multiple binding sites. The ATP-binding site, near Lys745, is key for ATP-dependent phosphorylation. Ligands such as EGF and Transforming Growth Factor-alpha (TGF-α), also bind to the extracellular domain, generating receptor dimerization and activation (Garrett *et al.,* 2002).

Ø  **Domains**: EGFR consists of three main domains:

a. **Extracellular domain:** ligand-binding region.

b. **Transmembrane domain**: anchors EGFR in the cell membrane.

c. **Intracellular tyrosine kinase domain**: responsible for phosphorylation.

**The C-terminal tail** (contains multiple tyrosine residues for phosphorylation) (Normanno *et al.,* 2006).

Ø **Mutations and Diseases**: Mutations in the tyrosine kinase domain, such as L858R (leucine to arginine), which leads to uncontrolled activation of EGFR are predominantly found in Non-Small Cell Lung Cancer (NSCLC) (Gazdar, 2009). In addition, deletions in exons 2-7 of the extracellular domain of EGFR have been implicated in glioblastoma (Gan *et al.,* 2013).

**Protein Modelling Techniques**

**A.**    **Homology Modeling (SWISS-MODEL)**

Homology Modeling uses crystal structures of identical proteins as templates to create a three-dimensional structure. It is efficient when a high-quality template with significant sequence identity is available. However, its accuracy depends on the template's quality and similarity, indicating that structural sections with low similarity or flexible loops may be poorly represented.

**B.**    **AlphaFold**      

AlphaFold is an AI tool for accurately modelling proteins, using evolutionary and structural information from the protein sequence to predict their three-dimensional structure. It outperforms homology modelling due to its ability to model proteins de novo, accurately represent regions and require experimental confirmation for certain predicted conformational states.

**Conformation Analysis: Crystal Structures Vs Modeling Techniques**

The models created by homology modelling and AlphaFold for EGFR were visualised using PyMOL and compared to the Protein Data Bank (PDB) crystal structures of EGFR \[**2EB2** (Yoshikawa *et al.,* 2012)\], \[**5WB7** (Freed *et al*., 2017)\] and \[**5UGB** (Planken *et al.,* 2017)\]. The alignment and RMSD (Root Mean Square Deviation) measurements were then conducted to assess the degree of correspondence between the predicted models and the experimentally determined structures.

      I.          **Homology Modeling**:

**a.**     **2EB2**

Ø    Aligning the homology model with 2EB2 resulted in an RMSD of 0.236Å (253 to 253 atoms).

Ø  The model showed a good alignment with the EGFR crystal structures, especially in the core regions of the protein.

Ø  The model majorly resembled the **apo** form, since it exhibited no structural characteristics indicative of ligand binding or activation.

  
![Homology Modeling 2EB2](https://github.com/user-attachments/assets/02297173-8093-4ec8-b82e-83a1b1863b37)
**Figure 1**: Alignment of the EGFR Homology model with 2EB2 (Crystal structure of mutated EGFR kinase domain (G719S)).

  

**b.**     **5WB7**

Ø  Aligning the homology model with 5WB7 resulted in an RMSD of 32.493Å (219 to 219 atoms).

Ø  The model mainly resembled the **agonist** form, exhibiting structural characteristics linked to ligand binding or activation.

![Homology Modeling 5WB7](https://github.com/user-attachments/assets/c68b666d-daeb-40a9-a41d-5e9dd54ccec9)
**Figure 2**: Alignment of the EGFR Homology model with 5WB7 (Crystal structure of the epidermal growth factor receptor extracellular region in complex with epiregulin).

**c.**     **5UGB**

Ø  Aligning the Homology model with 5UGB in an **antagonist** state resulted in an RMSD of 0.309 Å (248 to 248 atoms).

![Homology Modeling 5UGB](https://github.com/user-attachments/assets/eab4c71e-43ee-4a00-82cf-5630488681a9)
**Figure 3**: Alignment of the EGFR Homology model with 5UGB (Crystal structure of the EGFR kinase domain in complex with 4-(4-{\[2-{\[(3S)-1-acetylpyrrolidin-3-yl\] amino}-9-(propan-2-yl)-9H-purin-6-yl\] amino} phenyl)-1-methylpiperazin-1-ium).

      **II.**          **AlphaFold**

**a.**     **2EB2**

Ø  Aligning the AlphaFold model with 2EB2 resulted in an RMSD of 0.216 Å (239 to 239 atoms)

Ø  The AlphaFold model elucidated aspects of the protein's conformation that were less distinctly displayed in the homology model, including the right orientation of certain side chains.

Ø  The structure generated by AlphaFold exhibited characteristics of an **apo** conformation.

![AlphaFold model 2EB2](https://github.com/user-attachments/assets/a575513f-8917-4d5f-acf0-6e6f61ad0bd9)
**Figure 4**: Alignment of the EGFR AlphaFold model with 2EB2 (Crystal structure of mutated EGFR kinase domain (G719S)).

**b.**     **5WB7**

Ø  Aligning the AlphaFold model with 5WB7 resulted in an RMSD of 28.932 Å (298 to 298 atoms).

Ø  The structure generated by AlphaFold exhibited characteristics of an **agonist** conformation.

![AlphaFold model 5WB7](https://github.com/user-attachments/assets/1b7e5169-1e31-4210-92f6-61847429a141)
**Figure 5**: Alignment of the EGFR AlphaFold model with 5WB7 (Crystal structure of the epidermal growth factor receptor extracellular region in complex with epiregulin).

**c.**   **5UGB**

Ø  Aligning the AlphaFold model with 5UGB resulted in an RMSD of 0.275 (247 to 247 atoms).

Ø  The structure generated by AlphaFold exhibited characteristics of an **antagonist** conformation.

![AlphaFold model 5UGB](https://github.com/user-attachments/assets/0106b318-90db-4131-b23d-ef8d5d4b4b5e)
**Figure 6**: Alignment of the EGFR AlphaFold model with 5UGB (Crystal structure of the EGFR kinase domain in complex with 4-(4-{\[2-{\[(3S)-1-acetylpyrrolidin-3-yl\] amino}-9-(propan-2-yl)-9H-purin-6-yl\] amino} phenyl)-1-methylpiperazin-1-ium).

  

**Accuracy of Each Technique**

AlphaFold appears to be the more accurate and applicable method for modelling EGFR due to certain factors.

1.     The RMSD results showed AlphaFold predictions were more accurate than homology modelling in predicting the crystal structure, with a 1.0 Å RMSD indicating substantial structural concordance.

2.     AlphaFold predicted an agonist-bound conformation, useful for ligand interactions and therapeutic inhibitor development, while homology modelling produced a plausible apo form of EGFR.

3.     AlphaFold is a tool that operates independently of templates, making it useful for proteins lacking high-quality templates or detecting areas with little sequence conservation, such as loops or disordered regions. This is particularly advantageous for EGFR, which has flexible domains that play a role in its activation.

4.     AlphaFold's model predicts active protein conformations crucial for drug research on EGFR's activated state, as it produced a conformation resembling an agonist-bound state.

**Conclusion**

AlphaFold is the most effective method for modeling EGFR, as it predicts active conformations without a template, which is beneficial for proteins involved in dynamic processes like EGFR. Homology modelling is useful for refining AlphaFold predictions or when experimental evidence informs model enhancements, but AlphaFold's predictions are superior in accuracy and biological relevance for EGFR.

**References**

Gan, H. K., Cvrljevic, A. N., and Johns, T. G. (2013). The epidermal growth factor receptor variant III (EGFRvIII): where wild things are altered. *FEBS Journal*, 280(21), 5350-5370.

Garrett, T. P., McKern, N. M., Lou, M., Elleman, T. C., Adams, T. E., Lovrecz, G. O., ... and Ward, C. W. (2002). The crystal structure of a truncated epidermal growth factor receptor extracellular domain bound to transforming growth factor α. *Cell*, 110(6), 763-773.

Gazdar, A. F. (2009). Activating and resistance mutations of EGFR in non-small-cell lung cancer: role in clinical response to EGFR tyrosine kinase inhibitors. *Oncogene*, 28(1), S24-S31.

Freed, D. M., Bessman, N. J., Kiyatkin, A., Salazar-Cavazos, E., Byrne, P. O., Moore, J. O., ... and Lemmon, M. A. (2017). EGFR Ligands Differentially Stabilize Receptor Dimers to Specify Signaling Kinetics. *Cell*, 171(3), 683–695.e18.

Hynes, N. E., and Lane, H. A. (2005). ERBB receptors and cancer: the complexity of targeted inhibitors. *Nature Reviews Cancer*, 5(5), 341-354.

Normanno, N., De Luca, A., Bianco, C., Strizzi, L., Mancino, M., Maiello, M. R., ... and Salomon, D. S. (2006). Epidermal growth factor receptor (EGFR) signaling in cancer. *Gene*, 366(1), 2-16.

Planken, S., Behenna, D. C., Nair, S. K., Johnson, T. O., Nagata, A., Almaden, C., ... and Lafontaine, J. (2017). Discovery of N-((3R,4R)-4-Fluoro-1-(6-((3-methoxy-1-methyl-1H-pyrazol-4-yl) amino)-9-methyl-9H-purin-2-yl)pyrrolidine-3-yl)acrylamide (PF-06747775) through Structure-Based Drug Design: A High Affinity Irreversible Inhibitor Targeting Oncogenic EGFR Mutants with Selectivity over Wild-Type EGFR. *Journal of Medicinal Chemistry*, 60(7), 3002-3019.

Yoshikawa, S., Kukimoto-Niino, M., Parker, L., Handa, N., Terada, T., Fujimoto, T., ... and Yokoyama, S. (2012). Structural basis for the altered drug sensitivities of non-small cell lung cancer-associated mutants of human epidermal growth factor receptor. *Oncogene*, 32(1), 27-38.
