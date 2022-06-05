# Project2
SP22 BIMM143 Bioinformatics Laboratory 

**Introduction:** Antivenoms are antibodies purified from animals injected with small doses of venom, and are used to treat bites from venomous snakes. When the small dose of venom is injected into the host animal, they produce antibodies where the variable region is specific for binding to the antigen (toxin) and the constant region is specific for determining the function of the antibody. IgG (Immunoglobulin G) is a type of antibody that can bind and neutralize toxins, and is the type of antibody that is purified from host animals. Thus, I would like to use a local pairwise sequence alignment to find the similarities of the immunoglobulin heavy constant gamma 1 (IGHG1) in humans, mouse, cattle, horse and monkey. The IGHG1 gene sequence that is the most similar to the human IGHG1 sequence and the least similar will be further analyzed to look at protein structure. This will hope to gain insight on which host animal IgG1 is most similar to the human IgG1, which could be the better host animal to use to produce antivenom antibodies.

**Scientific question:** How can the production of antivenom antibodies be optimized in terms of the IgG antibodies that is generated in the host animal?

**Hypothesis:** If the immunoglobulin heavy constant gamma 1 (IGHG1) in mice, cattle, horse or monkey is the most similar to the IGHG1 of human IgG, and the protein structure of the human IgG1 and host animal IgG1 is similar, then that host animal would produce IgG neutralizing antibody that would function in the most similar way as endogenous human IgG, which could give researchers an insight on which animal could produce the most effective antivenom antibodies to treat snakebites in humans.

**Files needed to run the code:**

For local pairwise sequence alignment: nucleotide sequences of the IgG1 gene downloaded from NCBI
1) human_IgG1.txt - Homo sapiens (human): https://www.ncbi.nlm.nih.gov/gene/3500
2) mouse_IgG1.txt - Mus musculus (house mouse): https://www.ncbi.nlm.nih.gov/gene/16017
3) cattle_IgG1.txt - Bos taurus (cattle): https://www.ncbi.nlm.nih.gov/gene/281850
4) horse_IgG1.txt - Equus caballus (horse): https://www.ncbi.nlm.nih.gov/gene/?term=Equus+caballus+IGHC1
5) monkey_IgG1.txt - Macaca mulatta (Rhesus monkey): https://www.ncbi.nlm.nih.gov/gene/708891

For structural bioinformatics: proteins structures were downloaded from RSCB PDB
1) 1jpt.pdb - Homo sapiens (human): PDB ID = 1JPT https://www.rcsb.org/structure/1JPT
2) 5dqj.pdb - Mus musculus (house mouse): PDB ID = 5DQJ https://www.rcsb.org/structure/5DQJ
3) 4d9q.pdb - Macaca mulatta (Rhesus monkey): PDB ID = 4D9Q https://www.rcsb.org/structure/4D9Q

The protein structure movie was made using the PyMOL software.

The notebook for running all of the code was written in Python. 
