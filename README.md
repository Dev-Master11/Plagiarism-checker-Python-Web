# Plagiarism Checker Web Application

This **Plagiarism Checker** web application is developed using **Flask**, **Python**, and **scikit-learn**. The application allows users to compare two text samples and calculates a similarity score to detect potential plagiarism.

## Features
- Users can input two text samples and compare their similarity.
- Utilizes **TF-IDF Vectorizer** and **Cosine Similarity** algorithms to assess the text similarity.
- Displays the similarity score as a percentage to indicate potential plagiarism.
- Fully responsive design for seamless access on both desktop and mobile devices.

## Technologies Used
- **Flask**: Lightweight web framework for Python used to build the web application.
- **scikit-learn**: Machine learning library for implementing **TF-IDF** and **Cosine Similarity**.
- **HTML/CSS/JavaScript**: Front-end technologies used for the user interface.
- **Python**: Back-end programming language for processing the plagiarism check.

## Setup Instructions

### Prerequisites

1. **Python** version 3.6 or higher.
2. **Flask** and **scikit-learn** libraries (installation instructions below).

### Installation Steps

1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/Dev-Master11Plagiarism-checker-Python-Web.git
   cd Plagiarism-checker-Python-Web
   ```
   
2. Create and activate a virtual environment:
   ```bash
   python3 -m venv venv
   source venv/bin/activate  # For Windows, use `venv\Scripts\activate`
   ```

3. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
   Alternatively, you can manually install the dependencies:
   ```bash
   pip install flask scikit-learn
   ```

4. Run the Flask application:
   ```bash
   python app.py
   ```
   The application will be hosted at `http://127.0.0.1:5000/` in your browser.

### Usage

1. Open a browser and go to `http://127.0.0.1:5000/`.
2. Enter two text samples into the input fields.
3. Click the **Check Similarity** button.
4. The app will display the similarity score as a percentage.

### Example

**Input 1:**
```
The quick brown fox jumps over the lazy dog.
```

**Input 2:**
```
A fast brown fox leaps over a lazy dog.
```

**Output:**
```
Plagiarism Similarity: 72.34%
```

## Folder Structure
```
/plagiarism-checker
    /static
        styles.css
        script.js
    /templates
        index.html
    app.py
    requirements.txt
    README.md
```
