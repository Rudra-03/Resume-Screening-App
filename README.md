
# Resume Category Prediction
[website](https://screening-resume.streamlit.app/
)

This is a simple web application built with Streamlit, designed to predict the category of a resume based on its content. The application uses a machine learning model trained on a dataset of resumes categorized into different job roles.





## Installation
To run this project, ensure you have Python installed on your system.
To run the application locally, follow these steps:

1. Clone this repository to your local machine:
    
        git clone https://github.com/Rudra-03/Resume-Screening-App

2. Navigate to the project directory:

        cd Resume-Screening-App

3. Install the required dependencies using pip:

        pip install -r requirements.txt

    
## Usage

After installing the dependencies, you can run the application using Streamlit. Streamlit provides a convenient way to create interactive web applications for machine learning projects.

To start the application, execute the following command in your terminal:

    streamlit run app.py


Once the application is running, you can access it through your web browser.

Upload a resume file (in .txt or .pdf format) using the provided file uploader.

The application will process the uploaded resume, clean the text, and predict the category of the resume based on its content.

The predicted category will be displayed on the screen.
## Model Building

The model is built using Python and scikit-learn. The dataset is preprocessed, vectorized, and then used to train a machine learning classifier. The trained model is saved for later use in the prediction system.
## Prediction System

The prediction system utilizes the trained model to predict the category of a given resume. It involves preprocessing the input resume, transforming it into feature vectors using TF-IDF vectorization, and then making predictions using the trained classifier.
## Files

    1. app.py: Python script containing the Streamlit application code, including preprocessing, vectorization, prediction, and user interface.

    2. requirements.txt: File listing the dependencies required to run the project, including Streamlit, NLTK, and scikit-learn.

    3. vectorizer.pkl: Pickle file containing the pre-trained TF-IDF vectorizer used for text vectorization.
    
    4. model.pkl: Pickle file containing the pre-trained machine learning model used for classification.
## Acknowledgements

- Special thanks to the authors and contributors of Streamlit, NLTK, and scikit-learn for their fantastic tools and libraries.
- This project was inspired by the need for automated resume screening in the recruitment process.
