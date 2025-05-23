# PH491-Hackathon-NMR-Challenge-Regression-Prediction-of-Magnetization
The strength and shape of the interactions of nuclear spins are predicted by the output of 3 real numbers from two-channel (real and imaginary component) time-series data of magnetization.

After trying several neural network architectures, the best balance of performance and efficiency was achieved with an Adaboost algorithm with boosted decision tree learners and a high maximum depth, and a random forest with a high maximum depth. The high maximum depth likely captured the finer points of the regression and overfitting was not a severe issue with this dataset.
