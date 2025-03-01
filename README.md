Detection of Phishing Attacks Using Random Forest Algorithm
📌 Project Overview
Phishing attacks are one of the most common cybersecurity threats, targeting users' sensitive information through fraudulent websites. This project utilizes Machine Learning (ML) techniques, specifically the Random Forest Algorithm, to classify websites into three categories: Benign, Spam, and Malicious.

Our system analyzes URL lexical features and classifies them without requiring access to the website’s core content, reducing runtime delays and ensuring user safety.

🚀 Key Features
✅ Machine Learning-Based Detection – Uses Random Forest Algorithm and Support Vector Machine (SVM) for high accuracy.
✅ Feature Extraction – Identifies suspicious patterns in URLs, including IP addresses, URL length, special characters, and prefixes/suffixes.
✅ High Efficiency – Processes thousands of URLs efficiently to detect phishing sites.
✅ Scikit-Learn Implementation – Uses Python's scikit-learn library for model training and evaluation.
✅ Anaconda Navigator Integration – Simplifies package and environment management.

📂 Project Structure
graphql
Copy
Edit
📁 Phishing-Detection
│── 📜 dataset.csv                 # Labeled dataset with benign, spam, and malicious URLs  
│── 📜 phishing_detection.ipynb    # Jupyter Notebook for model training & testing  
│── 📜 feature_extraction.py       # Code for extracting key URL features  
│── 📜 model_training.py           # Implements Random Forest & SVM training  
│── 📜 results_analysis.py         # Model evaluation and accuracy reporting  
│── 📜 README.md                   # Project documentation  
🛠️ Tech Stack
Programming Language: Python 🐍

Libraries Used:

pandas – Data handling
numpy – Numerical computations
scikit-learn – ML model implementation
matplotlib – Data visualization
Development Tools:

Jupyter Notebook 📓
Anaconda Navigator 🏗️
📊 Methodology
1️⃣ Data Preprocessing
Collected and labeled dataset of URLs
Removed duplicate and irrelevant entries
Applied feature extraction for classification
2️⃣ Feature Extraction
Checked for IP addresses in the URL
Measured URL length to identify unusually long or short URLs
Detected special characters used to mask phishing sites
Identified prefixes & suffixes commonly used in phishing domains
3️⃣ Model Training
Implemented Random Forest Algorithm and Support Vector Machine (SVM):

Random Forest: Uses multiple decision trees to improve classification accuracy
SVM: Finds the optimal hyperplane to separate phishing and benign URLs
4️⃣ Evaluation & Results
Trained on 3,000+ URLs
Achieved 98.38% accuracy in detecting phishing sites
📌 Installation & Setup
1️⃣ Prerequisites
Ensure you have Python 3.7+ and the required libraries installed.

2️⃣ Clone Repository
bash
Copy
Edit
git clone https://github.com/your-username/Phishing-Detection.git
cd Phishing-Detection
3️⃣ Install Dependencies
Using Anaconda:

bash
Copy
Edit
conda create --name phishing_env python=3.7  
conda activate phishing_env  
pip install -r requirements.txt  
4️⃣ Run the Model
Execute the following command to train and test the model:

bash
Copy
Edit
python model_training.py
🔍 Results & Future Work
✅ Successfully tested on a large dataset of phishing and benign URLs
✅ Achieved high accuracy in real-world scenarios
🔜 Future Enhancements:

Implement Deep Learning for improved classification
Integrate Google Safe Browsing API for real-time phishing detection
Develop a browser extension for user protection
📝 Authors
Mrs. R. Sathya (Assistant Professor) – sathyaraman76@gmail.com
U. Sai Kiran – kiran98118@gmail.com
J. V. Chowdary – adithya.chowdary810@gmail.com
B. Kasi Kumar Reddy – kasikumar214@gmail.com
📍 Institution: SRM Institute of Science and Technology, Chennai, India

📜 References
Refer to our research paper for in-depth methodology and dataset details.

For further reading on phishing detection techniques, check out:

Phishing Detection Literature Survey
Random Forest for Cybersecurity
