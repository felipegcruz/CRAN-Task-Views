# CRAN Task Views

CRAN task views aim to provide guidance on which packages on CRAN are relevant for tasks related to a certain topic. They give a brief overview of the included packages, which can also be automatically installed using the ctv package. The views are intended to have a sharp focus so that it is sufficiently clear which packages should be included (or excluded) - and they are not meant to endorse the "best" packages for a given task.

To automatically install the views, the ctv package needs to be installed, e.g., via:

```
install.packages("ctv")
```

Then the views can be installed via `install.views` or `update.views` (where the latter only installs those packages that are not installed and up-to-date), e.g.,

```
ctv::install.views("Econometrics")
ctv::update.views("Econometrics")
```

To query information about a particular task view on CRAN from within R or to obtain the list of all task views available, respectively, the following commands are provided:

```
ctv::ctv("Econometrics")
ctv::available.views()
```

The resources available from the CRAN Task View Initiative provide further information on how to contribute to existing task views and how to propose new task views.

For more information and to access the CRAN Task Views website, visit: [CRAN Task Views](https://cran.r-project.org/web/views/)

## Topics

- [Agriculture](https://cran.r-project.org/web/views/Agriculture.html): Agricultural Science
- [Bayesian](https://cran.r-project.org/web/views/Bayesian.html): Bayesian Inference
- [CausalInference](https://cran.r-project.org/web/views/CausalInference.html): Causal Inference
- [ChemPhys](https://cran.r-project.org/web/views/ChemPhys.html): Chemometrics and Computational Physics
- [ClinicalTrials](https://cran.r-project.org/web/views/ClinicalTrials.html): Clinical Trial Design, Monitoring, and Analysis
- [Cluster](https://cran.r-project.org/web/views/Cluster.html): Cluster Analysis & Finite Mixture Models
- [Databases](https://cran.r-project.org/web/views/Databases.html): Databases with R
- [DifferentialEquations](https://cran.r-project.org/web/views/DifferentialEquations.html): Differential Equations
- [Distributions](https://cran.r-project.org/web/views/Distributions.html): Probability Distributions
- [Econometrics](https://cran.r-project.org/web/views/Econometrics.html): Econometrics
- [Environmetrics](https://cran.r-project.org/web/views/Environmetrics.html): Analysis of Ecological and Environmental Data
- [Epidemiology](https://cran.r-project.org/web/views/Epidemiology.html): Epidemiology
- [ExperimentalDesign](https://cran.r-project.org/web/views/ExperimentalDesign.html): Design of Experiments (DoE) & Analysis of Experimental Data
- [ExtremeValue](https://cran.r-project.org/web/views/ExtremeValue.html): Extreme Value Analysis
- [Finance](https://cran.r-project.org/web/views/Finance.html): Empirical Finance
- [FunctionalData](https://cran.r-project.org/web/views/FunctionalData.html): Functional Data Analysis
- [GraphicalModels](https://cran.r-project.org/web/views/GraphicalModels.html): Graphical Models
- [HighPerformanceComputing](https://cran.r-project.org/web/views/HighPerformanceComputing.html): High-Performance and Parallel Computing with R
- [Hydrology](https://cran.r-project.org/web/views/Hydrology.html): Hydrological Data and Modeling
- [MachineLearning](https://cran.r-project.org/web/views/MachineLearning.html): Machine Learning & Statistical Learning
- [MedicalImaging](https://cran.r-project.org/web/views/MedicalImaging.html): Medical Image Analysis
- [MetaAnalysis](https://cran.r-project.org/web/views/MetaAnalysis.html): Meta-Analysis
- [MissingData](https://cran.r-project.org/web/views/MissingData.html): Missing Data
- [MixedModels](https://cran.r-project.org/web/views/MixedModels.html): Mixed, Multilevel, and Hierarchical Models in R
- [ModelDeployment](https://cran.r-project.org/web/views/ModelDeployment.html): Model Deployment with R
- [NaturalLanguageProcessing](https://cran.r-project.org/web/views/NaturalLanguageProcessing.html): Natural Language Processing
- [NumericalMathematics](https://cran.r-project.org/web/views/NumericalMathematics.html): Numerical Mathematics
- [OfficialStatistics](https://cran.r-project.org/web/views/OfficialStatistics.html): Official Statistics & Survey Statistics
- [Omics](https://cran.r-project.org/web/views/Omics.html): Genomics, Proteomics, Metabolomics, Transcriptomics, and Other Omics
- [Optimization](https://cran.r-project.org/web/views/Optimization.html): Optimization and Mathematical Programming
- [Pharmacokinetics](https://cran.r-project.org/web/views/Pharmacokinetics.html): Analysis of Pharmacokinetic Data
- [Phylogenetics](https://cran.r-project.org/web/views/Phylogenetics.html): Phylogenetics
- [Psychometrics](https://cran.r-project.org/web/views/Psychometrics.html): Psychometric Models and Methods
- [ReproducibleResearch](https://cran.r-project.org/web/views/ReproducibleResearch.html): Reproducible Research
- [Robust](https://cran.r-project.org/web/views/Robust.html): Robust Statistical Methods
- [Spatial](https://cran.r-project.org/web/views/Spatial.html): Analysis of Spatial Data
- [SpatioTemporal](https://cran.r-project.org/web/views/SpatioTemporal.html): Handling and Analyzing Spatio-Temporal Data
- [SportsAnalytics](https://cran.r-project.org/web/views/SportsAnalytics.html): Sports Analytics
- [Survival](https://cran.r-project.org/web/views/Survival.html): Survival Analysis
- [TeachingStatistics](https://cran.r-project.org/web/views/TeachingStatistics.html): Teaching Statistics
- [TimeSeries](https://cran.r-project.org/web/views/TimeSeries.html): Time Series Analysis
- [Tracking](https://cran.r-project.org/web/views/Tracking.html): Processing and Analysis of Tracking Data
- [WebTechnologies](https://cran.r-project.org/web/views/WebTechnologies.html): Web Technologies and Services

