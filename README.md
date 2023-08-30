# ConfidentialityAnalysis-ScalibilityEvaluation
This repository contains the scalibility setup used in [this research paper](https://publikationen.bibliothek.kit.edu/1000161187).
The analysis can be found [here](https://github.com/PalladioSimulator/Palladio-Addons-DataFlowConfidentiality-Analysis)

## Installation and Results
The repository contains three major bundles.
The `scalibility.new` bundle contains the code needed to run the Java-based analysis.
To run the scalibility evaluation, please follow the Installation guide in the repository of the analysis first.
After that you can run the Java Application contained in the bundle.

The `scalibility.old` bundles contain the code needed to run the Prolog-based analysis.
To run this scalibility evaluation, you need to download an old installation of eclipse from [here](https://fluidtrust.github.io/tutorial-ecsa2021/material/).
Afterwards, install the dependencies in `oldAnalysis.p2f` and install a Prolog interpreter.
Then you should be able to run the Java Application contained in the base bundle.

The `scalibility.common` bundle contains common code that is shared between the evaluation of the new and old analysis.
Lastly, the testmodels used in the evaluation will be generated into `scalibility.testmodels`.

Results of the analysis will be created into a `results` folder at the root of the project.
Before running the analysis, please make sure to adjust the static paths present in the bundels. 
