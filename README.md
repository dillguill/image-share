# Django Image Sharing Application

## Overview
This is a beginner-friendly Django project: a simple Image Sharing application. It’s designed to reinforce foundational web development concepts using Django, including creating models, views, forms, and templates.

## Features
- Allows users to:
  - View a gallery of shared images on the home page.
  - Click on an image to view its details on a separate page.
  - Upload new images with descriptive text via a form.
- Includes:
  - Feedback messages for successful uploads.
  - Validation for file uploads.
  - A modern, responsive design using **Bootstrap** for styling.
- Demonstrates key Django concepts:
  - **Models**: Defining and interacting with the database.
  - **Forms**: Creating and processing user inputs.
  - **Views**: Handling logic for rendering templates and forms.
  - **Templates**: Displaying content dynamically using template tags.
  - **Messages Framework**: Providing user feedback.

## What I Learned
- Deepened understanding of Django fundamentals, including:
  - Setting up views with `TemplateView`, `DetailView`, and `FormView`.
  - Using `Model` objects to interact with a database.
  - Handling file uploads in Django forms and saving them to the media directory.
  - Displaying dynamic content using Django's template language.
  - Enhancing the user experience with Bootstrap for responsive and modern design.
  - Utilizing Django’s `messages` framework for feedback.

## Example Workflow
1. **Home Page**: Displays all uploaded images in a grid layout.
2. **Detail Page**: Clicking on an image opens a detailed view with the full-size image and its description.
3. **Add Post**: Users can upload a new image with a description via a form, receiving confirmation upon success.

## How to Run
1. Ensure you have **Python 3.9+** and **Django 4.x** installed. You can download Python from [python.org](https://python.org) and install Django via pip:
   ```bash
   pip install django
   ```
2. Clone the repository or download the project files.
3. Navigate to the project directory and run the following command to start the development server:
   ```bash
   python manage.py runserver
   ```
4. Open your browser and navigate to `http://127.0.0.1:8000/` to access the application.

## Credits
This project was based on the instructions from the Django section of the [Ultimate 2024 Fullstack Web Development Bootcamp](https://www.udemy.com/course/the-ultimate-fullstack-web-development-bootcamp/) on Udemy. Special thanks to the instructor **Kalob Taulien** for his guidance.
