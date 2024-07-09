## Medbot
MedBot is an intelligent medical chatbot leveraging the capabilities of Llama 2.0 Large Language Model (LLM). This repository provides a comprehensive solution for querying medical and disease-related information from uploaded PDF documents. The web application is built using Chainlit and LangChain to ensure an intuitive and user-friendly interface.

## Features

- **Llama 2.0 LLM Integration:** Utilizes the advanced Llama 2.0 LLM for high-quality natural language understanding and generation.
- **PDF Data Upload:** Users can upload medical journals and other related PDFs to train the model.
- **Medical Query Response:** Provides accurate and reliable answers to medical and disease-related questions.
- **Chainlit Web Application:** Interactive web application interface built using Chainlit.
- **LangChain Integration:** Enhances data processing and interaction capabilities.

## Getting Started

Follow these instructions to get a copy of the project up and running on your local machine.

### Prerequisites

- Python 3.8 or later
- pip (Python package installer)
- Git

### Installation

1. **Clone the Repository:**
   ```sh
   git clone https://github.com/dvtushar/medbot.git
   cd medbot

2. **Create a Virtual Environment:**
   ```sh
   python -m venv venv
   source venv/bin/activate   # On Windows use `venv\Scripts\activate`
3. **Install Dependencies:**
    ```sh
    pip install -r req.txt

### Running the application
1. **Start the Chainlit Server:**
    ```sh
    chainlit run app.py
2. **Access the Web Application:**
  Open your web browser and go to http://localhost:8000.

### Usage
1. **Upload PDF Documents:**
- Navigate to the upload section of the web application.
- Upload your medical journal PDF files.

2. **Ask Questions:**
- Enter your medical or disease-related query in the provided text box.
- Receive detailed and accurate answers from MedBot.

### Usage
The project requires the following packages:
- pypdf
- langchain
- torch
- accelerate
- bitsandbytes
- transformers
- sentence_transformers
- faiss_cpu
These dependencies are listed in the req.txt file and will be installed when following the installation steps above.
### Contributing
We welcome contributions from the community. Please read the following guidelines before contributing:
 - 1.Fork the repository.
 - 2.Create a new branch (git checkout -b feature/your-feature).
 - 3.Make your changes.
 - 4.Commit your changes (git commit -am 'Add new feature').
 - 5.Push to the branch (git push origin feature/your-feature).
 - 6.Create a new Pull Request.
### License
This project is licensed under the MIT License. See the LICENSE file for more details.

### Acknowledgements
- Llama 2.0 LLM
- Chainlit
- LangChain

**Download the pretrained lamma 2.0 model using the following link:**
https://huggingface.co/TheBloke/Llama-2-7B-Chat-GGML/blob/main/llama-2-7b-chat.ggmlv3.q8_0.bin



### Screenshot of the working app
![image](https://github.com/dvtushar/Medbot/assets/96177523/8892f84e-00e6-4d51-b76e-651a5349de47)
![image](https://github.com/dvtushar/Medbot/assets/96177523/fa9fe8e7-e2f2-44a4-b921-7f90d843881d)
![image](https://github.com/dvtushar/Medbot/assets/96177523/a1d2ceb4-26a0-4119-80a0-89050648830f)





