# Automatic-Scoring-of-the-Test-des-Deux-Barrages-T2B

Paper-pencil tests are essential tools in neuropsychology to quantify effects of a disease on cognitive performance. The evaluation of these tests is mostly done manually, which is time-consuming and prone to errors. This thesis proposes an automatic scoring system for the Test des Deux Barrages, a selective attention test regularly used in Switzerland. The goal of the thesis was to investigate the number of errors made in the evaluation and to develop a scoring system that would deliver results similar to the manual evaluation by clinical experts. 
For this purpose, 23 filled-out test sheets and their evaluations by clinical experts were collected. The clinical evaluations were examined for errors using the ground truth of the patients. The collected test sheets were split into individual symbols and the symbols classified as marked by the patient or not based on their grayscale values. Three models were developed for binary classification. The performance of the models was evaluated on various performance metrics (balanced accuracy, F1 measure, sensitivity and specificity) and compared to the performance of clinical experts using the sign test and Wilcoxon signed-rank test.

# Overview:

In this repository you can find:
- the data used in this thesis (see 'Data')
- the script used for performance analysis (see 'Performance Analysis')
- the script used for statistical tests (see 'Statistical Tests')
- the script used to plot figures (see 'Plots')
- a script to convert .pdf files to images
- a script that scores the T2B automatically and visualizes errors
- the Master thesis

# How to navigate:

Folders were specifically created: Scripts within a folder use the files within the folder. Please use the files that were included in the same folder to ensure that the scripts run correctly. Tkinter windows will pop up when running the code, prompting to select files. The window titles will specify which files to choose.


