1. Performed initial data understanding to identify feature types, target variable structure, and overall dataset characteristics.
2. Conducted exploratory data analysis (EDA) to understand customer behavior patterns and relationships with term deposit subscription.
3. Analyzed categorical features using count plots, crosstabs, and percentage-based comparisons to study class-wise behavioral trends.
4. Analyzed numerical features using distributions, KDE plots, and summary statistics to understand spread, skewness, and class separation.
5. Observed strong skewness in several numerical variables and therefore used non-parametric statistical methods where appropriate.
6. Applied the Mann–Whitney U test to compare numerical feature distributions between subscribers and non-subscribers without assuming normality.
7. Used Rank Biserial Correlation (RBC) as a non-parametric effect size measure to quantify practical significance after the Mann–Whitney U test.
8. Used chi-square tests and effect-size interpretation for categorical variables to evaluate association strength with the target variable.
9. Identified important behavioral and financial features such as duration, poutcome, balance, contact type, and campaign frequency.
10. Recognized duration as a potential data leakage feature because it becomes known only after the marketing interaction.
11. Performed feature engineering and categorical grouping to improve interpretability and reduce category sparsity.
12. Applied encoding techniques such as One-Hot Encoding to convert categorical variables into machine-readable numerical format.
13. Used scaling/standardization to normalize feature magnitudes for models sensitive to feature scale.
14. Split the dataset into training and testing subsets to evaluate model generalization on unseen data.
15. Built baseline machine learning models including Logistic Regression, Decision Tree, Random Forest, and Gradient Boosting.
16. Understood Logistic Regression as a linear probabilistic classifier with regularization-based complexity control.
17. Understood Decision Tree as a high-variance nonlinear model capable of learning hierarchical decision boundaries.
18. Understood Random Forest as a bagging-based ensemble method that reduces variance by averaging multiple decorrelated trees.
19. Understood Gradient Boosting as a sequential ensemble technique that reduces bias by iteratively correcting previous model errors.
20. Applied hyperparameter tuning using RandomizedSearchCV to optimize model complexity and improve generalization performance.
21. Used cross-validation during tuning to evaluate model stability across multiple train-validation splits.
22. Evaluated models using Accuracy, Precision, Recall, and F1-score to analyze different classification tradeoffs.
23. Interpreted Precision as the reliability of positive predictions and Recall as the ability to capture actual subscribers.
24. Used F1-score as the harmonic balance between Precision and Recall for balanced classification evaluation.
25. Constructed confusion matrices to visualize true positives, false positives, false negatives, and true negatives for each model.
26. Compared confusion matrices across models to understand practical prediction behavior beyond aggregate metrics.
27. Performed PCA-based visualization to study variance structure and low-dimensional class separability in the dataset.
28. Observed limited clear linear separability through PCA, indicating complex nonlinear relationships among customers.
29. Used feature importance analysis to identify variables contributing most strongly to predictive performance.
30. Understood ROC curves as threshold-based TPR–FPR tradeoff visualizations across all classification thresholds.
31. Interpreted ROC-AUC as a measure of overall class separability and ranking quality between subscribers and non-subscribers.
32. Understood ROC-AUC probabilistically as the likelihood that the model ranks a randomly chosen subscriber above a non-subscriber.
33. Compared ROC-AUC across models to identify the strongest overall ranking-based classifier.
34. Understood PR curves as Precision–Recall tradeoff visualizations especially relevant for positive-class prediction quality.
35. Understood PR-AUC as a more sensitive metric for minority-class evaluation and positive prediction reliability.
36. Compared PR-AUC across models to analyze how effectively models maintained precision while increasing recall.
37. Observed that ensemble methods consistently outperformed standalone models in both ROC-AUC and PR-AUC evaluations.
38. Identified Random Forest and Gradient Boosting as the strongest models due to superior nonlinear learning and generalization capability.
39. Discussed threshold optimization conceptually as a business-dependent deployment strategy for balancing operational cost and customer capture.
40. Discussed profit-cost analysis conceptually as a future business-oriented extension depending on organizational marketing objectives.
41. Summarized the project through comparative evaluation, interpretability analysis, and business-oriented performance understanding.

