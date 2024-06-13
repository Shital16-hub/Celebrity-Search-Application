# Celebrity Search with OpenAI and LangChain

This repository contains a Streamlit web application that leverages OpenAI's API and the LangChain library to provide detailed information about celebrities. The application uses a series of chained prompts to gather and display information such as the celebrity's biography, birth date, and major world events around the time of their birth.

## Features

- **Streamlit Integration**: Provides a user-friendly web interface.
- **Chained Prompts**: Utilizes sequential chains of prompts to fetch detailed information.
- **Memory Buffers**: Stores conversation history to maintain context.
- **OpenAI API**: Powered by OpenAI's language model for generating responses.

## How to Use

1. **Input**: Enter the name of a celebrity you want to know about.
2. **Output**: The app displays the celebrity's biography, birth date, and major events around their birth year.
3. **Expanders**: Additional details are available in expandable sections for deeper insights.

## Setup

1. Clone the repository.
2. Install required packages:
   ```sh
   pip install -r requirements.txt
   ```
3. Run the Streamlit application:
   ```sh
   streamlit run main.py
   ```

## Files

- `main.py`: Main application script.
- `constants.py`: Contains API keys and other constants.

---

This repository provides an engaging way to explore celebrity information through an interactive web application, leveraging the power of AI for a rich user experience.
