# Next Word Predictor

This project implements a Next Word Prediction model using Long Short-Term Memory (LSTM) neural networks. The model is designed to predict the next word in a given sequence of text, which can be useful for applications like autocomplete systems, chatbots, and text editors.([GitHub][1], [GitHub][2])

## Features

* **LSTM-based Model**: Utilizes LSTM layers to capture the temporal dependencies in text data.
* **Tokenizer**: Employs a tokenizer to preprocess and convert text into sequences suitable for model training and prediction.
* **Pre-trained Model**: Includes a pre-trained model (`word_predictor_model.h5`) for immediate use.
* **Web Application**: Provides a simple web interface (`app.py`) to interact with the model and get predictions.

## Installation

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/sachin-pixe/next_word_predictor.git
   cd next_word_predictor
   ```



2. **Create a Virtual Environment** (Optional but recommended):

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```



3. **Install Dependencies**:

   ```bash
   pip install -r requirements.txt
   ```



*Note: Ensure that `requirements.txt` includes all necessary packages like `tensorflow`, `keras`, `numpy`, `flask`, etc.*

## Usage

1. **Run the Web Application**:

   ```bash
   python app.py
   ```



This will start a local server. Open your browser and navigate to `http://localhost:5000` to access the application.

2. **Interact with the Model**:

   * Enter a sequence of words in the input field.
   * Click on the "Predict" button to get the next word prediction.

## Files Description

* `LSTM.ipynb`: Jupyter Notebook containing the code for training the LSTM model.
* `app.py`: Flask web application to serve the model and provide a user interface.
* `tokenizer.pkl`: Serialized tokenizer used for text preprocessing.
* `word_predictor_model.h5`: Pre-trained LSTM model saved in HDF5 format.
* `README.md`: Project documentation.
* `LICENSE`: MIT License file.([GitHub][3], [GitHub][4])

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any enhancements or bug fixes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

