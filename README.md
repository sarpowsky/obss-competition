# OBSS AI Image Captioning Challenge

## Achievement
**16th Place** out of all participants in the OBSS Internship Competition on Kaggle

## Competition Overview
Image captioning challenge organized by OBSS for internship selection. The task was to generate descriptive captions for images using machine learning models.

## Approach
- **Model**: Fine-tuned BLIP-Large (Salesforce/blip-image-captioning-large)
- **Strategy**: Vision encoder freezing + text component fine-tuning
- **Evaluation Metric**: FGD (Fréchet GTE Distance) using GTE-small embeddings

## Key Features
- Advanced data augmentation and quality filtering
- Multi-scale training with test-time augmentation
- Beam search with nucleus sampling for generation
- Caption post-processing and enhancement
- Label smoothing and cosine learning rate scheduling

## Tech Used
- **Deep Learning**: PyTorch, Transformers (Hugging Face)
- **Vision**: BLIP, PIL, OpenCV
- **NLP**: Sentence Transformers, NLTK
- **Data**: Pandas, NumPy, Scikit-learn

## Files
- `obss_solution_sarpowsky.ipynb` - Complete solution notebook
- `submission.csv` - Final competition submission


## Results
- **Validation FGD Score**: 0.22008
- **Final Ranking**: 16th place
- **Model**: Fine-tuned BLIP-Large with 1.8B parameters
