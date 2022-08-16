---
Title: 			The spatial distribution and frequency of street, plot and building types across five European cities
Author:			Berghauser Pont
Year:			2019
Added in:		2021-12-06
tag:			Article
fullref: 		"Berghauser Pont, M., Stavroulaki, G., Bobkova, E., Gil, J., Marcus, L., Olsson, J., Sun, K., Serra, M., Hausleitner, B., Dhanani, A., & Legeby, A. (2019). The spatial distribution and frequency of street, plot and building types across five European cities. Environment and Planning B: Urban Analytics and City Science, 46(7), 1226–1242. https://doi.org/10.1177/2399808319857450"
status:			Extracted

---

# The spatial distribution and frequency of street, plot and building types across five European cities 
```ad-quote
Berghauser Pont, M., Stavroulaki, G., Bobkova, E., Gil, J., Marcus, L., Olsson, J., Sun, K., Serra, M., Hausleitner, B., Dhanani, A., & Legeby, A. (2019). The spatial distribution and frequency of street, plot and building types across five European cities. Environment and Planning B: Urban Analytics and City Science, 46(7), 1226–1242. https://doi.org/10.1177/2399808319857450
```
### Author's keywords
 - [[Typo-morphology]]
 - [[cluster analysis]]
 - [[built density]]
 - [[network centrality]]
 - [[land division]]

### Concepts
- [[]]
- [[]]
- [[]]
- [[]]
## Tags
#Methodologial #Theoretical #Berghauser_Pont
#EXAM_1 

## Abstract
```ad-abstract
**Typologies have always played an important role in urban planning** and design practice and formal studies have been central to the field of urban morphology. **These studies have predominantly been of a historical-qualitative nature and do not support quantitative comparisons between urban areas and between different cities**, nor offer the precise and comprehensive descriptions needed by those engaged in urban planning and design practice. **To describe contemporary urban forms,** which are more diffuse and often elude previous historic typologies, **systematic quantitative methods can be useful** but, until recently, these have played a limited role in typomorphological studies. **This paper contributes** to recent developments in this field **by integrating multi-variable geometric descriptions with inter-scalar relational descriptions of urban form. It presents typologies for three key elements of urban form (streets, plots and buildings)** in five European cities, produced using statistical clustering methods. In a first instance, the resulting typologies contribute to a better understanding of the characteristics of streets, plots and buildings. In particular, **the results offer insight into patterns between the types** _(i.e. which types are found in combination and which not_) **and provide a new large scale comparative analysis** across five European cities. To conclude, a link between quantitative analysis and theory is established, by testing two well-known theoretical propositions in urban morphology: the concept of the burgage cycle and the theory of natural movement.
```

## Bullet points
- Although [[urban typologies]] are ubiquitous in discourses about cities and urbanism, they are rarely related to more formal studies, but rather emanate from discourses within practice, as for instance found in expressions like ‘grid-cities’, ‘block-cities’ or ‘garden-cities’.

- [[typomorphological classifications]] are most often derived through visual appraisal, which has proven difficult when applied to the contemporary city (Prosperi et al., 2009).

· This paper contributes to these developments by integrating these two approaches and applying them to three key elements of urban form: streets, plots and buildings. ... in particular, it offers insight into the patterns of alignment between the types…

- Conzen (1960) introduced the concept of the burgage cycle, describing the evolution of built space over time, bounded by the spatial and legal framework of the plot.

- The burgage cycle concerns the progressive built occupation of plots, culminating in subdivision or amalgamation of original plots and a significant increase in built density (Whitehand, 2001).

- Hillier et al. (1993) discuss the pattern of alignment between [[configurational properties]] (i.e. street centrality), [[attractors]] (i.e. density and land use) and [[pedestrian movement]] in the theory of [[natural movement]], in which the former, it is argued, drives the latter two. More central streets are thus associated with more populated streets with a higher density and diversity of land uses (Hillier et al., 1993).

- For the quantitative description of streets, we use the network centrality measure, angular betweenness, following the latest methodological developments in the field of space syntax (Hillier and Iida, 2005; Turner, 2007), which describes the number of times a street segment (i.e. a node) is part of the shortest paths between all other segments in the network, which has been proven to correlate well with movement flows and patterns (e.g. Hillier and Iida, 2005; Serra and Hillier, 2018).1

- For this paper, a distance is chosen that most people are willing to walk, commonly recognised to be approximately 500 metres (Gehl, 2010). Thus, instead of plot size, the accessible number of plots within 500 metres is used. The generated typology of plots could, therefore, more accurately be described as the typology of plot patterns based on three morphological measures but will be referred to in this paper as plot types.

