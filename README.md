# patents-analysis

In this project, we are trying to analyze Technology diffusion using big data on Pyspark. 

In simple terms, we are trying to analyze how companies/organizations depend on each other using patents dataset and their records of citations.

The module consists of the following:

1. General analysis of dataset, like top 10 cited companies, top 10 patents producing companies.
2. Graph analysis - Pagerank, Strongly connected components.
3. Text analysis of patents abstract - LDA model
4. Machine learning model to predict whether company A will cite company B's patent - BERT, Naive Bayes, Multilayer Perceptron, Random Forest.

Note - We are only analyzing top 100 companies for each year.

## What is Technology Diffusion?

* The way by which innovation is disseminated through certain channels over time among the organizations.
* Citations provide useful insight for technology dissemination processes, as patents are an important medium of invention.
* Relation between innovation happening in organizations and how they are inter-dependent.

## Dataset & Infrastructure

The dataset used is Google Patents dataset.

* Platform - GCP
* 1 master, 3 worker nodes
* standard-m1 instance
* 30 GB Memory
* 8 CPU cores
* Dataset size – 20 million rows (patents from 1976)
* Tables -
  * Patent
  * Patent citation
  * Assignee


## Predictions

* Naïve Bayes – Accuracy about 57%
* Multilayer Perceptron – Accuracy about 98%
* Decision Tree – Accuracy about 93%
* Random Forest – Accuracy about 95%


## Other Contributors

- Simron Waskar
- Sumit Dhundiyal
- Zexu Li 


## Conclusion

* Technology diffusion exists and has been increasing year by year.
* IBM & Samsung are the top most innovation hub in the last decade.
* We can predict the citation by an organization with certain accuracy for top 100 companies.
* The topics extracted from documents show that technology trends are highly reflected in the abstracts/titles.

## Thank you. :)

