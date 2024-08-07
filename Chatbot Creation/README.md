# Simple Chatbot using spaCy

This project involves creating a simple chatbot that can engage in basic conversations with users using the spaCy library in Python.

## Project Aim

Develop a simple chatbot that can engage in basic conversations with users.

## Technologies Used

- Python
- spaCy

## Project Structure

- `Chatbot_Creation.ipynb`: The Jupyter notebook containing the entire project code, from importing libraries to running the chatbot.

## Installation

To run this project, you need to have the following dependencies installed:

- spacy

You can install the required library using pip:

```bash
pip install spacy
python -m spacy download en_core_web_sm
```

## Usage

### Google Colab

1. Open Google Colab.
2. Upload the `Chatbot_Creation.ipynb` notebook.
3. Run the cells in the notebook to execute the entire project.

### Jupyter Notebook

1. Ensure you have Jupyter Notebook installed. You can install it using Anaconda or pip:
   ```bash
   pip install notebook
   ```
2. Download the `Chatbot_Creation.ipynb` notebook and place it in your working directory.
3. Open the notebook in Jupyter:
   ```bash
   jupyter notebook Chatbot_Creation.ipynb
   ```
4. Run the cells in the notebook to execute the entire project.

## Steps to Develop the Chatbot

1. **Set Up Environment:**
   - Install necessary libraries.
   - Load spaCy model.

2. **Define Patterns and Responses:**
   - Create patterns for matching user inputs.
   - Define corresponding responses.

3. **Interactive Chat Session:**
   - Set up a loop to handle user input and provide responses.

## Example Patterns and Responses

- `hi` → `Hello! How can I assist you today?`
- `how are you` → `I am an AI, so I do not have feelings, but I am here to help you! How about you?`
- `what is your name` → `I am a simple chatbot created to assist you.`
- `bye` → `Goodbye! Have a great day!`
- `tell me a joke` → `Why don’t scientists trust atoms? Because they make up everything!`

For more detailed patterns and responses, refer to the `Chatbot_Creation.ipynb` notebook.

## License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/muhammadhuzaifayousaf/Codeclause_AI_Internship/blob/main/LICENSE) file for details.

---

**Note:** For detailed code and step-by-step implementation, refer to the `Chatbot Creation.ipynb` notebook.

[Open Chatbot Creation.ipynb in Google Colab](https://colab.research.google.com/drive/12m5la-jL_Fk2CuQXPlnbAMwiXp2XV6Sy?usp=sharing)
