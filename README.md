**TOPSIS Analysis for Pretrained Models in Text Conversational Tasks**

This repository contains Python code to perform TOPSIS (Technique for Order of Preference by Similarity to Ideal Solution) analysis to evaluate pretrained models for text conversational tasks. TOPSIS is a multi-criteria decision-making method that helps in selecting the best alternative from a set of options based on their performance against multiple criteria.

**How to Use**

**Follow these steps to use the provided code:**

**Clone the Repository:** Clone this repository to your local machine using the following command:

_git clone https://github.com/Tanishq2003be/Topsis-on-pretrained-model.git_

**Install Dependencies:** Ensure you have Python installed on your machine. Install the required dependencies using pip:

_pip install numpy matplotlib_

**Define Criteria and Models:**

Open the topsis.py file and define the criteria and models for evaluation. Criteria represent the factors to consider when evaluating the models (e.g., naturalness, coherence, efficiency), while models represent the pretrained models under consideration.

**Enter Performance Data:**

Enter the performance data for each model with respect to each criterion in the decision matrix. The rows represent models, and the columns represent criteria.

**Specify Weights:**

Define the weights for each criterion based on their relative importance. The weights should sum up to 1.

**Run the Analysis: **

Execute the TOPSIS analysis by running the topsis.py script:

_python topsis.py_

**View Results:**

After running the analysis, the script will output the TOPSIS scores for each model and identify the best-performing model. Additionally, a visualization will be displayed showing the TOPSIS scores for all models.

**Files Included**

topsis.py: Python script containing the implementation of TOPSIS analysis.
README.md: This file containing instructions and information about the repository.

**Requirements**

Python 3.x
NumPy
Matplotlib
