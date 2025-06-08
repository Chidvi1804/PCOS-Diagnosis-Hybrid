# PCOS Diagnosis Using Textual and Image Data

This project uses hybrid deep learning models to diagnose Polycystic Ovary Syndrome (PCOS) from both textual clinical data and ultrasound images.

## Features

- Textual data analyzed using CNN, LSTM, Bi-LSTM models.
- Ultrasound images processed with CNN, CNN-MLP, and attention models.
- Achieved up to 97.66% accuracy on image data using CNN+MLP.
- Models implemented in Python using TensorFlow/Keras.

## Folder Structure

- `data/`: Clinical and image datasets
- `images/`: Ultrasound images
- `pcos_diagnosis.ipynb`: Main Jupyter notebook
- `README.md`: Project overview and instructions

## Usage

1. Clone the repository.
2. Open `pcos_diagnosis.ipynb` in Jupyter Notebook or Google Colab.
3. If using Google Colab, **run the notebook cell that mounts Google Drive** before accessing data files.
4. Make sure to set the correct file paths inside the notebook according to your environment (local or Colab).
5. Install required libraries (TensorFlow, NumPy, Pandas, etc.).
6. Run the notebook cells step-by-step.

## Contact

For questions, reach out to **Chidvi1804**.
