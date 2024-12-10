# Visual-Question-Answering-on-Vizwiz-Dataset

This project aims to develop a Visual Question Answering (VQA) system designed to assist visually impaired individuals in understanding visual scenes by answering natural language questions about images. By leveraging computer vision, natural language processing, and assistive technologies, the system enhances accessibility for visually impaired users.

## Overview

#### Dataset:
- Vizwiz-VQA: https://www.kaggle.com/datasets/lhanhsin/vizwiz

#### Model:
- BLIP: https://huggingface.co/Salesforce/blip-vqa-base


## Technology Stack

- **Programming Language**: Python
- **Libraries and Frameworks**:
  - PyTorch and HuggingFace for deep learning models.
  - PIL for image preprocessing.
- **Tools**:
  - 
  - NVIDIA GPUs for accelerated training and inference.
    - V100 32GB

## Code

The model is uploaded on HuggingFace and can be accessed as follows
```
from transformers import BlipProcessor, BlipForQuestionAnswering

model = BlipForQuestionAnswering.from_pretrained("ritika-kumar/finetuned-blip-vizwiz")
processor = BlipProcessor.from_pretrained("ritika-kumar/finetuned-blip-vizwiz")
```
## Inference

The complete code for evaluation and visualisation of results can be seen in the evaluation-finetuned-blip-vizwiz.ipynb file


## Acknowledgments
- Special thanks to the guiding professor and mentors for their invaluable insights.
- Thanks to the creators of the datasets and pre-trained models used in this project.
- Inspired by ongoing research and advancements in the field of Visual Question Answering.

Team Member: Ritika Kumar and Saranya Kadiyala (Team #19)

