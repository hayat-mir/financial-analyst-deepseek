### **Financial Analyst with CrewAI and DeepSeek using SambaNova**

This project implements a Financial Analyst with CrewAI and DeepSeek using SambaNova.

[SambaNova](https://cloud.sambanova.ai/?utm_source=freeman-forrest&utm_medium=x&utm_campaign=sambanova-february&utm_term=dailydosedatascience&utm_content=deepseek) is used to as the inference engine to run the DeepSeek model.
CrewAI is used to analyze the user query and generate a summary.
Streamlit is used to create a web interface for the project.
Setup and installations
Get [SambaNova](https://cloud.sambanova.ai/?utm_source=freeman-forrest&utm_medium=x&utm_campaign=sambanova-february&utm_term=dailydosedatascience&utm_content=deepseek) API Key:

Go to [SambaNova](https://cloud.sambanova.ai/?utm_source=freeman-forrest&utm_medium=x&utm_campaign=sambanova-february&utm_term=dailydosedatascience&utm_content=deepseek) and sign up for an account.
Once you have an account, go to the API Key page and copy your API key.
Paste your API key by creating a .env file as shown below:
SAMBANOVA_API_KEY=your_api_key

Install Dependencies: Ensure you have Python 3.11 or later installed.

pip install streamlit openai crewai crewai-tools
