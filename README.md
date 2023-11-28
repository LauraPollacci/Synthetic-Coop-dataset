# Synthetic-Coop-dataset
Synthetic shopping retail consumption data generated with [Synthetic Data Vault (SDV)](https://docs.sdv.dev/sdv/) Python library Python library.

## Short description
Synthetic shopping retail consumption data was generated with SDV, i.e.,  Gaussian Copula Synthesizer, CTGAN Synthesizer, TVAE Synthesizer, and Copula GAN Synthesizer.  
The dataset provides monthly information on the spending of synthetic customers belonging to two classes (i.e., native Italians and foreigners residing in Italy). The data was generated starting from the UniCoop Tirreno dataset [1]. 

### Data
For each expense, together with the nationality of the synthetic customer, both general and specific shopping behaviors are included.
General features include the total and average indicators of quantities and capture the average frequency of the period within which a customer makes a purchase. 
Specific features capture the specific shopping behavior for each one of the various supermarket products. Note that, to avoid very sparse data, the products are grouped into categories representing goods of similar type, e.g., bread, pasta, tomatoes, milk, etc.

#### References
[1] Guidotti, R., Nanni, M., Giannotti, F., Pedreschi, D., Bertoli, S., Speciale, B., & Rapoport, H. (2021). Measuring immigrants adoption of natives shopping consumption with machine learning. In Machine Learning and Knowledge Discovery in Databases. Applied Data Science and Demo Track: European Conference, ECML PKDD 2020, Ghent, Belgium, September 14–18, 2020, Proceedings, Part V (pp. 369-385). Springer International Publishing.
