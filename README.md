# PETs_colR_tox

Note: This repository contains raw datasets used to create figures and to perform statistical analysis.

ABSTRACT: Genes encoding lipid A modifying phosphoethanolamine (pEtN) transferases (PETs) are genetically diverse and can confer resistance to colistin and antimicrobial peptides. To better characterize PETs, we used an isogenic expression system to characterize three canonical mobile colistin resistance (mcr) alleles (mcr-1, -3, -9), one intrinsic pet (eptA), and two mcr-like genes (petB, petC). We found that mcr-1 and mcr-3 are phenotypically similar, conferring colistin resistance with low fitness costs. Mcr-9, which is phylogenetically related to mcr-3 and eptA, provides fitness advantages in the presence of sub-inhibitory concentrations of colistin, whereas mcr-9 and eptA significantly reduce fitness in media only. PET-B and PET-C were phenotypically distinct from bonafide PETs and did not confer colistin resistance in E. coli. Strikingly, we found that PETs site-selectively modify the 1 or 4’ phosphate of lipid A with 4’-phosphate modifications facilitated by MCR-1 and -3 associated with high levels of colistin resistance and low toxicity.

DESCRIPTION OF FILES:

"AUC_western_FLAG.csv" - Area under the curves for canonical FLAG-tagged PETs (from western blots), estimated total proteins for the same samples (from SDS page gels), and calculated protein level

"CFU_counts_canonical_PETs.csv" - Cell viability concentrations (CFU/mL) at different timepoints after induction with different L-arabinose concentrations for canonical PET variants (EptA, MCR-1, MCR-3, MCR-9) and the empty vector control ("EV")

"CFU_counts_novel_PETs.cvs" - Cell viability concentrations (CFU/mL) at different timepoints after induction with different L-arabinose concentration for novel, mcr-like PET variants (PET-B, PET-C)

"CFU_counts_killing_assay.csv" - Cell viability concentrations (CFU/mL) after PET expressing strains were exposed to different concentrations of colistin (0, 1, 2, 4, 8 ug/mL) for 1 hour

"FitnessData_absence_colistin.csv" - Cell viability concentrations (CFU/mL) of PET expressing strains and competitior strains pre and post competition, fitness values, and fitness values adjusted by WT fitness values for competition assays performed in the absence of colistin

"FitnessData_presence_colistin.csv" - Cell viability concentrations (CFU/mL) of PET expressing strains and competitior strains pre and post competition, fitness values, and fitness values adjusted by WT fitness values for competition assays performed in the presence of colistin (1/4th of the PET expressing strains MIC
