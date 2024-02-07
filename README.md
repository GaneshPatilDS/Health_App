
---

# Gemini Health App

Gemini Health App is a Streamlit application that utilizes the Google Gemini Pro Vision API to analyze images of food items and calculate their total calories. It also provides details about each food item's calorie intake in a specified format and indicates whether the food is healthy or not.

## Features

- **Image Upload**: Users can upload images of food items in common formats such as JPG, JPEG, and PNG.
- **Calorie Calculation**: The app calculates the total calories of the food items detected in the uploaded image.
- **Nutritionist Guidance**: Users receive detailed information about each food item's calorie intake in a specified format.
- **Health Evaluation**: The app indicates whether the food items are considered healthy or not.

## Getting Started

To run the Gemini Health App locally, follow these steps:

1. Clone this repository to your local machine.
2. Install the required dependencies by running `pip install -r requirements.txt`.
3. Set up your Google API key and other environment variables as specified in the `.env` file.
4. Run the Streamlit app by executing `streamlit run app.py` in your terminal.

## Usage

1. Upload an image of food items using the file uploader.
2. Click the "Tell me the total calories" button to analyze the image and get the calorie details.
3. View the response, which includes the total calories and details of each food item detected in the image.

## Technologies Used

- Streamlit: For building the interactive web application.
- Google Gemini Pro Vision API: For image analysis and content generation.
- PIL (Python Imaging Library): For image processing and manipulation.



## Acknowledgements

- Special thanks to [Google Generative AI](https://cloud.google.com/generative-ai) for providing access to the Gemini Pro Vision API.

---

