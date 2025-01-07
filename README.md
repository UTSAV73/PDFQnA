# PDF-QnA
This is an interactive app developed to assist users to interact with their PDF. It is built using Open Source Stack.

## Getting Started

Follow these steps to set up and run the project on your local machine.


### Installation

```sh
## Clone the repository
git clone https://github.com/UTSAV73/PDFQnA/

## Create the necessary folders
mkdir db
mkdir models
## Add your model files to the 'models' folder
mkdir docs

----
### Usage 

## Run the ingestion script to read pdf and create embeddings

`python ingest.py`

## Start the chatbot application using Streamlit

`streamlit run chatbot_app.py`



![image](https://github.com/user-attachments/assets/f41dc6b4-57e6-4612-99d6-78f8459bd859)
![image](https://github.com/user-attachments/assets/48a5a208-18c1-4d83-bd3a-f8b9e1e22d9b)
Producing and with referrence from PDFs.

#Future Improvements:
-> Multi-modal
-> Context-awareness
-> Muti-lingual
