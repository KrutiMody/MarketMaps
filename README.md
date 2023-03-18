# MarketMaps
Implement YAKE, KeyBERT, Tf-idf for keyword extraction and Latent Dirichlet Allocation(LDA) for topic modelling on 10K+ company description to cluster them together and form Market Maps (Capstone Project at UW)
### Kruti_Pitchbook

 * Tf_Kmeans_LDA.ipynb is the jupyter notebook highlighting data cleaning, exploration which removes entries where company description is "NA". It includes implementation of Tf-idf, Kmeans clustering and LDA (in-progress).
 * data folder contains company names, description and existing keywords provided by PitchBook
 * doc_cluster is the model saved with the help of pickle to reduce execution time - it can be reused until more data is added for processing
 
