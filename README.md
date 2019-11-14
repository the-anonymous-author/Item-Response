# Item-Response-Citizen-Science
Data from the case study presented in the paper "Bayesian item response models for crowdsourced ecological data"

Variables:
-	LocationX and LocationY: X and Y coordinates of the site.
- DateTime: classification time stamp.
-	UserID: unique user identifier.
-	SiteID: site identification code.
- Species: classification value. 
-	True_Species: true species obtained from the gold standard dataset or via consensus voting.
-	Correct: outcome of the classification (1 = correct, 0 = otherwise).
- set: Data was split into 10 shards using stratified sampling. 

See Swanson et al. (2015) for more details.


## References:

Swanson, A., M. Kosmala, C. Lintott, R. Simpson, A. Smith, and C. Packer (2015).
Snapshot Serengeti, high-frequency annotated camera trap images of 40 mammalian species in an African savanna. Scientific data 2, 150026.
