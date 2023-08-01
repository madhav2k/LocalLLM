# LocalLLM
Experiments with LLM running locally on my own data. 

The goal of this project is to create an LLM which can run locally on a decent-sized laptop (with or without GPU support) to work with my own private data. While the LLM supports a CLI type of an interface for users to interact using a command prompt, it also comes with its own UI for a chat-bot type of an interface. 

Project dependencies: 
* Python 3.9 or above
* Pip 3
* Conda ( I used Mini-Conda )
* Al other dependencies are listed under the file dependencies.txt as a part of this repo

Private data should be stored under the SOURCE_DOCUMENTS folder provided in this repo. I have tested the LLM with CSV as well as PDF files and results are stunningly accurate. 
<img width="1133" alt="image" src="https://github.com/madhav2k/LocalLLM/assets/1558012/5de20c40-d9bb-4a96-86ad-0e8f37dad9be">

Following illustrates a generic data flow architeccture of the projet: 

![image](https://github.com/madhav2k/LocalLLM/assets/1558012/01e023b1-ea33-4c7d-8eb9-3c3c503a455b)

References: 
* Inspired by the ideas presented here: https://github.com/PromtEngineer/localGPT
* https://towardsdatascience.com/all-you-need-to-know-to-build-your-first-llm-app-eb982c78ffac?source=author_recirc-----7e663d808e6a----1---------------------41425d74_7011_4a38_9c94_d868d5406339-------
