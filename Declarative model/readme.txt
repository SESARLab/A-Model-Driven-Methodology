Declarative model

configuration.json presents the declarative model used in the experimental evaluation. It mainly defines three requirements: 
i) log dataset must address data minimization privacy requirement by hashing field UserID using SHA-256, while guaranteeing full analytics quality; 
ii) data must be analyzed by using a clustering algorithm; in this example, we specifically selected k-means with km in [1,. . .,10];
iii) data visualization must support visual inspection of data by expert users, to select valid alerts; the configuration in our example points to scatter-plots selection at procedural level.

A web application allowing the user to specify declarative requirements can be accessed at http://alphaplus.dti.unimi.it/mytoreador
- username: TSC@ieee.org
- password: tr@ns@ctions