# Azure AI-900 Model Deployment



A hands-on project demonstrating model deployment and inference using Azure AI Foundry, built as part of the Microsoft Azure AI Fundamentals (AI-900) certification journey.



## 📋 Overview



This notebook connects to a model deployed on Azure AI Foundry and sends chat completion requests using the OpenAI-compatible SDK. It demonstrates how to interact with cloud-hosted AI models through Azure's inference endpoint.



## 🛠️ Tech Stack



| Component | Technology |

|---|---|

| Language | Python |

| Model Hosting | Azure AI Foundry |

| Model | Phi-4-mini-reasoning |

| SDK | OpenAI Python SDK (Azure-compatible endpoint) |

| Config Management | python-dotenv |

| Environment | Jupyter Notebook |



## ⚙️ How It Works



1. The notebook connects to a model endpoint hosted on Azure AI Foundry.

2. Using the OpenAI-compatible client, it sends a chat completion request to the deployed model.

3. The model (Phi-4-mini-reasoning) processes the request in the cloud and returns a response.

4. API credentials are loaded securely from environment variables, keeping secrets out of the codebase.



## 🖥️ Run Locally



Clone the repository:



```bash

git clone https://github.com/osamag13/Azure-AI901-Model-Deployment.git

cd Azure-AI901-Model-Deployment

```



Install dependencies:



```bash

pip install -r requirements.txt

```



Add your Azure AI key:



Create a `.env` file in the root directory and add:



AZURE\_AI\_KEY=your\_azure\_key\_here



Run the notebook:



```bash

jupyter notebook "Model\_Deploy-Osama Ghafoor.ipynb"

```



## 📚 What I Learned



- Deploying and calling models hosted on Azure AI Foundry

- Using the OpenAI-compatible SDK to interact with Azure-hosted endpoints

- Secure credential management using environment variables

- Practical, hands-on application of concepts covered in the AI-900 certification



## 📄 License



This project is open source and available for anyone to learn from and build upon.



---



Built by \[Osama](https://github.com/osamag13) as part of Azure AI-900 certification preparation.

