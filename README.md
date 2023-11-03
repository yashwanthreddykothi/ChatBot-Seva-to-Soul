# ChatBot for Seva to Soul
Welcome to the Seva to Soul Chatbot repository. This chatbot is designed to be an integral part of the Seva to Soul (SOS) platform, which focuses on promoting holistic well-being, including mental, physical, and spiritual health.


# Build Details
1. [LangChain](https://github.com/hwchase17/langchain)
2. [GPT4All](https://github.com/nomic-ai/gpt4all)
3. [LlamaCpp](https://github.com/ggerganov/llama.cpp)
4. [Chroma](https://www.trychroma.com/)
5. [SentenceTransformers](https://www.sbert.net/)


# Environment Setup
In order to set your environment up to run the code here, first install all requirements:
```shell
pip3 install -r requirements.txt
```

Then, download the LLM model and place it in a directory of your choice:
- LLM: [ggml-gpt4all-j-v1.3-groovy.bin] (https://gpt4all.io/models/ggml-gpt4all-j-v1.3-groovy.bin)

Edit the variables appropriately in the `.env` file.


# Updating the Dataset
Put the files into the `source_documents` directory.
The supported extensions are:

   - `.csv`: CSV,
   - `.docx`: Word Document,
   - `.doc`: Word Document,
   - `.enex`: EverNote,
   - `.eml`: Email,
   - `.epub`: EPub,
   - `.html`: HTML File,
   - `.md`: Markdown,
   - `.msg`: Outlook Message,
   - `.odt`: Open Document Text,
   - `.pdf`: Portable Document Format (PDF),
   - `.pptx` : PowerPoint Document,
   - `.ppt` : PowerPoint Document,
   - `.txt`: Text file (UTF-8),

Run the following command to ingest all the data.
```shell
python ingest.py
```


## Run Command
```shell
python ChatRun.py
```

Type `exit` to finish the script.


# System Requirements
1. Python = 3.10 or later installed.

2. If you encounter an error while building a wheel during the `pip install` process, you may need to install a C++ compiler on your computer.


# Features
- **Supportive Conversations**: The chatbot offers empathetic and supportive conversations to users seeking emotional assistance.

- **Personalized Advice**: It provides personalized recommendations and advice based on user interactions and preferences.

- **Mental Health Guidance**: The chatbot offers guidance for stress management, mood tracking, and emotional well-being.

- **Community Interaction**: The chatbot can guide users to engage with SOS community support groups and workshops.

- **Integration with SOS Platform**: The chatbot seamlessly integrates with the broader SOS platform.


# Usage
To use the Seva to Soul Chatbot, simply interact with it through the provided chat interface. The chatbot will guide users through the various well-being resources and support available within the SOS platform.

# Thank you for using our platform.
   **Team Seva to Soul** 