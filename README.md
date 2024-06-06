We are exploring the analysis and modeling of a furniture dataset from Flipkart, focusing on predicting discounted prices based on original prices. The dataset includes attributes such as `furniture_type`, `name`, `discounted_price`, and `original_price`.

After loading and cleaning the data, we employed polynomial regression and decision tree regression to model the relationship between the original and discounted prices. Polynomial regression, which can capture non-linear relationships, showed good performance, indicated by a high R^2 score. Decision tree regression, known for its ability to model complex interactions without feature transformations, also performed well.

We visualized the models' predictions against actual data, showing the polynomial regression's smooth curve and the decision tree's step-like predictions. Additionally, we visualized the decision tree's structure, providing insights into how it splits the data based on original prices to make predictions. Each node in the tree represents a decision rule, with leaf nodes providing the final predicted discounted prices.

Our analysis highlights the strengths of both approaches: polynomial regression for capturing smooth trends and decision trees for handling complex interactions. These models can help businesses optimize pricing strategies by accurately predicting discounted prices based on original prices.
