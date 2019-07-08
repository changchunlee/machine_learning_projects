# Antimicrobial Peptide (AMP) Classifier

Antimicrobial peptide (AMP) recognition using deep learning

Peptide are short chains of amino acid linked by peptide bonds. Among them, antimicrobial peptides (AMP) are part of the innate immune response found among all classes of life, and have been demonstrated to kill Gram negative and Gram positive bacteria, enveloped viruses, fungi and even transformed or cancerous cells.

One of the research interest in our lab is to understand the mechanism of the peptide and lipid membrane interaction. We are especially interested in AMP peptide and lipid membrane interaction, and have studied many of them to understand the mechanism how AMP peptides kill bacteria by forming different types of pores on bacterias's membrane (Toroidal vs. Barrel Stave Model).

There are two goals we want to achieve using DNN:
(1) To recognize if a given peptide is a AMP peptide or not
(2) To classfy what kind of pores (Toroidal or Barrel Stave) will be formed on bacteria membrane for a given AMP peptide. 

Our first goal is achieved by building a 15 DNN model to reconigze AMP peptides with accuracy >91% on unseen test dataset. The next step of is work is to further classify the pore-forming mechanism (Toroidal vs. Barrel Stave Model) if a given peptide is recoginized as AMP.

<br>
