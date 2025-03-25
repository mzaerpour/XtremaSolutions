# [Agriculture’s impact on water–energy balance varies across climates](https://link.growkudos.com/1eqzjantrls)

**Authors**: Masoud Zaerpour, masoud.zaerpour@ucalgary.ca, Shadi Hatami, André S. Ballarin, Simon Michael Papalexiou, Alain Pietroniro, and Ali Nazemi

**Published**: 2025 in Proceedings of the National Academy of Sciences (PNAS)

**DOI**: [https://doi.org/10.1073/pnas.2410521122]

# Abstract #
Agriculture plays a key role in global food security, intricately tied to water resources for crop growth. However, navigating the interplay between agriculture and water availability poses challenges, especially during the Anthropocene, where traditional perspectives often overlook agriculture’s impacts on the water cycle. Understanding and integrating agriculture’s influence on water dynamics becomes imperative in addressing contemporary challenges. Our study highlights the contrasting impacts of agricultural activities across temperate and snowy climates. In temperate catchments, agriculture weakens the precipitation-streamflow (P-Q) relationship, contributing to precipitation-driven deviations from the water–energy balance, while in snowy catchments, agricultural activities strengthen the P-Q relationship. These findings offer insights for shaping effective water management strategies, ensuring food security, and promoting sustainable development globally.

## Results

Figure 1 below compares how well catchments in the United States (panels A and B) and Great Britain (panels C and D) follow the Budyko curve, which links the water balance (precipitation, evaporation, and runoff) of catchments. 

- In the United States (Fig. 1A), most catchments closely follow the Budyko curve, but on average they produce a slightly higher ratio of streamflow to precipitation (Q/P) than the curve predicts (by about 0.02). When the catchments are grouped by their percentage of cropland (CL%), those with more cropland tend to have a higher fraction of evaporation (E/P) and a lower ratio of runoff (Q/P). As shown in Fig. 1B, these cropland-rich catchments also tend to have higher streamflow anomalies, suggesting agriculture can shift hydrological processes away from what the Budyko curve alone would predict.

- In Great Britain (Fig. 1C), the average Q/P is also above what the Budyko curve forecasts (by about 0.04), implying slightly larger deviations than in the United States. Similar to the US catchments, Great Britain’s cropland percentage is associated with changes in the runoff ratio, as illustrated in Fig. 1D. 

Overall, the figure shows that agricultural activity—in both the United States and Great Britain—tends to shift catchments away from the “natural” water balance predicted by the Budyko curve, likely because cropland management alters how much water is evaporated or used by crops before it becomes runoff.

![Figure 01: The long-term observed streamflow and precipitation data are analyzed within the framework of the Budyko hypothesis (56). Panels (A) and (B) depict data for the United States, with (A) showing Budyko framework results and (B) illustrating the Spearman rank correlation between the percentage of cropland and the anomaly from the Budyko curve. Panels (C) and (D) present the corresponding results for Great Britain (GB), with (C) showing Budyko framework results and (D) illustrating the Spearman correlation. The colors indicate the percentage of cropland in each catchment. Spearmans between the CL% and the normalized streamflow anomaly in the United States and GB are 0.56 and 0.51, respectively. The normalized streamflow anomaly is calculated as the difference between the simulated (i.e., Budyko-based) and actual streamflow divided by the long-term precipitation. These anomalies indicate how agricultural activities alter the natural partitioning of water between evaporation and runoff.](papers/images/figure01.jpg)

Figure 2 below shows how different factors—cropland percentage (CL%), vegetation, and precipitation seasonality—contribute to deviations from the Budyko curve under various climate conditions. Researchers used a Random Forest (RF) analysis to break down the influence of each factor within three main climate classes (temperate, snow, and others). The temperate and snowy catchments dominate the data (over 90% of all stations) and include most of the agricultural regions studied, so their patterns strongly shape the overall findings. 

In running the RF models, the team used 1,000 decision trees and observed that the Out-of-Bag (OOB) error stabilized after about 400 trees, confirming that the model had sufficient complexity. Overall, the results highlight that besides agricultural activities, vegetation and the seasonal distribution of rainfall are also key players in affecting how real-world catchments deviate from what the Budyko curve would predict.

![RF model analysis of the relative importance of cropland percentage (CL%), vegetation, and precipitation seasonality in explaining deviations from the Budyko curve for catchments classified by the Köppen-Geiger climate classification. Panel (A) presents the factor importance for three climate classes. Panel (B) shows the OOB Error against the number of trees for each class. The analysis highlights that CL% consistently demonstrates the highest importance in temperate and snowy climates, surpassing the influence of vegetation and precipitation seasonality.](papers/images/figure02.jpg)

---

## What is it about?  
Agriculture accounts for approximately 72% of global water use, and its growing demand is putting pressure on water supplies and disrupting natural balances. This study examined how agricultural activity influences the water–energy balance across 1,342 catchments in the United States and Great Britain, identifying key factors driving changes in streamflow patterns using a causal discovery algorithm.  Analysis showed that in temperate regions of Great Britain, cropland expansion weakened the natural link between rainfall and river flow more than any other factor, including aridity and vegetation cover. In snowy climates, however, cropland had the opposite effect, strengthening the connection between precipitation and streamflow. Further analysis suggested a shift toward greater groundwater reliance in the US agricultural areas, as changes in baseflow indicated reduced dependence on direct precipitation. These findings provide valuable insights for improving water management strategies, ensuring food security, and promoting sustainable development globally.

## Why is it important?
We combine a simple yet powerful Budyko framework with causal analysis to reveal how agriculture’s impact on the water–energy balance varies across different climates, leading to distinct implications for water resource management. Our findings show that cropland can either weaken or strengthen the connection between precipitation and streamflow, depending on regional conditions. This nuanced understanding is crucial as climate change accelerates hydrological shifts, demanding more adaptive and climate-specific water management strategies. By integrating causal inference with a well-established hydrological framework, these findings provide valuable insights for improving water management strategies, ensuring food security, and promoting sustainable development globally.

## Perspectives
I hope that, in the face of population growth and climate change, this article draws attention to the need for sustainable agricultural expansion that carefully considers water resource management. Balancing the growing demand for food with responsible water use is more critical than ever. By highlighting how agriculture's impact on the water–energy balance varies across different climates, I hope this research sparks discussions on innovative development and management strategies that ensure long-term sustainability. Our goal is for this work to encourage policies and practices that support both agricultural productivity and the preservation of vital water resources, ultimately helping to secure a more resilient future for both people and the environment.

## Reference 
(https://doi.org/10.1073/pnas.2410521122)
