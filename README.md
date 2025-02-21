# Fine-Tuning a CNN Model for Cats vs. Dogs Classification 🐱🐶
📌 Overview
This project fine-tunes a pre-trained MobileNetV2 model to classify images of cats and dogs. The dataset used is TensorFlow's cats_vs_dogs dataset. The model was trained with transfer learning and further optimized using fine-tuning.

📌 Steps in the Project

1️⃣ Load and preprocess the cats_vs_dogs dataset.

2️⃣ Use MobileNetV2 as a base model (without top layers).

3️⃣ Freeze the base model and add custom classification layers.

4️⃣ Train the model on the dataset (initial training).

5️⃣ Unfreeze the last 50 layers for fine-tuning to improve performance.

6️⃣ Save and deploy the fine-tuned model.

📊 Model Performance

✅ Initial Training Accuracy: ~96.38%

✅ Fine-Tuned Accuracy: ~96.76%
