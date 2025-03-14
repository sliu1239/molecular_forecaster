# Pharmahacks 2025 #
# Challenge: Predict Kinase Selectivity Using Machine Learning

Below is a description of the files in this repository:
* all_seqs.pkl : A pickled version of all amino acid sequences for each kinase.
* global_embedings_max_length.npy : A numpy array of the global embeddings for each amino acid sequence obtained with ProteinBert. Note: local embeddings are not included in this repository but can be obtained from the same model
* global_embedings_map.pkl : A pickled version of the mapping between the kinases and their respective global embeddings
* Table-1.xlsx : a table containing additional information about each kinase
* Table-2_train.xlsx : a table containing selectivity scores and SMILES strings for the training set
* Table-3_train.xlsx: a table of Kd values for the training set
