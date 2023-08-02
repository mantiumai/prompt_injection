# Nmap Command Translator App
This is a simple Flask application that leverages OpenAI's GPT-3 model to translate user inputs into `nmap` commands. The application takes a user's input via a simple form, sends the input to OpenAI, and the generated `nmap` command is displayed back to the user.

## Features
- User input validation
- API response validation
- Simple and intuitive UI

## Requirements
- Python 3.6+
- Flask
- python-dotenv
- openai

## Getting Started
1. Clone this repository:

    ```
    git clone https://github.com/<your-github-username>/nmap-translator.git
    ```
    
2. Navigate into the project directory:

    ```
    cd nmap-translator
    ```

3. Install the required packages:

    ```
    pip install -r requirements.txt
    ```

4. Create a `.env` file in the project root and add your OpenAI API key:

    ```
    OPENAI_API_KEY=your-openai-api-key
    ```

5. Run the application:

    ```
    python app.py
    ```

6. Open your web browser and navigate to `http://localhost:5000`.

## Usage
Enter your desired action into the text box and click on the 'Translate' button. The application will generate the corresponding `nmap` command.

## License
This project is licensed under the terms of the MIT license.