# FREEtree

FREEtree, a tree-based method for high dimensional longitudinal data with correlated features. FREEtree deals with longitudinal data by using a  piecewise random effect model. It also exploits the network structure of the features, by first clustering them using Weighted Gene Coexpression Network Analysis (WGCNA). Then it conducts a screening step within each cluster of features and a selecting step among the surviving features, which provides a relatively unbiased way to select features. By using dominant principle components as regression variables at each leaf and the original features as splitting variables at splitting nodes, FREEtree maintains its interpretability and improves its computational efficiency. The simulation results show that FREEtree has improvements over other tree-based methods in terms of prediction accuracy, feature selection accuracy as well as the ability to recover the underlying correct structure. 

## Methods


## Installing 

To be completed after CRAN submission.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags). 

## Authors

* **Yuancheng Xu** 
* **Dan Kojis** 
* **Min Tan** 
* **Christina Ramirez**  

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

