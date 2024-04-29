# LoRA_text_classification

SMS Spam Classification with LoRA Fine-Tuning
This repository implements a text classification model to identify SMS spam messages.

Key Features:

Model: GPT-2 from Hugging Face
Fine-Tuning Technique: LoRA (Low Rank Adaptation), a Parameter-Efficient Fine-Tuning (PEFT) method from Hugging Face
Dataset: sms_spam from Hugging Face (https://huggingface.co/datasets/sms_spam)
Evaluation: Accuracy metric using datasets from Hugging Face
Benefits:

Efficient Fine-Tuning: LoRA significantly reduces computational resources required for fine-tuning compared to the full fine-tuning approach.
Scalability: The codebase can be adapted to classify sms messages as "spam" or "not-spam" by using a different training dataset.
Project Inspiration:

Special thanks to Udacity for developing the training materials that served as the foundation for this project.

Getting Started:

This repository provides a Jupyter Notebook that demonstrates the model training, evaluation, and comparison process. Refer to the notebook for detailed instructions on running the code.

Further Development:

Experiment with different pre-trained models from Hugging Face.
Explore more advanced text classification techniques.
Adapt the code to your specific text classification task using a relevant dataset.
