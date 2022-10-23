# GNN_Notebook
GNN_Optimum_Metric_Analysis_Project
This project aims to adress a gap in machine learning+particle physics studies. 
Especially in node classification on multiple particle clusters in "jet" particle showers, distinct particles' paths may not be accurately 
found, as there is a dispute on ways to analize relations of particles. Some metrices used in analizing whether a particle detected in a layer is the same particle preceded in the previous layers
include adjacency and energy metrices. These metrices prioritize the momentum of electromagnetic particles, as a particle with higher momentum would be less susceptible to deviation in a short distance, and look for the most adjacent particle in the succeding layers.
In some circumstances, however, this method of momentum-adjacency priority may not be so representitive and can be wrong. So, this project aims to adress this issue by proposing that for each layer of calorimeter, as this paper concerns priorly electromagnetic particles, particle cluster relations
should be expressed with weigths in range a 0 to 1. A comparitive study on various elements like electromagnetic phenomenon and characteristics of particle showers, like Moliere radius and radiation depth, will be conducted to choose the right weights.
This study is a part of a paper to be submitted to JHEP. This study can be expanded to cover hadronic particles like muon and pions as well.
