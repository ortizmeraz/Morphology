---
Title: 			Retail Fabric Assessment: Describing retail patterns within urban space
Author:			Araldi, A., & Fusco, G.
Year:			2019
Added in:		2022-08-16
tag:			Article_
group:			group
fullref: 		"Araldi, A., & Fusco, G. (2019). Retail Fabric Assessment: Describing retail patterns within urban space. _Cities_, _85_, 51–62."
status:			Need to extract
---

# Tittle 
```ad-quote
reference
```
### Author's keywords
- [[Retail distribution]]
- [[Retail fabrics]]
- [[Geoprocessing]]
- [[Point pattern analysis]]
- [[Bayesian classification]]
### Concepts
- [[]]
- [[]]
- [[]]
- [[]]
## Tags
#EXAM_1 

```ad-abstract
text
```

## Bullet points
1. Page 1
2. 1-Introduction
3. The presence of retail activity within urban space is of paramount importance to street and neighborhood attractiveness: it enhances social and economic exchanges between citizens, contributing to the dynamics of a city (Gehl, 1987; Jacobs, 1961)
4. Spatial distribution of retailers within settlements reveals information on the socio-economic characteristics of the population living and working in those spaces
5. The aggregate choices of consumers shape the overall patterns of retail activities (Craig, Ghosh, & McLafferty, 1984).
6. Awareness of the role of retail presence in urban space is now a well-established value for planners. Indicators of retail presence have been also incorporated in street/neighborhood measurement for real estate value estimation (i.e. Walk Score in USA,1 CityScan in France, etc.).
7. Starting from Central Place Theory, researchers deducted and debated different spatial representations and models of retail distribution within urban settlements (Berry, 1963; Burns, 1959; Davies, 1974; Guy, 1994; Proudfoot, 1937). Constantly evolving technological progresses are modifying and multiplying citizens' shopping behaviors,
8. Page 2
9. The study of retail distribution within settlements (retailscape, (Cachinho, 2014)) is not merely a descriptive task. Identifying retail fabric patterns and their spatial configuration represents the first step for the elaboration of new urban planning development and regeneration projects. Furthermore, it might represent an essential variable for locational decision and modeling of retailers.
10. Retail Fabric Assessment (RFA) is based on senior theoretical models but allows the identification and characterization of urban retail localization patterns in a whole metropolitan area, with a micro-scale bottom-up approach, using automated geo-processing.
11. 2. Retail patterns, models
12. Proudfoot (Proudfoot, 1937) transposed the concepts of Central Place Theories (CPT) to the intra-urban retail distribution. Based on detailed studies of several American cities, this author proposed the first spatial representation of commercial structure through the definition of five categories of retail districts: Central Business District (CBD), outlying business centers, principal business thoroughfare, neighborhood business street and isolated store clusters.
13. The most studied and discussed scheme is the Berry's hierarchical model (Berry, 1963). The analysis of the business districts of Chicago led this author to identify three morpho-functional groups: (i) nested hierarchical centers, (ii) commercial ribbons and (iii) specialized areas (Fig. 1). Each of these groups is divided in sub-groups considering size and complexity of the retail structure.
14. Consequently, several post- and quasi- hierarchical models have been proposed to address these criticisms. Brown's (1991) taxonomy represents an interesting evolution of the hierarchical model. The starting point of Brown's classification is based on the identification of two main aspects describing retail districts: the form of a shopping area and its function. Three types of form can be recognized: cluster, linear and small isolated concentrations.
15. The combination of these two factors, generates a classification matrix composed by 9 groups of commercial districts, extended to 12 when considering planned/unplanned clusters (Fig. 2).
16. ![[Pasted image 20220816114211.png]]
17. A growing number of quantitative studies in urban geography and urban planning explored the relationships between urban form and socioeconomic characteristics within a city.But when it comes to cross analyzing these properties with retail distribution, the simple density/presence of stores is considered. As discussed in the introduction, the combination of spatial distribution and functional mix at the origin of the retail system should not be reduced to simply counting the number of stores in a given space.
18. We thus propose to define the new concept of retail fabrics within the city, taking into account the most characteristic spatial and functional properties of retail distribution patterns within urban space and building on the aforementioned theories of retail geography in the city.
19. Only separate assessments of urban fabrics and retail fabrics might allow in a later phase of analysis, the study of the interrelations between these two aspects revealing the organization of the global form of a complex city as a whole.
20. Page 3
21. Asides from that, it seems to us that a clearer understanding of the spatial logics of retail distribution in the city should not ignore the main characteristic of urban space for pedestrians and retailers: urban space is a network space, and all administrative subdivisions ignore this very nature of urban spatiality.
22. Urban planners and practitioners aware of the importance of theoretical models and of the lack of well-established methodological procedures beyond traditional aggregate statistics, adopted classification measures of the urban retail spaces based on expert-based knowledge and observation of the space study under analysis.
23. A systematic, quantitative, bottom-up (even if partially theory driven) approach for retail distribution assessment at the urban microscale is therefore needed for both modeling and assessment purposes. In order to achieve this goal, empirical studies resulting from economic geography theories need to be combined with methodological works from geo-statistics and point pattern analysis.
24. . Page 4
25. Mackaness and Chaudhry (2011) propose an automatic classification of retail spaces from a large scale topographic database.
26. This work represents one of the first examples of classification of retail concentrations considering different aspects of retail configuration.
27. Vazquez (2011) applied k-means classification on eight configurational, form and dimension indicators.
28. Hidalgo and Castañer (2015) implement a recommender system to identify missing amenities considering current specialization patterns within neighborhoods. An ad hoc clustering algorithm is here im plemented starting from a distance based accessibility indicator.
29. Jensen (2006) proposes a local appropriateness indicator for each retail activity in a specific location, considering store presence within its surrounding area. This indicator is based on quantitative measures of local spatial attractive/repulsive behaviors between retail categories, based on the M (Duranton & Overman, 2005; Marcon & Puech, 2009).
30. The analysis of density based spatial clustering algorithms applied to retail distribution in the city represents the focus of Dolega, Pavlis, and Singleton (2016). In this paper spatial methods for point  pattern clustering identification like k-means, quality threshold, KDE, random walk and density based spatial clustering of application with noise (DBSCAN) are applied and compared.
31. The spatial arrangement of a given set of points at different scales is compared to random distributions, in order to detect and extract clustering/clumping information pertaining only to anomalies, which means identifying elements that are unlikely to happen by chance.
32. From the works reviewed in this section we can formulate the following observations: (i) Classifying retail fabrics in the city should be independent from physical elements of the urban settlements; (ii) Partitioning retail points through clustering/clumping methodologies, by the means of thresholds or adopting exogenous administrative partitions could bias the results of the resulting functional correlations. (iii) Any fine-grained spatial analysis of retail should respect the network-space of the city. (iv) Data-based classification methods can produce more objective results and serve as a basis for comparative analysis and simulation models. (v) The analysis of retail distribution cannot be reduced to a simple agglomeration analysis (Guy, 1998): form and function should be considered simultaneously.
33. Page 5
34. 5. Methodology
35. Together with these objectives, some methodological constrains are included: (a) Network constrained distances to respect the nature of retail distribution within the city; (b) Minimal and standardized information on retailers, required to guarantee the reproducibility and adaptability to other case studies.
36. Multiple Retail Assessment (MRA) is a three-step protocol for the analysis of retail distribution; it can be summed up as follows: 
	1. Defining a network constrained catchment area around each event and collecting retail activity information.  
	2. Identification of retail distribution patterns: (i) configurational properties, (ii) geometrical distribution (iii), local significant prevalence of retail typology; 
	3. Clustering of relative event-based patterns through Bayesian methods in order to identify and characterize retail fabrics.
