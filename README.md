# Text Classification Project

## Data: 
The MITRE ATT&CK framework is a globally accessible knowledge base of adversary tactics and techniques based on real-world observations of cyber-attacks. The framework categorizes tactics and techniques used by adversaries in order to help organizations better understand and defend against cyber threats.

## Objective:
Develop a supervised machine learning algorithm that can learn the relationship between attack descriptions and the corresponding MITRE technique. 

## Methodology:
- Data checks
- Data Preprocessing
- Create features using TF-IDF vectorizer
- Train simple models and check accuracy
- Select model with good accuracy and tunne the model on different parameters using gridsearch.

## Final Result:
The final accuracy on test set is 73.33% on GBM model. However thers is no improvement on model tunning. 

## Next Step:
Tune models on more range of paramenets and also add some more fatcor like min_samples_split, min_samples_leaf, etc.
