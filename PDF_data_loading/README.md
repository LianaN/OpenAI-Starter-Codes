##Installation

If you are using a local development environment, please follow steps below:

1. Clone this repository:
```
git clone https://github.com/LianaN/OpenAI-Starter-Codes.git
```

2.Navigate to the project directory:
```
cd PDF_DATA_LOADING
```

3. Create .env file in the folder `PDF_DATA_LOADING`. In the .env file specify all the environmental variables that are used in the `data_loading.ipynb` notebook.

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