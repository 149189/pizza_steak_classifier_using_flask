# Pizza vs. Steak Image Classifier
## Project Overview
This project is a Flask-based web application that predicts whether an uploaded image is of a pizza or a steak. It uses a pre-trained machine learning model to classify images in real time, providing users with an intuitive interface for uploading and getting results.

## Features
1. Upload an image to classify it as either pizza or steak.
2. Processes images securely and provides instant results.
3. Simple, user-friendly interface with HTML and Flask.
4. Extensible for adding more classes or improving predictions.

## Technologies Used
1. Backend:
    - Flask (Python web framework)
    - TensorFlow (Deep learning model)
    - Pillow (Image preprocessing)
    - NumPy (Numerical processing)
2. Frontend:
    - HTML for the web interface

      
## Installation Instructions:
1. Clone the repository:
    - git clone <repository-url>
    - cd project-folder
2. Install dependencies:
    - pip install -r requirements.txt
3. Ensure the model file (classifier.h5) is placed in the model/ folder.
4. Run the Flask application:
    - python app.py
5. Open your browser and go to:
    - http://127.0.0.1:5000/

## Usage
1. Visit the root URL (/) to access the image upload page.
2. Upload an image file (jpg, jpeg, png).
3. Submit the image to see whether it’s classified as pizza or steak.

## File Structure:
    -- project/
      │
      ├── app.py                # Main Flask application
      ├── model/                # Folder for the trained model
      │   └── classifier.h5     # Pre-trained model file
      ├── templates/            # Folder for HTML templates
      │   └── index.html        # Upload form
      ├── uploads/              # Folder to store uploaded images temporarily
      ├── requirements.txt      # Python dependencies
      └── README.md             # Project documentation

## Future Improvements
 - Add support for additional food categories.
 - Enhance the UI with Bootstrap or JavaScript for a better user experience.
 - Deploy the application to a cloud platform like Heroku, AWS, or Google Cloud.
 - Implement user authentication and save user predictions

## Dependencies 
  - Flask
  - Tensorflow
  - Pillow
  - Numpy
  - Werkzeug
Install all dependencies with:
   -- pip install -r requirements.txt

## Contribuiting
Contributions are welcome! Please fork the repository, create a new branch, and submit a pull request with your changes.

## License
This project is licensed under the MIT License. You’re free to use, modify, and distribute this application as per the terms of the license.

## Author
 - Name: Kaustubh Ratwadkar
 - Contact: https://github.com/149189


Enjoy classifying your favorite foods! 🍕🥩


