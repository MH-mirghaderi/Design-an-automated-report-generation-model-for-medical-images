# Design-an-automated-report-generation-model-for-medical-images
Medical practitioners examine medical images, such as X-rays, write reports based on the findings, and 
provide conclusive statements. However, manual interpretation of the results and report generation by 
examiners are time-consuming processes that lead to potential delays in diagnosis. To address this challenge, 
we aim to design an automated report generation model for medical images leveraging an encoder–
decoder architecture.
For this task, we will use the Open-I collection of the Indiana University Chest X-ray dataset from the 
Indiana University Hospital network. This dataset consists of 7,470 X-ray images and 3851 patients 
reports. Each image in the dataset consists of two views: frontal and lateral. The number of X-ray images 
per report varies from 1 to 5. The training data resides in a dataset containing three key elements: indication, 
impression, and findings

Build a multi-modal encoder-decoder model: Use Vision Transformer (ViT) as the encoder to extract 
visual information from medical images. Use Generative Pre-trained Transformer 2 (GPT-2) as the 
decoder to generate medical reports and implement a cross-attention mechanism between the encoder 
and decoder to align visual features with the textual output.
• Explore and experiment with other vision models like Swin Transformer, BEiT, or similar feature 
extractors for medical images. Leverage your creativity to evaluate which encoder performs best for this 
task.
• Evaluate the performance of your models using word overlap metrics such as BLEU scores, 
ROUGE-L. Compare the performance of the models to determine the most effective architecture for
automated medical report generation.
