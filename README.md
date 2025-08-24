# HC-XAI-using-AutoML-Paper
This repository consists the reproducible materials of the paper "Trustworthy and Human-Centered XAI using AutoML: A Rashomon Perspective on Explanation Uncertainty"

📄 Paper link: [DOI / arXiv / Journal link]

📂 Repository Structure
```
├── raw results/
│   ├── real_data_results/                 # Real dataset result files
│       ├── regression_results/...         # Regression real dataset result files
│           ├──                            # 
│           ├── ...                        
│       ├── classification_results/...     # Classification real dataset result files
│           ├──                            # 
│           ├── ...                        
│   ├── simulation_results/                # Results from simulation studies
│       ├── regression_results/...         # Regression task results
│           ├──                            # 
│           ├── ...                        
│       ├── classification_results/...     # Classification task results
│           ├──                            # 
│           ├── ...                        
│       ├── ground_truth_pdp_results/...   # Ground-truth PDP results
│           ├── regression_pdp/...         # Ground-truth PDPs for regression task
│               ├──                        # 
│               ├── ...                        
│           ├── classification_pdp/...     # Ground-truth PDPs for classification task
│               ├──                        # 
│               ├── ...                        
│
├── scripts/
│   ├── 01_simulation.R          # Simulation study code
│   ├── 02_real_data_analysis.R  # Real data analysis code
│   ├── 03_tables_figures.R      # Code to reproduce tables and figures
│
├── outputs/
│   ├── tables/                  # Reproduced tables from the paper
│   ├── figures/                 # Reproduced figures from the paper
│
├── README.md                    # This file
```
🚀 How to Use

Clone the repository:

git clone https://github.com/username/repo-name.git
cd repo-name


Restore the R environment with renv:

install.packages("renv")
renv::restore()


Run the scripts to reproduce the results:

source("scripts/01_simulation.R")
source("scripts/02_real_data_analysis.R")
source("scripts/03_tables_figures.R")

📊 Contents

Simulation studies: Results for different parameter settings are stored in simulation_results.rds.

Real data application: Analysis of the real dataset is stored in real_data.rds.

Tables and figures: All tables and figures from the paper can be reproduced by running scripts/03_tables_figures.R.

🔎 Reproducibility Notes

Code has been tested on R (>=4.3.0).

Package dependencies are listed in renv.lock.

Randomness in simulations is controlled by fixed seed values (set.seed()).

📜 License
This repository is released under the MIT License
.

Code can be freely used and adapted.

Data files are provided for research purposes only.

✨ Contact

For questions, please contact:

Author Name – [email@example.com
]

Or open an issue on GitHub.
