Goal of the Project: Analysis of Hazardous Ingredients in Cosmetics Reported to the California Safe Cosmetics Program (CSCP)
The primary goal of this project is to analyze and evaluate the data collected by the California Safe Cosmetics Program (CSCP) to assess the presence of hazardous ingredients in cosmetic products sold in California. 
By conducting this analysis, the project aims to achieve the following objectives:
Objective: 
Investigate the presence and frequency of chemicals that are known or suspected to cause cancer, birth defects, or other developmental or reproductive harm.
Approach: Analyze the reported data to identify patterns in the use of such chemicals over time and across different product categories.
Outcome: Generate insights about which chemicals are most commonly used, their potential health risks, and whether there are changes in their prevalence within the cosmetic industry.
Expected impact:
This project aims to significantly improve the understanding of hazardous chemicals in cosmetics and drive better practices within the industry. By raising awareness, increasing compliance, and supporting consumers with relevant information.
the project hopes to promote a safer and more transparent cosmetic market, ultimately reducing the risk of exposure to harmful substances.
columns used:
1)CDPHId: Likely an ID related to the California Department of Public Health (CDPH).

2)ProductName: The name of the product.

3)CSFId: Likely a unique ID for a CSF (could be related to a specific certification or program).

4)CSF: Information about the CSF, possibly indicating a certification, status, or category.

5)CompanyId: Unique identifier for the company.

6)CompanyName: Name of the company.

7)BrandName: Name of the brand associated with the product.

8)PrimaryCategoryId: ID for the primary category of the product.

9)PrimaryCategory: The main category of the product.

10)SubCategoryId: ID for the subcategory of the product.

11)SubCategory: The subcategory under which the product is listed.

12)CasId: Likely referring to an ID related to the Chemical Abstracts Service (CAS).

13)CasNumber: The CAS number associated with the product or chemical.

14)ChemicalId: Unique identifier for the chemical in the product. 15)ChemicalName: The name of the chemical.

16)InitialDateReported: The first date this product/chemical was reported.

17)MostRecentDateReported: The most recent date the product/chemical was reported.

18)DiscontinuedDate: The date when the product or chemical was discontinued.

19)ChemicalCreatedAt: The creation date of the chemical record.

20)ChemicalUpdatedAt: The last update date of the chemical record.

21)ChemicalDateRemoved: Date when the chemical was removed (from a database or list).

22)ChemicalCount: Likely the number of occurrences or items related to the chemical.

Conclusion:

1)Gradient Boosting shows a strong performance, with high precision and a solid recall, indicating it balances both false positives and false negatives well.
 The relatively small gap between training and test accuracy suggests that the model is generalizing well to new data.
2)The Decision Tree performs exceptionally well, with near-perfect accuracy both on the training and test datasets.
The weighted precision, recall, and F1 scores further demonstrate its ability to classify the data effectively, though it may be overfitting to some extent.
3)KNN shows a solid performance with high accuracy on the test set. The model has a good balance between precision, recall, and F1-score
but it might not be as strong as the Decision Tree or Random Forest in terms of raw accuracy, though it's still highly effective for classification tasks.
4)Forest achieves excellent performance, similar to the Decision Tree, but with slightly better generalization to the test set (lower overfitting). 
The precision, recall, and F1 scores are very high, confirming the robustness and reliability of the model.
5)Linear regression shows decent precision, but its recall is relatively lower, meaning it might miss some positive cases. 
The F1 score is reasonable, but it's evident that linear regression isn't as effective as the other classification algorithms, especially when dealing with imbalanced data or more complex decision boundaries.


