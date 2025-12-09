# Overview
This project examines how six English intensifiers (very, really, so, totally, literally, and super) change over time and across genres in the Corpus of Contemporary American English (COCA). I extract frequencies from COCA files, create a tidy dataset, run Negative Binomial regression models, and visualize the results. 

# Notes about COCA
The COCA corpus is licensed, so I did not include it in this repository. Only my processed dataset (coca_intensifiers_tidy.csv) is provided. To fully reproduce the data extraction step, you must have your own COCA copy. 

# Main Notebook
The main notebook for this project (coca_pipeline.ipynb) is located in 'code/'. It containes the full workflow, including preprocessing, analysis, and visualizations. Before running the extraction section used in the preprocessing step, you would need to update the 'BASE_DIR' path near the top of the notebook so that it points to your own COCA directory. All plots and tables created during analysis have been saved to the 'results/figures/' and 'results/tables/' folders. 

# Documentation References
I looked at common Python resources to understand specific syntax and concepts throughout this project. These sources are commented in my code, but no external code was copied, they were just used for understanding. 

# AI Disclosure 
I used ChatGPT in a few places to help with understanding syntax or getting the correct syntax for certain functions. All AI-assisted code is labeled in the notebook with comments such as '# LLM-assisted:' and everything was reviewed and edited by me to make sure I understood it. 