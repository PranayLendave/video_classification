## Video Classification 
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/PranayLendave/video_classification/blob/main/trained_movinets_notebook.ipynb)

Video classification is an essential task in computer vision, and this project focuses on utilizing MoViNet models for this purpose. MoViNet models are known for their efficiency and lightweight nature, making them suitable for real-time and resource-constrained applications.

The notebook provides a comprehensive guide on video classification using MoViNet models. It covers data preparation, model training, evaluation, and inference on new videos.

To train and test the MoViNet model, a subset of the UCF101 dataset has been used. This dataset contains various video clips across multiple action categories, making it suitable for training and evaluating video classification models.

### Notebook Contents

The notebook includes the following key sections and functionalities:

1. **Introduction**: An introduction to video classification and an overview of the MoViNet models used in the notebook.
2. **Data Preparation**: Instructions and code for preparing the video dataset for training and evaluation.
3. **Model Training**: Steps for training the MoViNet model on the prepared video dataset.
4. **Model Evaluation**: Evaluation of the trained MoViNet model on test data and performance analysis.
5. **Inference on New Videos**: Instructions and code for using the trained MoViNet model to classify new videos.
6. **Conclusion**: Summary of the notebook's findings and potential future directions.

### Dependencies

The notebook requires the installation of the following dependencies:

- `tensorflow`: The deep learning framework used for training and inference.
- `tensorflow_hub`: A library for importing and using pre-trained models from TensorFlow Hub.
- `tf-models-official`: TensorFlow Models library, providing a collection of official models and tools for training and evaluating them.
- `keras`: A high-level API for building and training deep learning models.
- `opencv-python`: A library for computer vision tasks, including video processing.
- `remotezip`: A library for working with remote ZIP files.
- `tqdm`: A library for displaying progress bars during iterations.
- `numpy`, `seaborn`, and `matplotlib.pyplot`: Libraries for numerical operations and data visualization.

### How to Use the Notebook

To use the notebook, follow these steps:

1. Clone or download the repository to your local machine.
2. Open the "trained_movinets_notebook.ipynb" notebook using Jupyter Notebook or Google Colab.
3. Run the notebook cells sequentially, following the provided instructions and comments.
4. Modify and adapt the code as per your requirements and data.

Note: Make sure to have the necessary video dataset available and adjust the paths accordingly in the notebook.
