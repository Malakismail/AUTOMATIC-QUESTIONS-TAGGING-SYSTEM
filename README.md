# Automatic Questions Tagging System
A machine learning-based solution for automatically tagging questions with relevant categories or keywords. This project uses natural language processing (NLP) techniques to analyze the semantic context of questions and assign meaningful tags, improving organization, searchability, and management of content.



# Features
•	**Automated Tagging:** Assigns tags to questions based on their textual content.

•	**NLP-Powered Analysis:** Processes and analyzes questions using advanced NLP techniques.

•	**Machine Learning Models:** Utilizes supervised learning algorithms for text classification.

•	**Customizable Pipelines:** Easily adaptable for different datasets and tag hierarchies.

•	**Scalable Design:** Handles large datasets efficiently, suitable for real-world applications.



# How It Works
**1. Data Preprocessing:** Cleans and tokenizes the text, removes noise, and normalizes input data.
**2. Feature Engineering:** Converts textual data into numerical features using techniques like TF-IDF, word embeddings, or transformers.
**3. Model Training:** Trains a supervised machine learning model to predict tags based on labeled data.
**4. Tag Prediction:** Uses the trained model to automatically assign tags to new, unseen questions.
**5. Evaluation and Optimization:** Validates model performance using metrics like precision, recall, and F1-score and optimizes for better results.



# Installation
**1. Clone the repository:**

    git clone https://github.com/Malakismail/AUTOMATIC-QUESTIONS-TAGGING-SYSTEM.git
    cd AUTOMATIC-QUESTIONS-TAGGING-SYSTEM
**2. Install dependencies:**

    pip install -r requirements.txt



# Usage
**1. Prepare your dataset in the required format** (e.g., CSV with a column for questions and optional tags).
**2. Preprocess the data:**

    python preprocess.py --data <path_to_dataset>
**3. Train the model:**

    python train_model.py --data <path_to_preprocessed_data>
**4. Predict tags for new questions:**

    python predict_tags.py --input <path_to_questions_file>
**5. Evaluate the model:**

    python evaluate_model.py --data <path_to_labeled_test_data>




**The dataset can be found here** https://drive.google.com/drive/u/0/folders/1c6Ev0XG1-0uC6-pubZ7XPwTl9H8377T9



## Contributing
Contributions are welcome! Fork the repository, create a branch for your feature or bug fix, and submit a pull request.




## Contact
For inquiries or collaboration opportunities, please reach out to me:

**Name**: Malak Ismail  
**Email**: malakismail706@gmail.com 
**LinkedIn**: www.linkedin.com/in/malak-ismail-393148251

