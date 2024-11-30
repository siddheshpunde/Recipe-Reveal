# Recipe Reveal

**Recipe Reveal** is an AI-powered application that helps users identify dishes from images and provides a detailed recipe, including ingredients and cooking instructions. The app uses Google Gemini Vision API for dish recognition and Streamlit for an interactive user interface.

---

## Demo Video

👉 Watch the demo of **Recipe Reveal**: [Click Here to Watch](https://drive.google.com/file/d/15pJcc9kn_dm-TQjrrQlI9VuQhPpCIu8F/view?usp=sharing
)
 

---

## Features

- **Image Upload**: Users can upload an image of a dish.
- **Dish Recognition**: The app identifies the dish using Google Gemini Vision API.
- **Recipe Suggestions**: Get detailed recipes, including:
  - Dish name
  - List of ingredients
  - Step-by-step cooking instructions
- **Streamlit Interface**: A clean, user-friendly platform to interact with the app.

---

## Tools and Technologies

### Programming and Frameworks
- **Python**: Core programming language used.
- **Streamlit**: Framework for building the interactive web app.

### AI & APIs
- **Google Gemini Vision API**: For analyzing images and generating recipes.

### Libraries
- **Pillow**: For image processing.
- **Python-dotenv**: To manage environment variables.
- **google.generativeai**: For Google Gemini API integration.

### Deployment
- **Streamlit Cloud** (optional): Deploy your app for public access.

---

## How It Works

1. **Image Upload**:
   - Users upload an image of a dish.
   - The app processes the image.

2. **Data Processing**:
   - A predefined text prompt is combined with the image data.
   - The data is sent to the Google Gemini Vision API.

3. **Output**:
   - The API returns:
     - Dish name.
     - Ingredients list.
     - Cooking instructions.

4. **Display**:
   - The app displays the results in a structured, readable format.

---

