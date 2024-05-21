<img width="928" alt="image" src="https://github.com/InsightEdge01/RAGGemmaModel/assets/131486782/0645d193-b59a-4809-8082-1af3aad80aa3">
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