37. 5.2. Form and functioning patterns
38. In the following description of pattern recognition, three local levels have been separately associated to each indicator, depending on the enclosed information. We refer to them as: street level (r = 150 m), neighborhood level (r = 300 m) and community level (r = 600 m). The local Form of retail activities is described by a set of three indicators:
39. - Relative Accessibility. For each store-point, we compute the total number of retailers N(r) within a given radius r. A segmentation based on quantiles is applied to the statistical distribution of N(r) on the overall study area. This discretization informs us on the relative importance of local retail accessibility.
40. Page 6
41. - Agglomeration considers the ratio of the number of stores at two different scales: street/neighborhood levels and neighborhood/community levels. This indicator discloses the information on the aggregation of the retailscape at a given level compared to the larger one.
42. - Geometry refers to the morphological nature as defined by Berry (1963). This indicator is obtained implementing the point pattern analysis methodology developed by Araldi and Fusco (2018). This procedure detects the local geometrical layout of a point pattern dataset on network implementing the functional sandbox counting method (Kanevski & Pereira, 2017) developed in fractal studies.
43. In order to identify retail fabrics, we still have to combine the results of the geo-statistical and morphology patterns.
44. The local Functioning of a retail distribution is described by three indicators: Retail category variety is described by the number of retail types present within the neighborhood distance. This indicator represents the amplitude of the commercial offer enabling a multi-purpose shopping behavior. Lower values of variety might represent both specialized areas and small convenience/street-corner developments.
45. Retail category prevalence aims at identifying significant patterns of specific function concentrations.
46. The results of the application of this methodology to each group of the 12 retail typologies identify statistical High, Low and Not Significant patterns of functional prevalence (Fig. 6).
47. - Anchor store category prevalence. This group of indicators are introduced in the analysis to consider the presence of anchor stores in the retail ecosystem. The importance of these magnet/attractor stores (Brown, 1994) requires a specific group of indicators to quantify their influence on smaller retailers and also those “out-of town” store configurations, missing in the hierarchical models.
48. 5.3. Recomposing and characterizing retail fabrics: Bayesian classification
49. Bayesian inference method is based on conditional probabilities (Duda, Hart, & Stork, 2001); this method tries to minimize the probability of error in a decision, by associating to each individual the most probable outcome.
50. Page 8
60. Results and discussion
61. . The main result of the Bayesian classification is represented by the assignment of each individual store to its most probable cluster.
62. . Describing the precise profile of each retail fabric (RF) obtained goes beyond the aim of this paper.
63. Page 11
64. 7. Conclusions and perspectives
65. We proposed a multi-step geoprocessing approach to identify retail districts in a vast metropolitan area. It integrates a theory-based matrix of morpho-functional indicators taking into account the micro retail location, network-constrained geo-statistics and Bayesian clustering.
66. Brown's and Berry's models represent the theoretical foundation of the RFA procedure: these theories have been developed and discussed along the last century considering European and North American case studies. With a few adaptations, RFA might nevertheless help in describing and defining new theoretical models for non-western countries. For example, in the Japanese and Korean context it is well known that retailers are not limited to the ground floor: the vertical dimension of retail distribution represents an important aspect that should be considered when analyzing the retail fabric of a city (Cho, 2015; Shelton, 1999). The third dimension in these cities correspond to both planned and unplanned commercial centers while in western cities the latter is missing. For far-eastern cities, the RFA indicator of geometry should be thus extended to third dimension, allowing the identification of these specific retail districts.
67. RFA presents several methodological innovations allowing a vast range of applications. The probabilistic content of the Bayesian clustering could be better exploited to identify uncertainties in the knowledge of retail district spatial organization. The bottom-up procedure removes the store district delimitation problem and consequently, the need of an a priori taxonomy of retail agglomerations.
68. Page 12
69. Finally, the cross analysis of these results with urban fabric parameters, street accessibility and centrality values, might highlight interrelations between settlement form and commercial functioning. This is a particularly important perspective within our research, linking retail policies to urban planning and urban design.
