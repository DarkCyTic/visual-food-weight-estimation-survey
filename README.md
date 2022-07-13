# Visual Food Weight Estimation Survey

Dear researcher, welcome to the Visual Food Weight Estimation Survey repository! This repository contains a dataset exploring people's ability to visually estimate food weight. The aim of the survey is to understand more about the factors that impact the human estimation accuracy. Participants were given 15 random images containing food waste and were tasked with estimating the weight of the presented food waste.

The features we have collected during the survey are:
* **submissionId**: An ID to identify entries which come from the same submission
* **pictureId**: Picture identifier
* **weightEstimation**: Weight estimation in grams
* **userType**: What type of user submitted the estimations, e.g. food company employee
* **foodRecognised**: Whether the user recognises the food or not
* **containerRecognised**: Whether the user recognises the food container or not
* **duration**: The time (in ms) the user took to estimate the weight
* **submissionDatetime**: The datetime when the submission was posted

Here, you can find the following files and folders:

* **images/**: Folder containing all the survey food images. These are dummy images because the original ones are not publicly available. If you need access to the original images, please contact the author of this repository!
* **survey_dataset.csv**: CSV file containing the ground-truth weight for each food image
* **survey_results.csv**: CSV file containing collected survey results
* **survey_analysis.ipynb**: Jupyter notebook containing pre-processing and analysis of the survey results
* **requirements.txt**: Virtualenv requirements.txt file containing the dependencies of **survey_analysis.ipynb**.

## Reproduction
To reproduce the analysis, run the following steps:

1. Clone repository: `git clone git@github.com:DarkCyTic/visual-food-weight-estimation-survey.git`
2. Make sure you are in the repository's root directory.
3. Create a new virtualenv: `python3 -m venv venv`
4. Activate the newly created virtualenv: `source ./venv/bin/activate`
5. Install dependencies: `pip3 install -r requirements.txt`
6. Open the **survey_analysis.ipynb** with Jupyter.
7. Enjoy!
