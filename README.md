# Revealing Relevant Factors that Prompt Gendered Language in Job Descriptions

Gender impacts the candidate journey, or the process job seekers go through. 
Companies can influence candidate journeys in order to attract a certain crowd of job seekers. 
However, companies can inadvertently discriminate candidates before they even apply for the job 
because of their use of gendered language in their job descriptions. Gendered language refers to 
language that has a bias towards a specific sex and stereotypically assigns nouns and sometimes 
adjectives to distinct sex-based categories, masculine and feminine. 
In this project, we aim to discover if gendered language used in job descriptions vary by 
job salary, location, and company size. This project is a part of Georgia Tech's CSE6240 in the Spring semester of 2020.

_IMPORTANT: This repository only features my contributions to this project. 
Some implementations mentioned will not be included in this repository._



## Project Folder Overview
The root directory for the project called `Gendered_Language_Study` has the environment setup files, project presentation, and report. 
The `data/` folder 
**must** be separately downloaded before running any code (see `Prerequisites` section below for instructions).

```
Gendered_Language_Study
├── job_locations_ANOVA.ipynb
├── data
│   └── Final_Data.csv
├── environment.yml
├── presentation.pdf
├── README.md
└── report.pdf
```



## Prerequisites
### Set Up Environment
1. Install [Miniconda](https://docs.conda.io/en/latest/miniconda.html).
It doesn’t matter whether you use Python 2 or 3 because our environment will use Python 3.
If you already have Miniconda or Anaconda installed, please skip to step 2.

2. Create a conda environment using the appropriate command. On Windows, open the installed **Conda
prompt** to run the command. On MacOS and Linux, you can just use a terminal window to run the
command. Run the following command: ```conda env create -f environment.yml```. 
This should create an environment named ```cse6240-git```.

3.  Activate the `cse6240-git` conda environment using the Windows command,
``` conda activate cse6240-git```, **OR** the macOS/Linux command, ```source activate cse6240-git```

### Get Data
The dataset is ~1 GB and should not take a long time to download and unzip.
1. Download [data.zip](https://gtvault-my.sharepoint.com/:u:/g/personal/mjones386_gatech_edu/ETLfX-7LVx9LglOfAwuZbjIBiSXEAVr4qNdiaFMf6YkKZQ?e=4BdCbN)
2. Unizp `data.zip`. Once unzipped, the `data/` folder should contain this structure:
    ```
    data
    └── Final_Data.csv
    ```
3. Place the `data/` folder inside the `Gendered_Language_Study` folder. 
Please make sure you adhere to the project folder structure above.



## Run Codebase
### Analyzing Gendered Language Based on Job Location
For our second experiment, we explore if job location influences the use of gendered language in job descriptions.
In the Conda prompt/terminal, activate the ```cse6240-git``` environment if not done so already. 
Navigate to the ```Gendered_Language_Study``` folder in the prompt/terminal then run the command below.
```
jupyter notebook ./job_locations_ANOVA.ipynb
```
Alternatively, you can run ```job_locations_ANOVA.ipynb``` using Google Colab or anything related.



##Contact Information
Miasia Jones ~ miasiajones1@gmail.com