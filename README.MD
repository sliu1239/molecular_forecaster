# PharmaHacks 2025  
## Challenge: Predict Kinase Selectivity Using Machine Learning  

### Repository Contents  

- **`all_seqs.pkl`**  
  A pickled version of all amino acid sequences for each kinase.  

- **`global_embedings_max_length.npy`**  
  A NumPy array of the global embeddings for each amino acid sequence obtained with ProteinBert.  
  **Note:** Local embeddings are not included in this repository but can be obtained from the same model.  

- **`global_embedings_map.pkl`**  
  A pickled version of the mapping between kinases and their respective global embeddings.  

- **`Table-1.xlsx`**  
  A table containing additional information about each kinase.  

- **`Table-2_train.xlsx`**  
  A table containing selectivity scores and SMILES strings for the training set.  

- **`Table-3_train.xlsx`**  
  A table of Kd values for the training set.  

### Important Notes  

- You are **not required** to use `all_seqs.pkl`,`lobal_embedings_max_length.npy` and `global_embedings_map.pkl`; they are provided for **your convenience**.  
- The **test set will be released on Sunday at 11 AM**.  
