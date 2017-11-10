Set of OWL-S service description files

Declarative model specification is used to select the set of compatible services that can be composed to build the Big Data 
campaign. According to the three requirements described in the paper, our MBDAaaS methodology selects all SHA-256 services, 
different instances of service k-means of Apache Spark, and all visualization services available on our platform, including 
the ones provided by Zeppelin, for scatter-plot visualization. The specification of declarative constraints can further 
affect the list of selected services. 

The definition of constraint km of k-means affects service selection results. When km is not defined or is
defined as a range (Figure 2), the list of compatible services also includes optimization services such as elbow method and
silhouette score. This means that either the final user can select a value for km at procedural time or an optimization algorithm 
can be used to infer it.


  * DataCleaningService.owls and describe the services of data cleaning in the data preparation step
  * SparkKmean.owls models the K-Mean algorithm coded using the spark library	
  * KmeanElbow.owls model the Elbow method algorithm used to evaluate the best K value coded using the spark library
