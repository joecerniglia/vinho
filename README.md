# Wines of the vinho verde region of Portugal
In 2009, four researchers from Portugal published a [paper](https://www.sciencedirect.com/science/article/abs/pii/S0167923609001377) in which they reported their results of the use of machine learning algorithms in R to model the preferences of professional wine-tasters for wines from the vinho verde region. Because of the differences between red and white wines, the authors split their data into separate datasets, which may be found [here](https://archive.ics.uci.edu/ml/datasets/wine+quality) at the website of the UCI Data Repository. The intent of the study was to use machine learning to assist in the certification process of professional testers and to help stratify premium wines for price-setting purposes.

Although the problem is one of classification, the authors found that SVM, a regression algorithm, outperformed the classification algorithm of Neural Networks. Thus, they chose SVM as their favored model for vinho verde wine modeling.

In selecting my first machine learning project, I wanted a topic that was not inherently controversial, not subject to privacy or data protection concerns, had popular appeal, and most importantly, would encourage experimentation and courage in spite of possible error on my part.

My project has two objectives:

1. To the extent possible, attempt to duplicate the regression result of the study authors, using Python machine learning libraries.
2. Using classification methods such as decision trees, determine whether the precision and recall achieved by the original study may be improved.

The code in this notebook may be used to evaluate either white wine or red wine. For this study, I have chosen to focus on white wine because it is the more robust of the two datasets, and because, as the paper authors relate, white vinho verde wine is the more predominant Portuguese export. Also, because the notebook takes several minutes to run to completion, it seemed appropriate to choose a single wine varietal for the models to evaluate, rather than require that they evaluate them both.

Note also that because the models are stochastic in nature, results will vary by small amounts each time the notebook is run.
