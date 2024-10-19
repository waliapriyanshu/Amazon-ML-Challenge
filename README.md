# Amazon-ML-Challenge
Project Description:
This project is part of the Amazon ML Challenge, which involves a Machine Learning pipeline using BERT (Bidirectional Encoder Representations from Transformers) in combination with PaddleOCR for Optical Character Recognition (OCR) tasks. The project aims to extract entities from text in images and generate corrected predictions for structured data formats. BERT is used for text generation and prediction tasks, while PaddleOCR is leveraged for recognizing text from images.

Key Features:
1. Entity extraction and prediction from OCR output.
2. Correction of entity values using domain-specific rules.
3. Integration of BERT for generating or correcting text outputs.
4. Use of PaddleOCR for high-performance optical character recognition.
5. Export of results for further analysis.

Technologies Used:
1. BERT: Pre-trained language model used for text generation and entity prediction.
2. addleOCR: A powerful OCR tool used for detecting and recognizing text from images.
3. Python: Programming language used for orchestrating the model pipelines and data processing.
4. Pandas: For data manipulation and CSV export.
5. Matplotlib: For visualizing data.

Files and Structure:
1. bert + paddleocr.ipynb: Main notebook that integrates BERT and PaddleOCR for OCR, text extraction, and entity prediction.
2. Data: Input data for training and testing (assumed to be loaded from external files).
3. Results: Final predictions are saved in CSV format.
   
How to Run:
1. Install Required Libraries: Make sure you have the following dependencies installed in your Python environment:
pip install transformers paddleocr pandas matplotlib
2. Prepare the Data: The dataset should contain image files and corresponding labels, which will be processed using PaddleOCR for text extraction and fed into the BERT model for predictions.
3. Run the Notebook: Open the notebook (bert + paddleocr.ipynb) in Jupyter or any other compatible environment. Follow the steps provided in the notebook to load the data, preprocess it, and execute the model pipeline.
4. Inspect and Export Results: The final predicted outputs and corrected entity values are saved as CSV files. You can review and analyze the generated predictions by loading these files.

Acknowledgments:
1. Amazon ML Challenge for providing the problem statement.
2. Hugging Face for providing the BERT implementation.
3. PaddleOCR for enabling high-performance text recognition from images.
