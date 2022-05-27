# PlotlyPlus 

A dataset for Visualization Recommendation Systems(VRS)

## Abstract
Visualization recommendation is a novel and challenging field of study, whose aim is to provide non-expert users with automatic tools for insight discovery from data. Advances in this research area are hindered by the absence of reliable datasets on which to train the recommender systems. To the best of our knowledge, Plotly is the only publicly available dataset, but as complained by many authors and discussed in this article, it contains many labeling errors, which greatly limits its usefulness. We release an improved version of the original dataset, named Plotly.plus, which we obtained through an automated procedure with minimal post-editing. In addition to a manual validation by a group of data science students, we demonstrate that when training two basic classifiers on Plotly.plus, systems’ performance improves more than twice as much as when the original dataset is used, thus proving that models are able to find more regularities in the data


## Repostitory description
In this [link](https://drive.google.com/drive/folders/1Dgk6ql4USoqe_uKAhm8hXwXZbeE_HkkS?usp=sharing) are provided all the data described in the paper. More in details:
- *Scatter_new* contains all the images for class 0(not insightful) and class 1(insightfull) of scatters labeled in Plotly.plus
- *Scatter* contains all the images for class 0(not insightful) and class 1(insightfull) of scatters from original Plotly corpus
- *Lines_new* contains all the images for class 0(not insightful) and class 1(insightfull) of lines labeled in Plotly.plus
- *Lines* contains all the images for class 0(not insightful) and class 1(insightfull) of lines from original Plotly corpus
- *augmented_dataset.pkl* is the dataframe of Plotly.plus with all the features extracted(centroid, class, confidence score, img and xycoordinate in tsne embeddings)

The clustering library is avaible at: [Clustimage](https://erdogant.github.io/clustimage/pages/html/index.html)
