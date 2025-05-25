<!--
# translaTHOR

## A language translation project<br>
(still under progress)

<br>

## Techonology used:
 - ### 🤗 Transformers library
 - ### Pytorch

<br>

## For English to Bengali Traslation
### Dataset from: <a href="https://ieee-dataport.org/open-access/supara-benchmark-benchmark-dataset-english-bangla-machine-translation">SUPARA-BENCHMARK</a>
### Resources:
 - https://huggingface.co/docs/transformers/en/model_doc/bert
 - https://huggingface.co/transformers/v3.0.2/model_doc/bert.html
 - https://huggingface.co/sagorsarker/bangla-bert-base
 - https://huggingface.co/Helsinki-NLP/opus-mt-bn-en
### Files & Folders:
 - <a href="https://github.com/PALLADIUM26/translaTHOR/blob/main/English_to_Bengali_1.ipynb">English_to_Bengali_1.ipynb</a> is the Notebook for the whole ML process - v1
 - <a href="https://github.com/PALLADIUM26/translaTHOR/blob/main/English_to_Bengali_0.ipynb">English_to_Bengali_0.ipynb</a> is the Notebook for the whole ML process - v0
 - <a href="https://github.com/PALLADIUM26/translaTHOR/blob/main/english_to_bengali_0.py">english_to_bengali_0.py</a> is the raw python file for the whole ML process - v0
 - <a href="https://github.com/PALLADIUM26/translaTHOR/tree/main/saved_model">saved_model</a> is the folder containing saved model for translating English to Bengali - v0
 - <a href="https://github.com/PALLADIUM26/translaTHOR/blob/main/Translate_EnglishToBangla.ipynb">Translate_EnglishToBangla.ipynb</a> is the Jupyter Notebook for initial working (incomplete)
 - <a href="https://github.com/PALLADIUM26/translaTHOR/blob/main/translate_englishtobangla.py">translate_englishtobangla.py</a> is the raw python file for initial working (incomplete)

<br>

## Machine Learning Process:
 - Import libraries
 - Import datasets and Preprocess data
 - Tokenize the data
 - Load the model
 - Train the model
 - Evaluate the model
 - Save the model
 - Output for User input
 - Convert the saved folder into zip

-->

# translaTHOR

**translaTHOR** is a language translation project focused on translating English text to Bengali. Leveraging advanced natural language processing techniques, it utilizes the Transformers library and PyTorch framework to build and train translation models. The project is currently under development.

## Features

* **English to Bengali Translation**: Translate English sentences into Bengali using trained models.
* **Model Training and Evaluation**: Train models on the SUPARA-BENCHMARK dataset and evaluate their performance.
* **Interactive Notebooks**: Jupyter Notebooks provided for experimentation and demonstration purposes.

## Technologies Used

* 🤗 [Transformers Library](https://huggingface.co/docs/transformers)
* [PyTorch](https://pytorch.org/)

## Dataset

The project utilizes the [SUPARA-BENCHMARK](https://ieee-dataport.org/open-access/supara-benchmark-benchmark-dataset-english-bangla-machine-translation) dataset for training and evaluation.

## Resources

* [Hugging Face Transformers Documentation](https://huggingface.co/docs/transformers)
* [BERT](https://huggingface.co/transformers/v3.0.2/model_doc/bert.html)
* [BERT](https://huggingface.co/docs/transformers/en/model_doc/bert)
* [Bangla BERT Base Model by Sagor Sarker](https://huggingface.co/sagorsarker/bangla-bert-base)
* [Helsinki NLP Models](https://huggingface.co/Helsinki-NLP/opus-mt-bn-en)
* [OPUS](https://huggingface.co/Helsinki-NLP/opus-mt-bn-en)

## Getting Started

### Prerequisites

Ensure you have the following installed:

* Python 3.x
* PyTorch
* Transformers
* Jupyter Notebook

### Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/PALLADIUM26/translaTHOR.git
   cd translaTHOR
   ```



2. **Install dependencies**:

   ```bash
   pip install torch transformers jupyter
   ```



3. **Launch Jupyter Notebook**:

   ```bash
   jupyter notebook
   ```



4. **Open and run notebooks**:

   * `English_to_Bengali_0.ipynb`
   * `English_to_Bengali_1.ipynb`
   * `Translate_EnglishToBangla.ipynb`

   These notebooks demonstrate the translation process and model usage.

## Project Structure

* `saved_model/`: Directory containing saved model checkpoints.
* `English_to_Bengali_0.ipynb`: Jupyter Notebook for initial translation experiments.
* `English_to_Bengali_1.ipynb`: Continuation of translation experiments.
* `Translate_EnglishToBangla.ipynb`: Notebook demonstrating translation using trained models.
* `english_to_bengali_0.py`: Python script for translation tasks.
* `translate_englishtobangla.py`: Another Python script for translation tasks.
* `README.md`: Project documentation.

## Contributing

Contributions are welcome! Feel free to fork the repository, make improvements, and submit pull requests. For major changes, please open an issue first to discuss your ideas.


