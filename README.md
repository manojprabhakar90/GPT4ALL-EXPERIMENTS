# GPT4ALL

This is a step by step process to get GPT4ALL working in your system. 

If you are an Unix User, you can directly use pip install nomicai

If you are a windows user, please follow the below steps.

1. Install WSL from Microsoft Store
2. Enable Virtualization in BIOS (This can be done by pressing F2 continuously). 
3. Once Ubuntu is installed in Windows system, install anaconda using wget https://repo.anaconda.com/archive/Anaconda3-2023.03-1-Linux-x86_64.sh
4. Edit the bashrc file with nano ~/.bashrc and add export PATH=/home/yourunixusername/anaconda3/bin/:$PATH
5. Use Ctrl+X and then save it. 
6. Install jupyter by pip install notebook
7. Open Jupyter Notebook using python -m notebook. 
8. Download the gpt4all model using wget https://huggingface.co/mrgaang/aira/blob/main/gpt4all-converted.bin
