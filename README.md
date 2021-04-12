# ctDNA-dynamic-prediction-lung-cancer
Reference scripts for study 'Circulating tumor DNA as markers of dynamic recurrence risk and adjuvant chemotherapy benefit in resected non-small cell lung cancer'

## run 
All analysis are running under R version 4.0.2

load_requred_package.R -- To install packages used in this analysis.

run_joint_model_analysis.R -- To run the model construction and evaluation analysis.

run_survival_analysis.R -- To run the main survuval analysis in the study.

## data
Joint_model_data.csv -- data used for model construction and evaluation.

splits.RDS, split.AD.RDS -- splits for cross validation used in the study.

Survival_analysis_data.csv -- data used for survival analysis.

## functions
cross_validation.R -- To construct and evaluate joint model and Cox models by cross validation.
plot_evaluation.R -- To visualize the results of cross validation.
leaveoneout.R -- To construct and evaluate joint model and Cox models by leave one out cross validation.
reliability_diagram.R -- To apply the Hosmer-Lemeshow (H-L) test and draw the reliability diagrams.
get_survival_plot.R -- To draw the customized Kaplan Meier plot.
