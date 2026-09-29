# Dog Breed Classification with Transfer Learning

End-to-end deep-learning learning project for classifying dog images across 120 breeds using TensorFlow/Keras transfer learning.

## Project scope
This project was built as a learning implementation around the Kaggle Dog Breed Identification dataset. It demonstrates the complete image-classification workflow rather than claiming an original research contribution.

## Workflow
- Explore the labelled Kaggle dataset.
- Build TensorFlow image preprocessing and batching pipelines.
- Encode 120 dog-breed classes.
- Train a transfer-learning classifier using MobileNetV2.
- Use early stopping and validation monitoring.
- Save and reload trained models.
- Generate predictions on held-out and custom images.

## Recorded results
The original Colab run reached approximately **73% validation accuracy** on the held-out validation data. Training accuracy became substantially higher, showing why validation monitoring and early stopping are important.

## Tech stack
Python, TensorFlow, Keras, TensorFlow Hub, Pandas, NumPy, Matplotlib, Scikit-learn.

## Repository
- `dog-breed-classification.ipynb` — cleaned portfolio notebook.
- `requirements.txt` — Python dependencies.

## Data
The dataset comes from Kaggle's **Dog Breed Identification** competition and contains more than 10,000 labelled training images across 120 classes. Dataset files and trained models are excluded from Git.
