#git link to download the git repo for ollama app on Linux PC and for Windows and Mac download from ollama download page
git clone https://github.com/Qayam123/RAGGemmaModel.git
cd RAGGemmaModel
#run the following commands in the command line
curl -fsSL https://ollama.com/install.sh | sh
ollama pull llama3
ollama pull nomic-embed-text
#Once installed run
pip install -r requirements.txt
#Run app file
chainlit run app.py
