## Six Human Emotions Detection System
![Image Description] C:\Users\Lenovo\Pictures\Screenshots\Screenshot (1201).png


### Overview
This system is designed to detect six human emotions (Joy, Fear, Anger, Love, Sadness, Surprise) from input text data. It incorporates both machine learning (ML) and deep learning (DL) models to accurately classify emotions.

### Key Features
- **Emotion Detection:** The system can classify text input into one of six emotions.
- **Machine Learning Models:** Utilizes ML algorithms such as Multinomial Naive Bayes, Logistic Regression, Random Forest, and Support Vector Machine for emotion classification.
- **Deep Learning Model (LSTM):** Incorporates a deep learning model based on Long Short-Term Memory (LSTM) neural networks for more complex emotion analysis.
- **Web Application:** Offers a user-friendly web interface for easy interaction.
- **Model Persistence:** Enables saving trained ML and DL models, as well as other necessary files for future use.

### Components
1. **Data Preprocessing:**
   - Cleans and preprocesses text data.
   - Encodes emotions for ML models.
   - Tokenizes and pads sequences for DL model.

2. **Machine Learning Models:**
   - Trains and evaluates ML models using TF-IDF vectorization.
   - Selects the best-performing model (e.g., Logistic Regression or Random Forest).

3. **Deep Learning Model (LSTM):**
   - Builds and trains an LSTM neural network for deep learning-based emotion classification.

4. **Predictive System:**
   - Provides a function to predict emotions for new text inputs using both ML and DL models.

5. **Model Persistence:**
   - Saves trained ML and DL models for future use.
   - Stores necessary files such as LabelEncoder, vocabulary information, etc.

### Usage
1. **Installation:**
   - Install required dependencies by running the provided installation commands.
   - Ensure the required versions of TensorFlow and Keras are installed.

2. **Data Preparation:**
   - Load and preprocess the training data.
   - Perform data cleaning, encoding, and vectorization.

3. **Model Training:**
   - Train ML models using various algorithms and evaluate their performance.
   - Build and train the LSTM model for deep learning-based emotion classification.

4. **Predictive System:**
   - Utilize the trained models to predict emotions for new text inputs.
   - Save the models and necessary files for future use.

5. **Web Application (Optional):**
   - Develop a web application using Streamlit for interactive emotion detection.
