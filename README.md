# database-for-lipolytic-enzymes
A search method based on profile HMMs was developed to identify and annotate putative lipolytic genes in metagenomes.
In order to target homologous sequences, profile HMMs were built from multiple sequence alignments.

1. For lipolytic enzymes share a conserved α/β-hydrolase fold, protein sequences in corresponding families were downloaded from ESTHER database.
   Multiple sequence alignments were performed using the following three algorithms and default settings: ClustalW, Clustal Omega, and Muscle. 
   Moreover, profile HMMs supplied in the ESTHER database were downloaded.
   Thereafter, we designated the four profile HMM databases with respect to the corresponding alignment algorithm (clustalw-pHMMs, omega-pHMMs and muscle-pHMMs) or source (ESTHER-pHMMs).
   
2. For families II, VIII and patatin-like-proteins, profile HMMs were retrieved directly from Pfam database, and designated as pfam-pHMMs.


