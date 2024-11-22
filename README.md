# Chatbot with Streamlit and Arize Phoenix Observability

Welcome to the **LLM Chatbot Application** powered by Streamlit and integrated with **Arize Phoenix**, an open-source observability platform for large language models (LLMs). This application demonstrates the importance of tracing, evaluation, and observability in the lifecycle of LLM-based applications. 

---

## 🚀 **Why Observability for LLMs?**

You wouldn’t write code without **tests** and **logs**. So why treat your large language models any differently? 

As LLMs become integral to application logic, monitoring, evaluating, and tracing their behavior is critical for maintaining trust and ensuring performance. **Arize Phoenix** simplifies these tasks, offering robust tools to visualize, trace, and analyze LLM outputs.

Other observability tools should be mentioned like https://www.openlayer.com/ and https://www.galileo.ai/. Let me know if you would like to see them featured here.

---

## 🛠️ **Features**

1. **Interactive Chatbot**  
   Built with Streamlit’s intuitive framework, this chatbot interface allows users to interact with an LLM and see real-time responses.  

2. **Integrated Observability**  
   The app uses **Arize Phoenix** to:  
   - **Trace Conversations**: Monitor input-output pairs to understand the flow of interactions.  
   - **Evaluate Responses**: Automatically score responses for quality and relevance.  
   - **Debug Issues**: Quickly identify outliers and problematic outputs.

3. **LLM Evaluation Pipeline**  
   The app demonstrates best practices for integrating evaluations into your LLM workflow, ensuring your model is always improving.

---

## 🏗️ **Getting Started**

### Prerequisites

- API key for OpenAI
- An **Arize Phoenix** account for observability integration.

### Installation

1. Clone this repository:  
   ```bash
   git clone https://github.com/carlosmlribeiro/phoenix-streamlit-template.git
   cd phoenix-streamlit-template
   ```

2. Install dependencies:  
   ```bash
   pip install -r requirements.txt
   ```

### Running the App

Start the Streamlit app with:  
```bash
streamlit run app.py
```

Navigate to `http://localhost:8501` in your browser to interact with the chatbot.

---

## 📊 **Observability with Arize Phoenix**

1. **Data Ingestion**  
   This app streams input-output pairs and metadata (e.g., response time, user feedback) directly to Arize Phoenix.

2. **Dashboard Insights**  
   Use Phoenix’s dashboards to:  
   - Track key metrics like response latency and quality scores.  
   - Visualize trends and anomalies in your model’s behavior.  
   - Drill down into problematic conversations for debugging.

3. **Continuous Evaluation**  
   The app includes a feedback loop for scoring responses, enabling iterative improvements to the LLM.


---

## 🤝 **Contributing**

Contributions are welcome! Please submit a pull request or open an issue to suggest improvements or report bugs.

---

## 📜 **License**

This project is licensed under the MIT License. See the `LICENSE` file for details.

---

## 📬 **Questions?**

For support or feedback, contact me at https://www.linkedin.com/in/carlosmlribeiro.