# OpenAI-Starter-Codes

## Introduction

This repository contains starter codes and examples to help you get up and running with OpenAI technologies.

- **PDF_data_loading:** This folder features a Jupyter Notebook that demonstrates how to load PDF files (sample files stored in `data` folder) into an Azure Cognitive Search index using LangChain.
- **Testing_using_AdaTest:** This folder contains a Jupyter Notebook that shows how to use [AdaTest](https://github.com/microsoft/adatest) for finding bugs or low-quality answers in QA use case. AdaTest is developed by Microsoft Research, and more details can be found in the official repository: [https://github.com/microsoft/adatest](https://github.com/microsoft/adatest). The folder `Testing_using_AdaTest` contains AdaTest with few minor updates to adopt it to Azure OpenAI and gpt-3.5-turbo.


## Installation

If you are using a local development environment, please follow steps below:

1. Clone this repository:
```
git clone https://github.com/LianaN/OpenAI-Starter-Codes.git
```

2.Navigate to the starter code directory, for example:
```
cd PDF_DATA_LOADING
```

3. Create .env file in the starter code folder (e.g. in `PDF_DATA_LOADING` folder). In the .env file specify all the environmental variables that are used in a notebook that you are going to run.

example of .env file

```
AZURE_SEARCH_SERVICE_ENDPOINT=<url, FROM portal -> overvire -> url>
AZURE_SEARCH_INDEX_NAME=demo
AZURE_SEARCH_ADMIN_KEY=<key, from portal -> OpenAI resource -> Keys -> Primary admin key>

OPENAI_API_KEY=<key, from portal -> OpenAI resource -> Keys and Endpoint -> -> KEY 1>
OPENAI_API_BASE=<url, from portal -> OpenAI resource -> Keys and Endpoint -> Endpoint>
OPENAI_API_VERSION=2023-05-15
```

4. Create a new Python virtual environment:
```
python -m venv venv
source venv/bin/activate
```

5. Install the required packages:
```
pip install -r requirements.txt
```

6. Launch your preferred IDE to access the notebooks (recommended Python version: 3.10.11)
