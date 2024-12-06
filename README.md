# Human MDH2
# Uniprot ID: P40926
# Variation: phosphorylation of S309


## Description

# Serine 309 of human MDH2 has previously been identified as a post-transitionally modified site. The only study of this site has been a serine changing to a phenylalanine through acetylation, which caused a missense mutation (4). This caused an aromatic ring to be on the side chain, which cause the side chain to be hydrophobic (4). In this experiment, Serine 309 was changed to Aspartic acid 309 through phosphorylation. It is common for serine to be phosphorylated and this process is reversible (2). This process causes the site to become more stable due to a hydrophobic, non-polar molecule becoming a hydrophilic, polar molecule (2). There are no functional studies of this site in human metabolism. However, there is evidence of Serine at this site causing melanoma (1). This site is located on a loop between an alpha helix and a beta sheet. This site is not located near any active nor binding sites. In the modified and unmodified site all had hydrogen bonding with GLU 313 and GLU 312. The variant did not have any bonding to any nearby amino acids nor ions. The variant Serine 309 modified to Phenylalanine 309 through acetylation has no known disease (5). This protein is typically located within the mitochondria as it is responsible for contributing to the citric acid cycle (3).

1. image of the unmodified site
![alt text](images/MDH2.original.309.png)

2. image of modification site
![alt text](images/MDH2.PTM.309.png)


## Effect of the sequence variant and PTM on MDH dynamics

Serine 309 changed to Aspartic acid 309 through phosphorylation. This caused the amino acid to change from a polar unchanged to an amino acid with a negatively charged side change amino acid. Due to the side chain becoming charged, it is expected for different bonding to occurring where the negative charge is on the side change. Observing the modified protein, there was no changes in bonding for the amino acid at 309. This amino acid is not involved in any active sites, so the active sites remained normal. There was no observable substrate binding differences as all of the ligands; LMR, NAI, OAA, and MLT; do not bind with the amino acid at 309 in the variant, unmodified, and modified protein site. Due to no significant changes to the structure of this protein, this modification is likely not to affect the overall metabolic processes of this protein. However, the negative charge may cause this amino acid to interact more with positively charged ions and molecules to become a neutral charge. This amino acid is likely to bond with hydrogen atoms in order to change the negative charge to a neutral charge. This may cause a change in free energy (ΔG)  because the electrons involved to cause a hydrogen to bond to the negatively charge side chain will change the overall amount of work this system can perform. Due to more stability occurring as a result of the phosphorylation, the ΔG decreases and leads to a more spontaneous reaction. The stability also causes the entropy (ΔS) and enthalpy (ΔH) to decrease because there is less disorder in the system and less energy required to create products. 

1. Image of aligned PDB files (no solvent)
![alt text](images/align.png)

2. Image of the site with the aligned PDB files (no solvent)
![alt text](images/modification.site.png)

3. Annotated RMSF plot showing differences between the simulations
![alt text](images/rmsf_plot.png)

4. Annotated plots of pKa for the key amino acids
![alt text](imagespka.active.site.png)

5. If needed, show ligand bound images and how modification affects substrate binding

After simulation, the dynamics as described by the root mean square fluctuation (RMSF) value were compared. In the plot, there are differences between the unmodified (red) and modified (blue) around amino acids 15 and 350. These sites are loops bordering the active site. The modified one showed higher RMSF scores overall compared to the unmodified one. The higher the RMSF score, the higher the flexibility of these atoms at a specific location. The modification to the MDH2 protein allowed for the protein to become more flexible at the binding sites, which can cause the structure to become less defined. A lower RMSF value indicates more rigidity, which the unmodified protein exhibits. There was no observable changes to the structure in Mol* after modification. There was no changes in binding to any of the active sites nor the binding sites. The protein did not change structure overall due to this modification, but had slight functional changes to the protein. Overall the modification did greatly affect the pKa values of the modified site (309), as the modified pKa value was significantly higher than the unmodified pKa. Overall, there was slight changes to the active site pKa, but the unmodified protein had the highest overall pKa values compared to the modified values. 


## Comparison of the mimic and the authentic PTM

The RMSD (root mean square deviation) of phosphorylation of MDH2 309D and acetylation of MDH2 309F was 1.38 Å. The closer the RMSD value is to 0, the more identical the two structures are. However, this RMSD value is above 1, which indicates these structures are not identical. This is only useful in determining identity and not any other features to compare the two structures. The overall structures are similar with no major differences in structure or position. However, the binding is different at the 309 position in the mimic and the modified protein. The mimic protein has phenylalanine at this position, while the modified protein has aspartic acid at this position. A change from serine to phenylalanine caused the amino acid located at the 309 position to not bond with the other amino acids as it should in the normal MDH2 protein. However, in the modified protein where serene was changed to aspartic acid, there was no changed in the bonding compared to the original MDH2 protein. This mimic is not a good indication of the PTM (post-transitional modification) because the process to change this amino acid was different and the mimic amino acid is in a completely different classification than the one used in this PTM. 

include images as needed
![alt text](images/Mimic.png)


### Colab notebook links

Provide file names of completed colab notebooks
![alt text](data/colab_1/Copy_of_MD_simulation_Step1.ipynb)
![alt text](data/colab_1/humanmdh2/Another_copy_of_MD_simulation_Step1.ipynb)
![alt text](data/colab_2/humanmdh2/mdanalysis_colab_Step2.ipynb)
![alt text](data/colab_2/humanmdh2s309d/Copy_of_mdanalysis_colab_Step2.ipynb)


## Authors

Addison Rowland

## 12/05/2024

## License

Shield: [![CC BY-NC 4.0][cc-by-nc-shield]][cc-by-nc]

This work is licensed under a
[Creative Commons Attribution-NonCommercial 4.0 International License][cc-by-nc].

[![CC BY-NC 4.0][cc-by-nc-image]][cc-by-nc]

[cc-by-nc]: https://creativecommons.org/licenses/by-nc/4.0/
[cc-by-nc-image]: https://licensebuttons.net/l/by-nc/4.0/88x31.png
[cc-by-nc-shield]: https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg


## References

* Citation1 ![DOI](DOI Hive lab. https://hivelab.biochemistry.gwu.edu/biomuta/proteinview/P40926 (accessed 2024-12-06).)

* Citation2 ![DOI](DOI Zhong, Q.; Xiao, X.; Qiu, Y.; Xu, Z.; Chen, C.; Chong, B.; Zhao, X.; Hai, S.; Li, S.; An, Z.; Dai, L. Protein Posttranslational Modifications in Health and Diseases: Functions, Regulatory Mechanisms, and Therapeutic Implications. MedComm 2023, 4 (3), e261. https://doi.org/10.1002/mco2.261.)

* Citation3 ![DOI](DOI Mullinax, T. R.; Mock, J. N.; McEvily, A. J.; Harrison, J. H. Regulation of Mitochondrial Malate Dehydrogenase. Evidence for an Allosteric Citrate-Binding Site. J Biol Chem 1982, 257 (22), 13233–13239.)

* Citation4 ![DOI](DOI Uniprot. https://www.uniprot.org/uniprotkb/P40926/variant-viewer (accessed 2024-12-06).)

* Citation5 ![DOI](DOI EMBL-EBI ProtVar - Contextualising human missense variation. https://www.ebi.ac.uk/ProtVar/query (accessed 2024-12-06).)
