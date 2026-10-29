# Scientific-Paper-Summarization-Using-a-Hybrid-Deep-Learning-Approach
This project aims to automate the summarization of scientific papers using a hybrid approach that combines extractive text processing with deep learning.

The system uses **TF-IDF and cosine similarity** to identify important sentences and an **LSTM Encoder–Decoder with Attention** to generate concise summaries. It also supports PDF text extraction and basic identification of scientific paper sections.

## Key Features
- Extract text from scientific PDF documents using PyMuPDF.
- Select important sentences using TF-IDF and cosine similarity.
- Generate abstractive summaries using an LSTM Encoder–Decoder with Attention.
- Identify common scientific sections, including the abstract, introduction, methodology, results, discussion, and conclusion.
- Process and summarize scientific text through a modular Python notebook workflow.

## Technologies
- Python
- TensorFlow and Keras
- NumPy and Pandas
- NLTK and scikit-learn
- PyMuPDF
- Matplotlib

## Model Architecture
The Encoder processes the input text, while the Decoder generates the summary token by token. The Attention mechanism helps the Decoder focus on relevant parts of the encoded input.

The model is trained on scientific article–abstract pairs.

## Evaluation
The current model evaluation produced a loss of approximately **5.20**. This value represents the model's loss, not its accuracy. Further evaluation using masked token accuracy and summarization metrics such as ROUGE is needed to assess performance.

## Future Improvements
- Improve summary fluency and coherence.
- Evaluate generated summaries using ROUGE metrics.
- Improve scientific section detection.
- Experiment with larger datasets and model configurations.

## Project Status
Research and development prototype.
