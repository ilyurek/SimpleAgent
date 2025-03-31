# SimpleAgent 🕵️‍♂️
*A simple AI-powered research agent using LangChain and OpenAI API.*

## Overview
SimpleAgent is a Python-based AI agent that searches Wikipedia and the internet for information, then saves the results into a `.txt` file. It leverages **LangChain** for structured AI interactions and the **OpenAI API** for natural language understanding.

## Features
✅ Search Wikipedia and the internet for relevant data  
✅ Use OpenAI's API to process and summarize information  
✅ Save the results into a `.txt` file for easy access  
✅ Lightweight and easy to use  

## Installation
1. **Clone the repository:**  
   ```sh
   git clone https://github.com/ilyurek/SimpleAgent.git
   cd SimpleAgent
   ```
2. **Create and activate a virtual environment (optional but recommended):**  
   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows use: venv\Scripts\activate
   ```
3. **Install dependencies:**  
   ```sh
   pip install -r requirements.txt
   ```
4. **Set up your API keys:**  
   - Create a `.env` file in the project root and add your OpenAI API key:  
     ```ini
     OPENAI_API_KEY=your_api_key_here
     ```

## Usage
Run the agent with:  
```sh
python main.py
```
It will prompt you for a search query, fetch the information, and save it to a `.txt` file.

## Example Output
```
Enter your search query: Artificial Intelligence
Searching Wikipedia...
Saving results to output.txt...
Done!
```
Contents of `output.txt`:  
```
Artificial intelligence (AI) is intelligence demonstrated by machines, as opposed to the natural intelligence displayed by humans or animals...
```

## Technologies Used
🔹 **Python** – Main programming language  
🔹 **LangChain** – AI-driven workflow  
🔹 **OpenAI API** – Natural language processing  
🔹 **Requests** – Fetching internet data  
🔹 **Wikipedia API** – Searching Wikipedia  

## Contributing
Contributions are welcome! To contribute:  
1. Fork the repo  
2. Create a new branch (`feature-name`)  
3. Commit your changes  
4. Open a pull request  

## License
📜 MIT License – Free to use and modify!
