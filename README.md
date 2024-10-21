# Text Summarization by Tuning HuggingFace Models

This project is designed to perform text summarization using Hugging Face summarization models. It includes various stages such as data ingestion, data transformation, model training, and model evaluation. The project is built using FastAPI for serving the model and includes a training pipeline to automate the entire process. 

## Technologies Used
Python: The main programming language used for the project.

FastAPI: For serving the model and creating API endpoints.

Transformers: For implementing the text summarization model.

PyTorch: For model training and evaluation.

Jupyter Notebooks: For research and experimentation.

Docker: For containerizing the application.

YAML: For configuration management.

## Installation and Running

1. Clone the repository:
    ```sh
    git clone https://github.com/OnurAsimIlhan/text-summarizer.git
    cd text-summarizer
    ```

2. Create a virtual environment and activate it:
    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```
    or
    ```sh
    cuda create -p venv
    cuda activate venv/
    ```

3. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```

4. Run FastAPI:
   ```sh
    python app.py
    ```
## Configuration

The configuration for the project is managed through the `config/config.yaml` file. This file includes paths and parameters for different stages of the pipeline such as data ingestion, data transformation, model training, and model evaluation.

