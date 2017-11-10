A Model-Driven Methodology for Big Data Analytics-as-a-Service

Claudio A. Ardagna, Valerio Bellandi, Michele Bezzi, Paolo Ceravolo, Ernesto Damiani, Cedric Hebert

Abstract The Big Data revolution promises to build a data-driven ecosystem where better decisions are supported by enhanced
analytics and data management. However, major hurdles still need to be overcome in the road that leads to commodization and wide
adoption of Big Data Analytics (BDA). Big Data complexity is the first factor hampering the full potential of BDA. The opacity and variety of Big Data technologies and computations in fact make BDA a failure prone and resource-intensive process, which requires a
trial-and-error approach. This problem is even exacerbated by the fact that current solutions to Big Data application development take a bottom-up approach, where the last technology release drives application development. Selection of the best Big Data platform, as well as of the best pipeline to execute analytics, represents then a deal breaker. In this paper, we propose a return to roots by defining a Model Driven Engineering (MDE) methodology that supports automation of BDA based on model specification. Our approach lets customers declare requisites to be achieved by an abstract Big Data platform and smart engines deploy the Big Data pipeline carrying out the analytics on a specific instance of such platform. Driven by customers’ requisites, our methodology is based on an OWL-S ontology of Big Data services and on a compiler transforming OWL-S service compositions in workflows that can be directly executed on the selected platform. The proposal is experimentally evaluated in a real-world scenario focusing on threat detection system of SAP. 


Index Terms—Big Data, Model-Driven Architecture, OWL-S


This page contains a guide on how to download the experiments (results and configuration files) exposed in the paper "A Model-Driven Methodology for Big Data Analytics-as-a-Service"


Repository is organized in six main folders containing all building blocks and datasets at the basis of experimental evaluation and examples in the paper.

- Folder [DataSet](https://github.com/SESARLab/A-Model-Driven-Methodology/tree/master/Datasett) contains all datasets we have used for evaluation. 

- Folder [Declarative Model](https://github.com/SESARLab/A-Model-Driven-Methodology/tree/master/Declarative%20model) contains the  declarative model in JSON-LD described in section 3.

- Folder [OWL-S service composition](https://github.com/SESARLab/A-Model-Driven-Methodology/tree/master/OWL-S%20service%20composition) contains all OWL-S files .

- Folder [OWL-S service description](https://github.com/SESARLab/A-Model-Driven-Methodology/tree/master/OWL-S%20service%20description) contains all OWL-S files .

- Folder [Oozie workflow](https://github.com/SESARLab/A-Model-Driven-Methodology/tree/master/Oozie%20workflow) contains all XML files exposed in section.

- Folder [Results](https://github.com/SESARLab/A-Model-Driven-Methodology/tree/master/Results) contains all results files exposed in section .



