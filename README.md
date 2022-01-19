# Find Relations Between Entites and Graph

To understand the relationship with the extracted entities from a corpus is a challange in the *natural language processing* world. To understand how to find the relationship you can read this notebook to get the idea. In this notebook we use the [spaCy](https://spacy.io/) and [networkx](https://networkx.org/) packages to identify and plot the relationship between the entities. 

To find the relationships we must go through some steps. The steps are:
* find the sentences and chop them 
* find the tokenized words
* find their roles in the sentences
* finally find relations. 

### Required Softwares:
* [spaCy](https://spacy.io/) 
* [networkx](https://networkx.org/)
* [matplotlib](https://matplotlib.org/) 