- **[[FSI]]** is used to describe the total amount of built floor space in an area; **[[GSI]]** describes the division between built and non-built land in an area. Together, they also inform us about the average amount of building floors by dividing [[FSI]] by [[GSI]].

- Table 1 
 ![[Pasted image 20211124181707.png]]
 
 - To develop types comparable across cities, similar geographic representation and measures of the three urban form elements are used as discussed in ‘Quantitative description of the elements of urban form’ section and all cities are classified simultaneously using k-means clustering analysis, well suited for large data sets. The main goal of clustering is to find similarities between objects to group them into classes: the greater the similarity (or homogeneity) within a class and the greater the difference between classes, the better (or more distinct) the clustering solution (Wilmink and Uytterschaut, 1984).

- For [[street]] and plot types, unsupervised clustering (Tan et al., 2005) was used, which means that, besides the raw data and the number of clusters, no input is given to the algorithms. (For streets and buildings, all cases with value 0 are excluded, because street segments with value 0 are dead-end roads; for buildings, the value 0 represents areas without any buildings; both represent uniquely identifiable clusters that can be excluded from the statistical analysis.)

- The purpose of the clustering is to identify natural structures in the data set. To know how well the proposed partition fits the input data, the silhouette index was chosen for the evaluation of the different clustering results (i.e. amount of clusters) (Arbelaitz et al., 2013).

- After clustering, cross-tabulation is used to help find patterns between the types.

- Any streets, plots or buildings in the data set that are not associated with an address point are therefore not included in the comparison of numerical distribution patterns and cross-tabulation.

- The cluster analysis resulted in five street types, which have the following profiles (Figure 1 (a)): first, **Background streets** (street cluster 2 or SC2)…‘background network’,… **Metropolitan streets** (SC1), representing street segments with betweenness values that increase especially at the highest scales, typically capturing the highway network; third, **Neighbourhood streets** (SC3), representing street segments that have high betweenness at lower scales, but betweenness drops quickly at the higher scales; **fourth, City streets** (SC4), representing street segments that have consistently high betweenness values at most scales, but distinctly dropping values at the lowest and highest scales and, coming closest to what Hillier (2009) describes as foreground network; fifth, **Dead-end streets** (SC0),…

- The {_plot_} clustering analysis resulted in seven plot types with the following profiles… **medium sized** plots (i.e. Medium-grain), but variation in the shape of the plots from **compact** (PC2) and **medium-compact** (PC1) to **non-compact** (PC4);… **Large-grain, non-compact** (PC3) that shows similarities with PC4 in terms of the lack of compactness, but has lower accessibility to other plots…

- The { _Building types_} clustering analysis resulted in seven building types that can be characterised by their mean accessible FSI and [[GSI]] values that at the same time inform us about the average amount of floors for each building type (Figure 3(a)). **Spacious low-rise** (BC1), with low FSI and GSI values and primarily capturing villa areas; **Compact low-rise** (BC2), with medium GSI and FSI values; and **Dense low-rise** (BC4), where the GSI value is the highest of the three low-rise types …. **Dense mid-rise** (BC3), with a **Spacious midrise** (BC6), with low GSI values and moderate [[FSI]] values (comparable to BC4); **Compact mid-rise** (BC5), with slightly higher [[FSI]] and [[GSI]] values; **Dense mid-rise** (BC3), with a combination of both high [[FSI]] and [[GSI]] values; and finally, **Compact high-rise** (BC7), a distinct type with very high [[FSI]] values and moderate to high [[GSI]] values.

- According to the theory of **natural movement** (Hillier, 1993), we expect the street types with high betweenness values across scales such as the Neighbourhood street type (SC3) and City street type (SC4) to be associated with denser building types (BC3 and BC5)…. Further, a difference between Neighbourhood and City streets in the different cities becomes apparent. For the Neighbourhood type streets, the trend is exactly the opposite, with large differentiation between low and high dense building types in London and Amsterdam and less so in the Swedish cities.

- We have also shown that the method presented can be used to create a link between quantitative analysis and theory, by testing two well-known theories in urban morphology: the concept of the burgage cycle and the theory of natural movement.

- Finally, an interesting next step to further develop the field of typo-morphology would be to use fuzzy or soft clustering where each observation belongs to a cluster to a certain degree, instead of hard clustering, used in this paper, where each observation belongs to a cluster or not. Fuzzy clustering is especially powerful in identifying, on the one hand, in-between types, where the degree of belonging is relatively low and equally shared by two or three clusters, and on the other hand, archetypes (i.e. the perfect example), where the degree of belonging is high.
