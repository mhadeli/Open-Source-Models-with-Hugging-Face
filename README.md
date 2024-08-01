# Translation and Summarization

## Overview

This project demonstrates the use of the Hugging Face `transformers` library for various natural language processing (NLP) and computer vision tasks. It covers translation, summarization, sentence embeddings, zero-shot audio classification, text-to-speech, segmentation, image retrieval, image captioning, visual question answering, and zero-shot image classification.

## Sections

1. **Translation**: Using pre-trained models to translate text.
2. **Summarization**: Building a summarization pipeline.
3. **Sentence Embeddings**: Computing sentence embeddings and measuring similarity.
4. **Zero-Shot Audio Classification**: Classifying audio files without training.
5. **Text to Speech**: Converting text to speech using `transformers`.
6. **Segmentation - SAM**: Implementing the Segment Anything Model (SAM) for image segmentation.
7. **Image Retrieval**: Loading models and processors for image and text input and performing image-text matching.
8. **Image Captioning**: Generating captions for images with and without specific prompts.
9. **Visual Question & Answering**: Asking questions about images and getting answers.
10. **Zero-Shot Image Classification**: Classifying images into categories without prior training on specific labels.

## Requirements

To run the code provided in this notebook, you'll need to install the following Python packages:

```bash
pip install transformers
pip install datasets
pip install soundfile
pip install librosa
pip install gradio
pip install timm
pip install inflect
pip install phonemizer

For text-to-speech capabilities, py-espeak-ng is required and is only available on Linux operating systems. Install it using the following commands:

```
sudo apt-get update
sudo apt-get install espeak-ng
pip install py-espeak-ng

## Usage
Follow the instructions in each section of the notebook to run the examples. The notebook provides code snippets and explanations for setting up and using various NLP and computer vision models.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgements
Hugging Face for the transformers library
The open-source community for various contributions and support
