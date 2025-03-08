# 🚀 AIAgentInsight: Intelligent Analysis & Insights Platform  

🎯 **AIAgentInsight** is a Streamlit-based web application designed to provide detailed insights and recommendations for analyzing product or company-related queries. It utilizes various agents (MultiAgents) for scraping, validating, and summarizing data from platforms like G2, Crunchbase, and DuckDuckGo, combined with the power of LLMs for query analysis and summary generation.

<p align="center">
  <img src="https://github.com/user-attachments/assets/05408381-c5a5-4075-9819-3fa29e36193d" width="800">
</p>  

---

## ✨ Key Features  
🔍 **Query Analysis** – Detects and refines search queries for precise analysis.  
📝 **G2 Reviews Extraction** – Fetches **detailed reviews**, **ratings**, and **sentiments** from G2.  
📊 **Crunchbase Insights** – Extracts and aggregates **business intelligence** from Crunchbase.  
🌎 **Web Content Search** – Performs smart searches and cleans extracted web content.  
📄 **Summary Generation** – Merges data from multiple sources into a **cohesive business report**.  

---

## ⚡ Installation & Setup  

### 🛠 Prerequisites  
- 🐍 **Python 3.10+**  
- 🔑 **Groq API Key**  
- 🔑 **Crawlbase API Key**  
- ⚙️ **Environment Variables Configuration**  

### 🚀 Steps to Install & Run  

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/polok-dev98/Multi-Agent-Product-Analyzer
   cd Multi-Agent-Product-Analyzer
2. **Set Up a Virtual Environment:**
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows: venv\Scripts\activate
3. **Install Dependencies:**
    ```bash
    pip install -r requirements.txt

4. **Run Setup Command:**
      After installation, set up the required Playwright browsers by executing:
      ```bash
      crawl4ai-setup
5. **Set Up Environment Variables:**
    Create a `.env` file in the project root directory and define the following variables:
    ```bash
    GROQ_API_KEY=your_api_key_here
    CRAWLBASE_API_KEY=your_api_key_here
6. **Run the Application:**
    Start the Streamlit application:
    ```bash
    streamlit run app.py
7. **Access the Application:**
Streamlit will provide a URL in the terminal. Copy the URL (e.g., http://localhost:8501) and paste it into your browser to access the app.


## Additional Information

### Folder Structure
- **`agents/`**: Contains the logic for query analysis, web scraping, and data validation.
- **`modules/`**: Includes utilities for content cleaning, summarization, and file reading.
- **`scrapPages/`**: Temporary folder for storing intermediate results and reports.

### Customization
- Update `prompts.yml` for modifying LLM prompt configurations.

### Troubleshooting
- Ensure environment variables are correctly set up and accessible.
- Check if the required Python version and dependencies are installed.
- Use `nest_asyncio` and `asyncio` fixes for compatibility with Streamlit on Windows.

### Example Usage
1. Run the app and enter a query like `"Analyze Tesla Inc."`.
2. Click **"Run Analysis"** and monitor the progress in the status columns.
3. View the final summary output generated by the app.

---

**Enjoy analyzing with AIAgentInsight! 🚀**









