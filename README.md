# ai_text-completion-project
Understand how Generative AI processes input prompts to generate coherent and relevant text.  Set up and interact with a pre-trained AI model through an API.  Experiment with prompt design and model parameters to evaluate output quality.  Reflect on the capabilities and limitations of the AI model.

# Generative AI Text Completion App

This project demonstrates how to use a pre-trained Generative AI model via an API to generate text completions based on user prompts.

## Features

- Accepts user input
- Interacts with OpenAI's GPT-3.5 Turbo
- Allows dynamic adjustment of `temperature` and `max_tokens`
- Displays coherent and contextual responses
- Includes error handling and input validation

## Setup Instructions

1. **Clone the Repository or Open the Notebook**

2. **Install Dependencies**  
   Run the following in your terminal or notebook:
   
3. **Create a `.env` File**  
Add your OpenAI API key:


4. **Run the Notebook**  
Use any Jupyter Notebook environment and follow the step-by-step cells.

## Sample Prompts to Try

- “Once upon a time, there was a robot who…”
- “Explain photosynthesis to a 10-year-old.”
- “Write a haiku about the ocean.”
- “Summarize the plot of Romeo and Juliet.”

## Notes

- You can modify `temperature` for creativity and `max_tokens` for response length.
- Includes test prompts and output logging.

## License

Free to use for educational and personal projects.


⚙️ Usage
Once you’ve set up the environment and added your API key, you can use the application as follows:

🔄 Running the Notebook
Launch the Jupyter Notebook:
Open Generative_Ai_Project.ipynb in JupyterLab, Jupyter Notebook, or a compatible IDE like VS Code.

Step-by-Step Execution:

Run the setup cells to install and import required libraries.

Enter your input prompt when prompted.

Optionally customize:

Temperature: Controls randomness (0.0 = deterministic, 1.0 = creative).

Max Tokens: Controls response length.

Examples:

text
Copy code
Prompt: Once upon a time, there was a robot who...
Temperature: 0.8
Max Tokens: 100
Output:
A coherent and relevant AI-generated response is printed in the cell output.

Run Multiple Times:
You can execute the interaction cell multiple times to experiment with new prompts and parameters.

📦 Dependencies
The project relies on the following Python packages:

Package	Description
openai	Used to interact with OpenAI's GPT-3.5 model API
python-dotenv	Loads environment variables securely from .env file
os	Standard Python library to access environment variables
dotenv	For managing secrets securely (API key)

Installation
Install the required libraries with:

bash
Copy code
pip install openai python-dotenv
