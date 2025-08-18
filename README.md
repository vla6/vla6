## Valerie Carey's Personal Repository 

This is my personal code stash, where I explore some of my favorite topics, including:
* Categorical feature embeddings and encodings
* Model explainaibilty methods and their limitations
* Testing processes to detect and mitigate bias in machine learning models

*See also [vcarey-circlestar](https://github.com/vcarey-circlestar)*

## Towards Data Science 

You're a  Towards Data Science Reader?  Get the code used for my articles here:

#### [Visualizing Stochastic Regularization for Entity Embeddings](https://github.com/vla6/Blog_naics_nn/tree/main/_A_embeddings)

Pretty pictures illustrate how stochastic regularization impacts entity embeddings in neural network models.  

#####Topics: Python / Tensorflow / tSNE / kMeans / SHAP / Entity Embeddings

Read the article at [TDS](https://towardsdatascience.com/visualizing-stochastic-regularization-for-entity-embeddings-c0109ced4a3a/) or [Medium](https://medium.com/data-science/visualizing-stochastic-regularization-for-entity-embeddings-c0109ced4a3a).

#### [Data Disruptions to Elevate Entity Embeddings](https://github.com/vla6/Blog_naics_nn)

Exploring how messing with data can increase model accuracy and robustness, when using entity embeddings in neural network models. 

#####Topics: Python / Tensorflow / Stochastic Regularization / Data Generators / Entity Embeddings

Read the article at [TDS](https://towardsdatascience.com/data-disruptions-to-elevate-entity-embeddings-b1ddf86a3c95/) or [Medium](https://towardsdatascience.com/data-disruptions-to-elevate-entity-embeddings-b1ddf86a3c95).

#### [No Label Left Behind: Alternative Encodings for Hierarchical Categoricals](https://github.com/vla6/Blog_gnn_naics/tree/main/A_target_count_encoding)

A comparison of several methods of encoding categorical features for XGBoost machine learning models.  Over-engineering of features can be problematic for missing or unseen codes.  Results suggest that simpler methods, in conjunction with data manipulation, may work better for changing business environments or code sets that update frequently.  

##### Topics: Python / XGBoost / Target Encoding / Categorical Feature Encoding

Read the article at [TDS](https://towardsdatascience.com/no-label-left-behind-alternative-encodings-for-hierarchical-categoricals-d1bcf00afc37/) or [Medium](https://medium.com/data-science/no-label-left-behind-alternative-encodings-for-hierarchical-categoricals-d1bcf00afc37).

#### [Exploring Hierarchical Blending in Target Encoding](https://github.com/vla6/Blog_gnn_naics)

In which I test a proposed method for encoding categorical features for machine learning models, e.g. XGBoost and neural networks, and discover tradeoffs between performance and robustness, which suggest alternative ways to approach these features.

##### Topics: Python / XGBoost / Neural Networks / Target Encoding / Deep Graph Infomax

Read the article at [TDS](https://medium.com/data-science/exploring-hierarchical-blending-in-target-encoding-fea4c59b305b) or [Medium](https://medium.com/data-science/no-label-left-behind-alternative-encodings-for-hierarchical-categoricals-d1bcf00afc37).

#### [SHAP vs. ALE for Feature Interactions: Understanding Conflicting Results](https://github.com/vla6/Blog_gnn_naics)

A deep dive into why two popular model explainability methods, SHAP and ALE, show opposite results in a public dataset.  This leads me to go on about how model "explainers" don't produce "explanations".  Instead, these methods should be viewed as diagnostic tests which must be interpreted thoughtfully.

##### Topics: Python / XGBoost / Model Explainability / SHAP / ALE

Read the article at [TDS](https://towardsdatascience.com/shap-vs-ale-for-feature-interactions-understanding-conflicting-results-ac506149f678/) or [Medium](https://medium.com/data-science/shap-vs-ale-for-feature-interactions-understanding-conflicting-results-ac506149f678).

#### [Measuring “Fairness” When Ages Differ](https://github.com/vla6/Blog_age_fairness)

A demonstration that common model fairness metrics can differ by group when the groups have different age profiles, even if everything else is the same.  I argue that metrics alone are not useful in assessing fairness, but it's necessary to understand reasons underlying the outcomes.

##### Topics: Python / Logistic Regression / Fairness Metrics

Read the article at [TDS](https://towardsdatascience.com/measuring-fairness-when-ages-differ-177d9597dd3b/) or [Medium](https://medium.com/data-science/measuring-fairness-when-ages-differ-177d9597dd3b).

#### [Feature Choice and Fairness: Less May be More](https://github.com/vla6/Stereotyping_ROCDS)

Part of a series presented at the [ROC Data Science Meetup](https://www.meetup.com/roc-data-science/).  The article argues that it's important to be extra careful with model bias / fairness when key information is missing from your models.  Relying on a bunch of weak predictors increases bias risk.

##### Topics: R / XGBoost / Random Forest / Fairness Metrics / SHAP

Read the article at [TDS](https://towardsdatascience.com/feature-choice-and-fairness-less-may-be-more-7809ec11772e/) or [Medium](https://medium.com/data-science/feature-choice-and-fairness-less-may-be-more-7809ec11772e).

#### [How to Fix Feature Bias](https://github.com/vla6/Stereotyping_ROCDS)

Part of a talk presented at the [ROC Data Science Meetup](https://www.meetup.com/roc-data-science/).  Explores some ways to mitigate feature bias which leads to unfair outcomes in a machine learning model.  

##### Topics: R / XGBoost / Random Forest / Fairness Metrics / SHAP / Feature Bias

Read the article at [TDS](https://towardsdatascience.com/how-to-fix-feature-bias-9e47abccb942/) or [Medium](https://medium.com/data-science/how-to-fix-feature-bias-9e47abccb942).

#### [No Free Lunch with Feature Bias](https://github.com/vla6/Stereotyping_ROCDS)

Part of a talk presented at the [ROC Data Science Meetup](https://www.meetup.com/roc-data-science/).  Argues that we can't assume that machine learning models will "automatically" incorporate interactions to compensate for feature bias.

##### Topics: R / XGBoost / Random Forest / Fairness Metrics / SHAP / Feature Bias

Read the article at [TDS](https://towardsdatascience.com/no-free-lunch-with-feature-bias-561c9cd3dd18/) or [Medium](https://medium.com/data-science/no-free-lunch-with-feature-bias-561c9cd3dd18).

#### [Fairness Metrics Won’t Save You from Stereotyping](https://github.com/vla6/Stereotyping_ROCDS)

Part of a talk presented at the [ROC Data Science Meetup](https://www.meetup.com/roc-data-science/).  Demonstrates that the same fairness metric results can be seen whether a model is basing its decision on a sensitive feature, or on a legitimate predictor correlated with that feature.

##### Topics: R / XGBoost / Fairness Metrics / SHAP 

Read the article at [TDS](https://towardsdatascience.com/fairness-metrics-wont-save-you-from-stereotyping-27127e220cac/) or [Medium](https://medium.com/data-science/fairness-metrics-wont-save-you-from-stereotyping-27127e220cac).


<!--
**vla6/vla6** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
