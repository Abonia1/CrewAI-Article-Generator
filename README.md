
# 📝 CrewAI Article Generator

CrewAI Article Generator is a Streamlit-based application designed to produce comprehensive, engaging articles on any topic. By leveraging advanced AI agents and language models, this system streamlines the process of research and content creation, making it perfect for analysts, journalists, and content creators.

---

## 🚀 Features

- **Two AI Agents**:
  - **Senior Research Analyst**: Conducts in-depth research on emerging trends and technologies.
  - **Technology Journalist**: Crafts well-structured, accessible articles for a general audience.
  
- **Automated Workflow**:
  - Research and writing tasks are handled sequentially.
  - Generates markdown-formatted articles with clean sections and clear narratives.

- **Customizable Topics**:
  - Input any topic to receive a detailed, polished article.

- **Downloadable Output**:
  - Download the generated article in markdown format.

---

## 🛠️ Technologies Used

- **Streamlit**: For creating the interactive UI.
- **CrewAI**: To manage AI agents and tasks.
- **LangChain**: For advanced LLM configurations and tools.
- **Ollama**: Provides the backend for the `mistral` language model.
- **DuckDuckGoSearchRun**: As an optional tool for web-based queries.

---

## 🖥️ How It Works

1. **Input a Topic**: Provide a subject, e.g., "Quantum Computing" or "Green Energy."
2. **Research Task**:
   - The Research Analyst collects data on:
     - Current trends and breakthroughs.
     - Key players, challenges, and market opportunities.
     - Predictions and industry impacts.
3. **Writing Task**:
   - The Technology Journalist creates a markdown-formatted article:
     - Includes examples, analogies, and future perspectives.
4. **Output**:
   - Displays the article in the UI.
   - Allows you to download it in `.md` format.

---

## 🔧 Setup and Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Abonia1/CrewAI-Article-Generator
   ```

2. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Set up Ollama**:
   - Install and configure Ollama locally.
   - Ensure the `mistral` model is available.

4. **Run the application**:
   ```bash
   streamlit run app.py
   ```

---

## ⚙️ Configuration

- **Agents**: Configured with backstories, goals, and roles.
- **Language Model**:
  - Base: `ollama/mistral`
  - URL: `http://localhost:11434`
  - Adjustable temperature settings.

---

## 📋 Example Usage

1. Start the Streamlit app:
   ```bash
   streamlit run article_generator.py
   ```

2. Enter a topic, e.g., "Artificial Intelligence in Healthcare."
3. Click the **Generate Article** button.
4. View and download the generated article.

---

## 🙌 Contributions

Contributions are welcome! Feel free to fork the repository and submit a pull request.

---

## 📞 Support

For any issues or questions, please [open an issue](https://github.com/Abonia1/CrewAI-Article-Generator/issues) in the repository.

---

Happy Writing! ✍️
