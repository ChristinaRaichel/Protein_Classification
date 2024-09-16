# Protein_Classification

Protein sequences stored in the fasta file are embedded using pretrained protBert, and classified as Antibiotic Resistant(and variants) and Non Resistant categories using a Multi-output classification head. The input file contains 21 categories of labeled sequences, which are broadly classified under 2 main categories. 

Multi class classification is learned by minimizing vategorical cross entropy and evaluation metrics like precision, recall and accuracy are used to evaluate the model performance.

