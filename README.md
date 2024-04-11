# RAG Demo

This is a fast and easy python notebook to understand how to implement RAG. It uses a chromadb and watsonx.ai, to output results directly in the notebook.

# Pre-reqs
Create a virtual environment:

with conda, the command is - ```conda create --name yourenvname```

Activate the virtual env - ```conda activate yourenvname```

do a ```pip install -r requirements.txt``` with the environment active

You will need an IBM cloud account with access to watsonx.ai, and you'll need to grab credentials and put them into a .env file in the same directory as your notebook.

#### Project ID
From your watsonx.ai project home page, go to the manage tab > general > the project ID will be listed under the details section.

#### API Key
Go to your IBM cloud account, and navigate to the IAM section under manage. Click on "API Keys" on the left-side, and generate an API key. Copy this key into your .env

#### Serving URL
Your ibm cloud region url.

If you need more help setting up credentials, check out the official [IBM documentation](https://dataplatform.cloud.ibm.com/docs/content/wsj/analyze-data/fm-credentials.html?context=wx&audience=wdp)

# Usage
Execute the cells to see how it all works.
