# LLM Citations
Improving the ability of LLMs to use citations. Work done as part of Stanford CS329T, Fall 2023.
Trustworthy Machine Learning: Large Language Models and their Applications.

# Setup

## Create Conda Environment
```
conda create --name llm_citations --file requirements.txt
conda activate llm_citations
```

## Download data in the ALCE project
Note that this repository contains the ALCE project: https://github.com/princeton-nlp/ALCE

Within the ALCE directory, make sure to run:
```
bash download_data.sh
```

You shouldn't need to run this command, but as an FYI, this project was added as a submodule using:
```
git submodule add git@github.com:princeton-nlp/ALCE.git ALCE
```
