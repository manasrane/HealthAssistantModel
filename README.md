# 🩺 AI Health Assistant using BERT

This project is an AI-powered Health Assistant that uses a fine-tuned `bert-base-uncased` model to predict possible diseases based on user-provided symptom descriptions.

The model was trained on a custom dataset to classify conditions with overlapping symptoms — for example, distinguishing between the common cold and flu-like illnesses.

### 🔍 Key Features:
- Uses `BERT` for symptom understanding and disease classification
- Fine-tuned on a domain-specific dataset
- Handles overlapping symptom categories with high accuracy

### 📁 File:
- `Health_Assistant.ipynb`: Core notebook with training, evaluation, and sample predictions

### 🚀 Future Improvements:
- API deployment (Flask/FastAPI)
- UI integration (Streamlit or React)
- Expand to multilingual input
