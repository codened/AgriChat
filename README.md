# Llama2-AgriChatBot

Hi there, 👋  This is a powerful AgriChat bot designed to help you ask queries related to any kind of agriculture-related problems. This Agri bot was built using Llama2 and sentence-transformers. The Front end of the bot is powered by Langchain and Chainlit.

## How to run?
1. Download and save the llama2 model in the project folder[ ](https://huggingface.co/TheBloke/Llama...)(6.6GB)
2. Download "knowledgebase.pdf" and save it in the "/data" folder. Link for knowledgebase https://drive.google.com/drive/folders/1YZf0bZScN5GOEjzRIsDDSoMDIf6AayrP?usp=sharing
3. install all necessary packages
4. conda activate langchain
5. python ingest.py 
6. langchain run model.py -w

## Note:
The bot runs on a decent CPU machine with a minimum of 16GB of RAM.

## Useful Links 🔗
Llama 2 Model (Quantized one by the Bloke): https://huggingface.co/TheBloke/Llama...
Llama 2 HF Model (Original One): https://huggingface.co/meta-llama
Chainlit docs: https://github.com/Chainlit/chainlit
Faiss GitHub: https://github.com/facebookresearch/f...
Langchain Docs: https://python.langchain.com/docs/get...
Sentence Transformers Hugging Face: https://huggingface.co/sentence-trans...
CTransformers GitHub: https://github.com/marella/ctransformers
