# Data science lab: process and methods

This repository collects all the material related to the course.

## Project

After having corrected hundreds of reports, it is easy to notice that many of you share
the same errors or things that can be improved, either on content or presentation.
Let us give you a list of things you should check before submitting.

### Checklist

Please read out the list below before submitting you report.


**Content**

- Have I described all the hyper-parameters tuned, along with their ranges?

- Are critical choices like "We use only model X", or "We drop feature Y" sufficiently justified?

- Did I use the correct wording and definitions (sentences like "the dataset distribution is low" do not make any sense)?

**Presentation and Style**

- Have I changed the provided layout (margin, font size, etc.)? If so, just undo it.

- Do all my figures and tables have a caption?

- Do all my charts have a label on all the axes?

- Have I done a full Grammarly pass?

**Other points**

- The number of estimators for a  Random Forest model is not a real hyper-parameter. Typically, it is the higher the better.

- You can user either "Figure"/"Table" or "Fig."/"Tab." in your text. But keep it consistent and avoid interchanging.

- Please call figures "Figure" and not "Chart" or "Graph".

- The SVD is not a dimensionality reduction, per se. You do dimensionality reduction by 1) doing Principal Component Analysis with Singular Value Decomposition and then 2) truncating the SVD matrix to only the top N pricipal components, corresponding to the top N singular values.

- Discuss with colleagues is fair. But avoid copying and sharing material or solutions outside of your team.
We have now trained eyes to discover when and where the underlying matter is the same.

- We don't really need the explanation of what algorithms and models do in the "Model selection" section.

- DO NOT insert screenshots, either of your code, pandas dataframes, results of any kind. Just don't do it.
