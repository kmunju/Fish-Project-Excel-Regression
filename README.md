# Fish-Project-Excel-Regression

Purpose


The purpose of this project was to predict weight estimate of fish using data regression model on
a given data.
Explanation of Data and Consideration
Given data contains a spreadsheet with collection of observation of fish identified by its
observation number, type of species, weight in grams, lengths measured in cm of 3 different
alignments, maximum height in percent, and width measured in percent, both based of
measurement “Length 3”, and sex of fish observed. The models are created within the limit of this
dataset (appending #I-1).


Method


The method of this project is divided into 3 major stages: Data Preparation and Preliminary stage,
Experiment and Result stage, and Extraction and Conclusion stage. Methods of each stages are
referred to appendix #P through #C.


Results & Conclusion


As a result of numerous trials, we have concluded that Model 3 is the best regression model to
predict the weight of fish with given data (appending #E-S1 to #E-S5):
The following is the full model with coefficients included which represents interaction of species
with x variables ln(length3), ln(height), and ln(width):
μ lnY = -3.0187 + 0.25132 species2 + 0.12198 species3 + 0.14526 species4 + -0.018313 species5
+ 0.068802 species6 + 0.22824 species7 + 1.8498 ln(length3) + 0.65479 ln(height) + 0.52604
ln(width) + 147
Here, we assume Y variable will be converted back to original value with eln(weight) function after
utilizing the model to predict ln(weight) variable. As you can see in the model, x variables of
length1 and length2 were removed from the model due to its insignificance (appending #E-S3,
#E-S4 respectively).
We concluded that Model 3 was the best fit model compared to the other regression model trials
and the closest fit to our initial assumption of ideal way in predicting weight using only given data.
Viewer should consider the outer environment and potential sample bias that may possibly
incorporate error (appending #C-1 through #C-4).
