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
![1](https://github.com/user-attachments/assets/531df3d2-a9b9-4a88-83f5-0378f510d173)


![2](https://github.com/user-attachments/assets/f9d75f4d-f572-4e3b-a2a5-e0507b08af23)


Producing and with referrence from PDFs.

#Future Improvements:
-> Multi-modal
-> Context-awareness
-> Muti-lingual
