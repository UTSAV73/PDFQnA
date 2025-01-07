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

![1](https://github.com/user-attachments/assets/6f913468-1898-4f06-b22b-dea203933983)



![2](https://github.com/user-attachments/assets/89ea7965-2e81-4627-976f-16f4b751304b)



Producing and with referrence from PDFs.

#Future Improvements:
-> Multi-modal
-> Context-awareness
-> Muti-lingual
