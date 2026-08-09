# UV install ation steps for Windows

1. Create a folder

2. uv package installer
	powershell -ExecutionPolicy ByPass -c "irm https://astral.sh/uv/install.ps1 | iex"

3. uv init

4. uv --version

5. uv venv

6. Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser

7.  .\.venv\Scripts\activate

8. virtual environment is created with (folder_name)

# UV installation in Mac

1. Create a folder
2. UV package installer
        curl -LsSf https://astral.sh/uv/install.sh | sh
3. Uv init
4. Uv —version
5. Uv venv
6. Source .venv/bin/activate —> it activate the virtual environment with (folder name)


# Git commands to push the code in github

1. git init
2. git add .
3. git commit -m "first commit"
4. git branch -M main
5. git git remote add origin https://github.com/AIAGENTGURUSHANTHA/GURU_GENAI_LEARN.git
6. git push -u origin main

Code from MAC

code from windows

# To Run the .ipynb file in windows and MAC both
* install ipykernel and pip package

# Requirements file
* Windows -> Create requirements.txt file
* MAC: -> touch requirements.txt


Add the below complete list in the file
langchain
langchain_community
langchain-openai
langchain-groq
python-dotenv
langchain-google-genai
ipykernel
pandas
python-dotenv
ipykernel
ipywidgets
requests
numpy
pandas
scipy
scikit-learn
matplotlib
torch
transformers
tqdm
openai
gradio
langchain
langchain-core
langchain-text-splitters
langchain-openai
langchain-chroma
langchain-community
datasets==3.6.0
google-generativeai
anthropic
chromadb
plotly
jupyter-dash
beautifulsoup4
pydub
modal
ollama
psutil
setuptools
speedtest-cli
sentence_transformers
feedparser
protobuf==3.20.2
wandb
jupyterlab
gradio
langchain_huggingface
litellm

*** Run the command to install all the dependecies from requirements.txt
uv add -r requirements.txt
