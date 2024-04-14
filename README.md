# Celebrity Search Result using OpenAI API
This project utilizes OpenAI's GPT-3 API to generate information about celebrities based on user input. The application prompts the user to enter the name of a celebrity and provides information such as the celebrity's date of birth and major events that occurred around that date.

## Getting Started
To run the application locally, follow these steps:

1. Clone the repository to your local machine:
```bash
git clone https://github.com/your_username/celebrity-search.git
``` 
2. Install the required dependencies by running:

```bash
pip install -r requirements.txt
```

3. Set up your OpenAI API key by replacing 'private key' in constants.py with your actual API key.

4. Run the Streamlit application:

```bash
streamlit run app.py
```
5. Access the application in your web browser at http://localhost:8501.

## Usage
1. Enter the name of the celebrity you want to search for in the provided text input field.
2. Press the Enter key or click on the Search button.
3. The application will display information about the celebrity, including their date of birth and major events around that date.

## Components
### 'app.py'
This file contains the main Streamlit application code. It handles user input, interacts with the OpenAI API, and displays the search results.

### 'constants.py'
This file contains sensitive information such as the OpenAI API key. Replace 'private key' with your actual API key before running the application.

### 'requirements.txt'
This file lists all the Python dependencies required to run the application. Install them using pip install -r requirements.txt.

### 'Contributing'
Contributions are welcome! If you'd like to contribute to this project, please fork the repository and submit a pull request with your changes.
