Hypothesis: The genes that were found to have roles in cancer treatment with wilfram A can be seen as changed within normal, non-cancer, cells.
Essentually want to retest the run they did in the original data set. In addtion I want to see if I can figure out some of the genes that were found to be up/downregulated and see thir "normal" uses within the genome. 

Original Data: https://www.ncbi.nlm.nih.gov/bioproject/565770
More from the original data: https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSM4080848
The infomraiton is very recent (Sept. 2019) so no paper out yet, however their pipline and methods are. 
Paper for OG data: There is no paper for this study. There are a total of 6 runs within this study. Unknown if all should be done or if just to focus on one?

Primary literature that will help me in proving my hyothesis that withaferin A could be used in cancer treatment by modifying gene expression.
1. Withaferin A Induces Cell Death Selectively in Androgen-Independent Prostate Cancer Cells but Not in Normal Fibroblast Cells
2. Par-4-Dependent Apoptosis by the Dietary Compound Withaferin A in Prostate Cancer Cells
3. Withaferin A-Induced Apoptosis in Human Breast Cancer Cells Is Mediated by Reactive Oxygen Species
4. Withaferin-A Inhibits Colon Cancer Cell Growth by Blocking STAT3 Transcriptional Activity
5. Withaferin A Associated Differential Regulation of Inflammatory Cytokines
6. Regiospecific Synthesis of Ring A Fused Withaferin A Isoxazoline Analogues: Induction of Premature Senescence by W-2b in Proliferating Cancer Cells
7. A Novel Combination of Withaferin A and Sulforaphane Inhibits Epigenetic Machinery, Cellular Viability and Induces Apoptosis of Breast Cancer Cells
8. Withaferin A suppresses the growth of myelodysplasia and leukemia cell lines by inhibiting cell cycle progression
9. Molecular targets and mechanisms of cancer prevention and treatment by withaferin a, a naturally occurring steroidal lactone.
10. Withaferin A induces apoptosis through the generation of thiol oxidation in human head and neck cancer cells.


Background information:
Withaferin-A is a steroidal lactone that has been traditionally used as ayurvedic medication. While having roles in this type of medicine 
withaferin-A could play a role in various types of cancers by inducing apoptosis. In general this lactone upregulates and downregulates
a total of over 12,000 genes. Looking at these genes it becomes ideal to see what these up/downregulated genes normally do and to see if
the lacton is able to aid in overall cancer treatment. 

Pipeline:
Take Raw Data provided -> run QA/QC -> Use cutadapt to get rid of unwanted base pairs -> Do differential gene expression analysis compared to healthy cells -> Generate a write up and show some interesting gene expression differences.
