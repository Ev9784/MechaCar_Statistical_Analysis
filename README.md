# MechaCar_Statistical_Analysis
![MapWhatGIF](https://user-images.githubusercontent.com/98368422/164949884-6a568840-d4f1-444e-bb37-b68306d981ac.gif)

## Deliverable 1: Linear Regression to Predict MPG 
	* Vehicle Length and Vehicle Ground Clearance are statistically significant with a p-value = 0.00000000000260 and p-value =  0.0000000521 respectively. This indicates these two factors significantly influence the MechaCar gas mileage. While Spoiler Angle, Vehicle Weight, and AWD have p-values greater than the .05 threshold for significance. 

	* The slope of this model would not be considered zero. With the overall p-value = 0.0000000521 for the model, we can reject the null hypothesis and demonstrate the slope would not be considered 0. 

	* This model can predict the gas mileage of MechaCar prototypes relatively effectively. Our R-Squared value = .7149, which roughly computes 71% of predictions. This would account for a large majority of mpg estimates. 

## Deliverable 2: Summary Statistics on Suspension Coils
	* The Total Summary for the production lot has a variance of 62.29, which does meet the design specifications. Lot 1 and Lot 2 do appear to meet the design specification for their respective manufacturing lots. Lot 1 has a variance of approximately .98, and Lot 2 has a variance of roughly 7.47. However, Lot 3's variance of 170.29 dramatically exceeds the design specifications. Lot 3 appears to be problematic and will need further investigation. 

## Deliverable 3: T-Tests on Suspension Coils

	* The actual mean for the sample across all the manufacturing lots was 1498.78 with a p-value = .06028, meaning we fail to reject the null hypothesis that there is a statistical significance in this case. 

	* Lot 1 had a proper mean of 1500 with a p-value = .61; we are also unable to reject the null hypothesis for this lot. 

	* Lot 2 had an actual mean of 1500.02 and a p-value = .61, meaning we cannot reject the null hypothesis. 

	* Lot 3 had a proper mean of 1496.14 and a p-value = .04, which means it does meet the threshold for statistical significance for this lot, and we reject the null hypothesis. This would be consistent with the significant variance we saw for Lot 3's PSI and signals there is more than likely a defect in this group. 

## Deliverable 4: Study Design MechaCar vs. Competition

	* MechaCar vs. Competition - Cost and Fuel Economy - how does MechaCar compare to similar models in terms of initial investment cost and fuel efficiency? 

	* Null Hypothesis: MechaCar and the Competition are priced similarly and have similar fuel efficiency compared to other vehicles in their class across the population from all manufacturers. 

	* Alternative Hypothesis - MechaCar fuel economy and initial price differ significantly from other competitors and the population of vehicles in its class. 

	* Identify all similar vehicles from competing manufacturers, and gather average selling price data for those models as well as the average gas mileage. Create a table containing all of this data and calculate summary statistic data to make comparisons between MechaCar and other individual competitors. Aggregate the summary statistics across the entire group and determine whether or not MechaCar varies significantly in terms of affordability. 

