# LangChain Streamlit Email Conversion App

![Screenshot from 2024-03-18 23-04-57.png](Screenshot%20from%202024-03-18%2023-04-57.png)
## Overview

This Streamlit app, powered by LangChain and OpenAI, facilitates the conversion of informal emails into a more professional format. It allows users to select the desired tone (formal or informal) and English dialect (American or British English) for their email. The app then generates a professionally formatted version of the input email based on the selected options.

## Features

- **Email Conversion**: Users can input their email text and select the desired tone and English dialect for conversion.
- **Tone Selection**: Users can choose between formal and informal tones for their email.
- **Dialect Selection**: Users can choose between American English and British English dialects.
- **Example Display**: An example email is provided to demonstrate the expected format.
- **OpenAI Integration**: Utilizes OpenAI's language model for text conversion.
- **Streamlit Interface**: The app interface is built using Streamlit, making it easy to use and interact with.

## Usage

1. **Select Options**: Choose the tone (formal or informal) and English dialect (American or British English).
2. **Input Email**: Enter your email text in the provided text area.
3. **View Example**: Click on the "*See An Example*" button to view an example of the converted email.
4. **Converted Email**: The app will generate and display the professionally formatted version of the input email based on the selected options.

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/your-repository.git
    ```

2. Install dependencies:

    ```bash
    pip install -r requirements.txt
    ```

3. Set up environment variables:

    - Obtain an API key from OpenAI.
    - Create a `.env` file in the root directory.
    - Add your OpenAI API key to the `.env` file:

        ```
        OPEN_API_KEY=your-openai-api-key
        ```

4. Run the Streamlit app:

    ```bash
    streamlit run app.py
    ```

5. Access the app in your browser at the provided URL.

## Requirements

- Python 3.x
- Streamlit
- LangChain
- OpenAI
- Dotenv

## Credits

- [LangChain](https://www.langchain.com/)
- [OpenAI](https://openai.com/)
- [@GregKamradt](https://github.com/gkamradt)

## License

This project is licensed under the [MIT License](LICENSE).
