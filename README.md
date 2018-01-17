# Dendrogram 

By Raphaël Allier

**Definition**: A dendrogram is a graphical representation of different aggregations made during a cluster analysis. It consists of knots that correspond to groups and branches that represent the associations made at each step. The structure of the dendrogram is determined by the order in which the aggregations are made. [1]
It comes from Greek "dendro" meaning tree, and "gramma", meaning analysis.

## 1. Historical examples 
The first examples of dendrograms were the phylogenetic trees (a tree that shows the inferred evolutionnary relationships among various biological species) by systematic specialists. The term "dendrogram" looks to have been used for the first time in the work of Mayr et al in 1953 [1]. 

![Exemple of phylogenetic tree](/images/phylogenetic_tree_example.jpg)

__Example of Phylogenetic tree [2]__

Most of the time Dendrograms are used in biology to describe the evolution of species. 

However they are also present in algorithms in cluster analysis. On a set of objects, a dendrogram allows to depict aggregations being made over iterations (the aggregations are made following a distance table that is computed at each iteration). Once all of the instances have been linked through the iterations, the dataset can be cut into clusters where the distance between instances is minimal within a cluster. 

![Example of dendrogram](/images/dendogram_example.png)

__Example of Dendrogram showing aggregations between instances[3]__

## 2. Recent most famous ones 

The better part of all famous dendrograms are phylogenetic trees, as are the ones below. 

![Phylogenetic tree of domestic dogs and grey wolves](/images/dogs_phylogenetic.jpg)

__Phylogenetic tree of domestic dogs and grey wolves[4]__

The previous phylogenetic tree depicts the distance between different dog breeds based on their DNA. 

![Phylogenetic tree of four-legged animals](/images/dendogram_time.png)

__Phylogenetic tree of some four-legged animals[5]__

As seen in the previous chart, the dendrogram can also be used to depict the time taken between the aggregation of the instances. In cluster analysis, this is the equivalent of separating different iterations of a clustering algorithm. 






## 3. Comments 

![Creation of a phylogenetic tree](/images/build_tree.png)

__Creation of a phylogenetic tree[6]__

Usually, phylogenetic tree are created from a dendrogram using simple modifications so they appear more as a chart depicting the evolution of the designated species. 

![Dendrogram on the famous Iris dataset](/images/Iris_dendrogram.png)

__Example of clustering on the famous Iris dataset__

As seen in the previous figure, the type of data used to create a dendrogram is simply instances of a dataset. 




## 4. Sources

[1] (2008) Dendrogram. In: The Concise Encyclopedia of Statistics. Springer, New York, NY
https://link.springer.com/referenceworkentry/10.1007%2F978-0-387-32833-1_103

[2] University of Michigan-Dearborn
 http://www-personal.umd.umich.edu/~fdolins/berenty/aboutberenty/fauna/lemurs/_phylogenetictree/index.html

[3] California Soil Resource lab
https://casoilresource.lawr.ucdavis.edu/blog/graphical-explanation-how-interpret-dendrogram/

[4] Creative Biostructure
https://www.creative-biostructure.com/custom-phylogenetic-tree-construction-service-399.htm

[5] Institute of Canine biology
http://www.instituteofcaninebiology.org/how-to-read-a-dendrogram.html

[6] Khanacademy
https://www.khanacademy.org/science/biology/her/tree-of-life/a/building-an-evolutionary-tree

[7] <a href=https://cran.r-project.org/web/packages/dendextend/vignettes/Cluster_Analysis.html>  Hierarchical cluster analysis on famous data sets by Tal Galili </a>

