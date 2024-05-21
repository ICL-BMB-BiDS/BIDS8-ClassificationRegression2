# Classification and Regression 2
This session revolves around what kernels are, why they are used in supervised learning, and how they are used with Support Vector Machines (SVMs) for classification (SVC) and regression (SVR).

Some help with getting the feature importance of a non-linear SVM: https://stackoverflow.com/a/67910281
For a non-linear kernel the `coef_` attribute does not exist, so we need a workaround (see lecture notes for other approaches for RFE with non-linear kernels).

If you get an empty row for the seaborn confusion matrix plot (heatmap), see this solution (update seaborn): https://stackoverflow.com/a/77231620
