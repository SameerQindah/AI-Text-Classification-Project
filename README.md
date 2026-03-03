# News Classification using Machine Learning

## Project Information
Course: Artificial Intelligence (COMP338)  
Instructor: Dr. AbdelRahman Hamarsha  
Students:
- Sameer Ayman (1221561)
- Hasan Ahmad Karakra (1220501)

## Project Description
This project classifies news headlines into four categories:
- World
- Sports
- Business
- Sci/Tech

Two machine learning models were implemented:
- Logistic Regression
- Decision Tree

## Dataset
AG News Dataset from HuggingFace:
https://huggingface.co/datasets/wangrongsheng/ag_news

## Preprocessing
- Lowercase conversion
- Removing special characters
- Removing extra spaces
- TF-IDF vectorization (max_features=5000)

## Results

| Model | Accuracy |
| Logistic Regression | 90.39% |
| Decision Tree | 63.89% |

Logistic Regression significantly outperformed Decision Tree.

## How to Run

```bash
pip install -r requirements.txt
