# TASK A (Churn Classification)

I picked task A because it's more interesting to work with Clockify data and it better maches my skills. 

Task was completed in Python and everything is contained in the [analysis notebook](analysis.ipynb).

Notebook ran on Python 3.11.4 on Ubuntu 23.04 with libraries specified in [requirements.txt](requirements.txt).

**Goal**: well-balanced classification model

**Outcome**: Logistic regression classification model to predict churned accounts. The model achieves 0.72 accuracy, 0.52 precision and F1 score of 0.63. Cross-validation mean score is 0.72 and AUC is 0.79.

Overall, the model performs moderately well. It's better at predicting the majority class (active accounts) than the minority class (churned accounts). This is also reflected in the feature importance ranking.

**Time** ~ 5h20m

![image](https://github.com/atomashevic/data-experiment-task/assets/39856297/32217f97-96ca-46b0-8c3d-10bb8c016688)

Auto-tracking using Clockify for Linux (2.1.0-296).

---

> At its core, churn prediction is a classification problem, where the classes often are ‘churned’ and ‘active’. The prediction is based on historical data, including customer behavior, demographics, transaction history, and more.

> **Goal**: well-balanced classification model.

> **Instructions:**

> - Work in Python or R.
> - Examine the data.
> - While working through the layers of challenge, please leave comments in your code.
> - Share your solution in a notebook format with us.
  
> **Deliverables:**

> - .ipynb or .R

> **Rules:**

> We understand your time is precious and would not want you to spend more than 6 to 8 hours on this over the span of one week max.

> **Evaluation:**

> Please send an email with your repository solution. It will be assessed based on:

> - Your applied statistics knowledge
> - Python or R proficiency
> - Your SaaS domain knowledge

