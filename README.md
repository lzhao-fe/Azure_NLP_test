# Azure_NLP_test

Here is a collection of demos for using Azure OpenAI services (useful documentation (here)[https://learn.microsoft.com/en-us/azure/ai-services/openai/]).

We use the existing (NLP-exploration instance)[https://portal.azure.com/#@fegamma.com/resource/subscriptions/1c2256ae-339e-4689-ab4c-b5023dc00d9d/resourceGroups/rg-aistudio-dev-001/providers/Microsoft.CognitiveServices/accounts/NLP-exploration/overview] (under FEGamma account) for illustration.

This repo is built with python 3.12.

Note that due to Azure service updates, demos might fail. If that happens, please contact the repo maintainer.


### Setup
* Contact IT to get access to the required resource (set up a FEGamma account and get the right role assigned)
* Clone this repo to a local folder
* Create a virtual environment called ".venv" under the same folder.
* Install dependencise in requirements.txt. 
* Deposite a ".env" file under the ".venv" folder. The ".env" file should contain below arguments (see the example 00_env_example.env). See (here)[https://learn.microsoft.com/en-us/azure/ai-services/openai/quickstart?tabs=command-line%2Cjavascript-keyless%2Ctypescript-keyless%2Cpython-new&pivots=programming-language-studio] for where to get those arguments from Azure portal.
    * AZURE_OPENAI_API_KEY
    * AZURE_OPENAI_ENDPOINT
* Try to run a demo notebook and test


### Folder structure

After completing the setup, your local folder should look like below

```
Azure_NLP_test/
├── .venv/
│   ├── <all virtual env folders>
│   └── .env
│ 
├── .gitignore
├── <demo notebooks and files>
├── ...
├── README.md
└── requirements.txt
```