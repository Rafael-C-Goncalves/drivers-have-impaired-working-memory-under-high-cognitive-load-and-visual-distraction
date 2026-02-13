# Drivers have impaired working memory under high cognitive load and visual distraction: Safety Implications for transitions of control from vehicle automation
This repository contains the code and data for the paper:  "Drivers have impaired working memory under high cognitive load and visual distraction: Safety Implications for transitions of control from vehicle automation".

## Data
The data is devided in two files, for different analyses:\
-The gaze dispersion and reaction time analysis data can be found in the file "dispersion_and_reaction_data.xlsx".\
-The Markov chain analysis data can be found in the file "markov_chain_data.xlsx".

## Analysis codes
As with the datasets, the analysis was divided into two Python notebook files, one for each analysis.\
The "Gaze_Dispersion_and_Reaction_Time_Analysis.ipynb" file contains the code used to generate the results reported in sections 3.1 and 3.3 of the manuscript, as well as the analysis code of the gaze dispersion of the occlusion periods, not reported in the main body of the text.\
The "Markov_Chain_Analysis.ipynb" file contains the code used to generate the results reported in section 3.2 of the manuscript, as well as the non-significant results for the Markov Chain analysis, excluded from the main body of the text.

## Usage
Please download both dataset files and edit the root folder in the analysis code before running. A comment was provided to guide the user on where to alter the code.\
The analysis code files contain the preloaded results reported in the manuscript. Keep in mind that any attempt to rerun the analysis may lead to slight variations in the results due to the probabilistic nature of Monte Carlo simulations used to generate the model predictions. However, this variation should not lead to any substantial differences or effects and will not affect the interpretation of the observed results.\
Should any queries arise or any assistance be needed, please contact the corresponding author (Dr.Rafael C. Gonçalves) at the email: trarg@leeds.ac.uk.

## Project structure

```text
├── Data
│   ├── dispersion_and_reaction_data.xlsx
│   └── markov_chain_data.xlsx
├── Analysis Codes
│   ├── Markov_Chain_Analysis.ipynb
│   └── Gaze_Dispersion_and_Reaction_Time_Analysis.ipynb
└── README.md
```

## Acknowledgements and ethics approval
The data used in this project were originally collected as part of the "University of Leeds and Seeing Machines Ltd. Collaboration Fellowship". \
The experiment received ethical approval from the University’s Research Ethics Committee (Approval Number: FREC 2023-0487-560). 
