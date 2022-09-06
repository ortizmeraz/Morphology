---
Title: 			A time-use activity-pattern recognition model for activity-based travel demand modeling
Author:			Hafezi, etl. al. 
Year:			year
Added in:		2021-12-06
tag:			Article
fullref: 		"Hafezi, M. H., Liu, L. and Millward, H. (2019) ‘A time-use activity-pattern recognition model for activity-based travel demand modeling’, Transportation, 46(4), pp. 1369–1394. doi: 10.1007/s11116-017-9840-9."
status:			Extracted

---

# A time-use activity-pattern recognition model for activity-based travel demand modeling 
```ad-quote
Hafezi, M. H., Liu, L. and Millward, H. (2019) ‘A time-use activity-pattern recognition model for activity-based travel demand modeling’, Transportation, 46(4), pp. 1369–1394. doi: 10.1007/s11116-017-9840-9.
```
### Author's keywords
- [[activity-based model]]
- [[time-use]]
- [[machine learning]]
- [[fuzzy c-means clustering algorithm]]
- [[activity pattern recognition]]

### Concepts
- [[]]
- [[]]
- [[]]
- [[]]
## Tags
#Methodologial 
#EXAM_3 

```ad-abstract
This study develops a new comprehensive pattern recognition modeling framework that leverages activity data to derive clusters of homogeneous daily activity patterns, for use in activity-based travel demand modeling. The pattern recognition model is applied to time use data from the large Halifax STAR household travel diary survey. Several machine learning techniques not previously employed in travel behavior analysis are used within the pattern recognition modeling framework. Pattern complexity of activity sequences in the dataset was recognized using the FCM algorithm, and resulted in identification of twelve unique clusters of homogeneous daily activity patterns. We then analysed inter-dependencies in each identified cluster and characterized the cluster memberships through their socio-demographic attributes using the CART classifier. Based on the socio-demographic characteristics of individuals we were able to correctly identify which cluster individuals belonged to, and also predict various information related to their activities, such as start time, duration, travel distance, and travel mode, for use in activity-based travel demand modeling. To execute the pattern recognition model, the 24-h activity patterns are split into 288 three dimensional 5 min intervals. Each interval includes information on activity types, duration, start time, location, and travel mode if applicable. Results from aggregated statistical evaluation and Kolmogorov–Smirnov tests indicate that there is heterogeneous diversity among identified clusters in terms of temporal distribution, and substantial differences in a variety of socio-demographic variables. The homogeneous clusters identified in this study may be used to more accurately predict the scheduling behavior of specific population groups in activity-based modeling, and hence to improve prediction of the times and locations of their travel demands. Finally, the results of this study are expected to be implemented within the activity-based travel demand model, Scheduler for Activities, Locations, and Travel (SALT).

```

## Bullet points
1. In summary, the modeling framework presented in this study provides a straightforward and easy-to-implement tool for urban and transport modelers to understand time-use activity patterns for different kinds of individuals.
2. **Literature review**
3. Activity generation modules can play an important role in every activity-based modeling framework. Prediction accuracy of individual travel behavior depends on actual information drawn from activity generation modules.
4. Since 1970, when Hagerstrand developed the preliminary activity-based model (Hagerstrand 1970), researchers have used several different approaches for the activity generation modules of activity-based models, such as empirical data analysis, decision trees, and hazard functions (Arentze and Timmermans 2000; Auld and Mohammadian 2009; Recker et al. 1986a, b; Miller and Roorda 2003).
5. The activity generation module in the ALBATROSS (A Learning-BAsed TRansportation Oriented Simulation System) model consists of an integrated decision-making heuristic with learning mechanisms (Arentze and Timmermans 2000). Initially, activities are classed into two sets: fixed and flexible activities. The model then produces the fixed activities and relocates them along with their temporal and spatial information to the scheduler module of the algorithm. The flexible activities are added to schedules based on their order of priority and choice of time-of-day.
6. Activities with similar features are recognized and essential information such as activity start times and durations are generated. The activity generation module in the simulation of travel/activity responses to complex household interactive logistic decisions (STARCHILD) model comprises three successive phases (Recker et al. 1986a, b). At the beginning, the algorithm generates all the feasible travel activity patterns. Next, all possible activity-travel patterns are found and grouped. Lastly, representative patterns in each group are identified using the logit choice model.
7. One limitation of using explanatory variables for grouping the population is that using different sets of explanatory variables results in different groupings and generates different probability distributions.
8. Through aggregation of statistical learning methods and data mining, Jiang et al. (2012) proposed a new modeling framework for clustering daily patterns of individual activities. Numerous machine learning techniques such as the K-means clustering algorithm and the principal component analysis (PCA) were employed to explore the inherent daily activity structure, and populations were clustered based on the similarity of their activities.
9. [ ] In another study, Li and Lee (2017) utilized probabilistic context-free grammars in the modeling and learning of daily activity patterns. Saneinejad and Roorda (2009) measured similarities between routine weekly activity sequences by utilizing the multiple sequence alignment methods.
10. **Method used in the article**
11. The pattern recognition modeling framework in this study comprises four modules, as follows. First, we employed a subtractive clustering algorithm for initializing the total cluster number and cluster centroids.
12. The second step in the proposed pattern recognition modeling framework is to identify individuals with homogeneous activity patterns and group them into clusters. For this purpose, the fuzzy C-means (FCM) unsupervised machine learning algorithm is employed. In the FCM each data point that represent a person-day activity has the likelihood to belong to several clusters. This aspect of the algorithm boosts the cluster quality by selecting the best fitted data points.
13. The third step in the proposed pattern recognition modeling framework is to identify the sets of representative activity patterns. For this purpose, the multiple sequence alignment (MSA) method is employed. The sequence alignment method is commonly used in the biological sciences to compare strings of chromosomes. One of the main challenges of the sequence alignment problem is to compute the required number of stages in order to align two strings (Chenna et al. 2003). This problem can be solved using various methods such as heuristic methods, approximation algorithms, probabilistic methods, and global optimization.
14. The last step in the proposed pattern recognition modeling framework is to discover the inter-dependencies among the socio-demographic attributes of persons in each identified cluster, with an assumption that cluster membership is dependent on demographic features.
15. **Conclusions**
16. Due to lack of full data on all individuals of the population, transport modelers are not able to predict or model the travel behavior of all individuals in the territory. Consequently, the best policy is to predict or model travel behavior for a representative set of model individuals, who represent homogeneous cohorts. Accordingly, aggregation is both inescapable and essential in travel demand modeling.
17. The proposed pattern recognition modeling framework in this study comprises four modules.
	1. The first module, subtractive clustering algorithm, initialized the cluster centroids.
	2. In the 3rd module twelve representative activity patterns were recognized, corresponding to cluster centroids. 
	3. In the next module, person-days in the dataset were bundled into dissimilar clusters based on comparable routine activity sequences using the novel and efficient fuzzy C-means (FCM) clustering algorithm.
	4. Finally, in the last module inter-dependencies among the attributes of each identified cluster were investigated using the CART algorithm.
		- …, the CART classifier algorithm was used to explore inter-dependencies among the attributes in each identified cluster, and to relate the membership of cluster individuals to their socio-demographic characteristics


