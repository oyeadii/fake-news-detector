# newsLime

News Lime is a Flask-based web application that employs a machine learning model to determine the authenticity of news articles. It helps users discern whether a given news article is fake or real, offering a valuable tool to combat misinformation and fake news.

## Features

- **Fake News Detection:** newsLime uses a powerful machine learning model to predict whether a news article is real or fake.
- **User-Friendly Web Interface:** The Flask web application provides an easy-to-use interface for users to input news articles and receive predictions.
- **Data Processing:** The application leverages data processing libraries like Numpy and Pandas to prepare the text data for the model.
- **Scalability:** As it's built on Flask, you can easily scale and deploy this application to reach a wider audience.

## Getting Started

Follow these steps to get the newsLime web application up and running on your local machine:

### Prerequisites

- Python 3.9
- Virtual environment (recommended)

### Installation

1. Clone the repository:
```bash
   git clone https://github.com/yourusername/newsLime.git

2. Change to the project directory:
```bash
   cd newsLime

3. Create a virtual environment (optional but recommended):
```bash
   python -m venv venv

4. Activate the virtual environment:
On Windows:
```bash
   venv\Scripts\activate

On macOS and Linux:
```bash
   source venv/bin/activate

5. Install the required packages:
```bash
   pip install -r requirements.txt

6. Run the Flask application:
```bash
   python app.py

### Access the application in your web browser by navigating to http://localhost:5000.

## Usage
Enter the text of the news article you want to analyze in the provided input field on the web interface.
Click the "Check Authenticity" button to get the model's prediction.
The application will display whether the news article is "Real" or "Fake."
Technology Stack
Flask: Web application framework
Python: Language for machine learning and web development
Scikit-learn: Machine learning library for model training and prediction
Numpy and Pandas: Data processing libraries
Contributing
If you'd like to contribute to newsLime, please follow these steps:

Fork the repository on GitHub.
Create a new branch for your feature or bug fix.
Make your changes and commit them.
Push your changes to your fork and submit a pull request.
License
This project is licensed under the MIT License. See the LICENSE file for details.

Contact
If you have any questions or suggestions regarding newsLime, feel free to contact us at your@email.com.

Thank you for using newsLime!
