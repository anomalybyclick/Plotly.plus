# PlotlyPlus 

A dataset for Visualization Recommendation Systems(VRS)

## Abstract
Visualization recommendation is a novel and challenging field of study, whose aim is to provide non-expert users with automatic tools for insight discovery from data. Advances in this research area are hindered by the absence of reliable datasets on which to train the recommender systems. To the best of our knowledge, Plotly is the only publicly available dataset, but as complained by many authors and discussed in this article, it contains many labeling errors, which greatly limits its usefulness. We release an improved version of the original dataset, named Plotly.plus, which we obtained through an automated procedure with minimal post-editing. In addition to a manual validation by a group of data science students, we demonstrate that when training two basic classifiers on Plotly.plus, systems’ performance improves more than twice as much as when the original dataset is used, thus proving that models are able to find more regularities in the data


## Repostitory description
In this [link](https://doi.org/10.6084/m9.figshare.20424924.v1) are provided all the data described in the paper. More in details:
- **Scatter_new** contains all the images for class 0(not insightful) and class 1(insightfull) of scatters labeled in Plotly.plus
- **Scatter** contains all the images for class 0(not insightful) and class 1(insightfull) of scatters from original Plotly corpus
- **Lines_new** contains all the images for class 0(not insightful) and class 1(insightfull) of lines labeled in Plotly.plus
- **Lines** contains all the images for class 0(not insightful) and class 1(insightfull) of lines from original Plotly corpus
- **augmented_dataset.pkl** is the dataframe of Plotly.plus with all the features extracted(centroid, class, confidence score, img and xycoordinate in tsne embeddings)

The clustering library is available at: [Clustimage](https://erdogant.github.io/clustimage/pages/html/index.html)


## Acknowledgements
This work is a result of the research project funded by MIUR under the grant of “Dipartimenti di eccellenza 2018-2022” of the Department of Computer Science of Sapienza University.

## License
Copyright © 2022 Luca Podo and Paola Velardi

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the “Software”), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
