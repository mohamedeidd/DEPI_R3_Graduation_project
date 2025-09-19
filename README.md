# DEPI_R3_Graduation_project
📌 Project Overview

Fashion styles can be subjective, but by combining visual features from clothing images with textual features like product descriptions, we can build a multi-modal model that classifies clothing styles more accurately than single-input models.

🎯 Objectives

🖼️ Use CNNs for image features.

📝 Use Transformers/LSTMs for text features.

🔗 Combine both to create a multi-modal classifier.

📈 Evaluate model performance on fashion datasets.

🛠️ Tech Stack
Component	Technology
Language	Python
Frameworks	TensorFlow / PyTorch
Image Handling	OpenCV, PIL
Text Processing	NLTK, HuggingFace Transformers
Visualization	Matplotlib, Seaborn
Data Handling	NumPy, Pandas
📂 Project Structure
├── data/                # Dataset files (images + text)
├── notebooks/           # Jupyter notebooks for experiments
├── src/                 # Source code for model, preprocessing, etc.
├── models/              # Saved trained models
├── requirements.txt     # Python dependencies
└── README.md            # Project documentation

🚀 How to Run

Clone the repository:

git clone https://github.com/your-username/multi-modal-clothing-classifier.git
cd multi-modal-clothing-classifier


Install dependencies:

pip install -r requirements.txt


Run training:

python src/train.py


Evaluate the model:

python src/evaluate.py

📊 Expected Results

📈 Higher accuracy using multi-modal input vs single input.

🖼️ Visualizations: Training curves, confusion matrix, sample predictions.

Example Output:


👥 Team Members

Mohamed Eid

[Team Member 2 Name]

[Team Member 3 Name]

[Team Member 4 Name]

Instructor: Aya Hesham

📜 License

This project is licensed under the MIT License.

✨ Acknowledgments

Special thanks to Aya Hesham for guidance and support throughout this project.
