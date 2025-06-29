# Permalink_Crawling_Lab


 Permalink Crawling Lab

This project is a hands-on web crawling lab focused on extracting news article content using permanent URLs (permalinks). It compares multiple Python libraries for scraping and content extraction, including newspaper3k, trafilatura, readability-lxml, and BeautifulSoup.

<br>
📁 Project Structure
Permalink_Crawling_Lab.ipynb: Main notebook for testing and comparing different crawling methods.
Input: Excel file containing permalinks to news articles.
Output: Extracted and cleaned article content stored in DataFrame columns.
<br>

🧰 Libraries Used
requests
beautifulsoup4
readability-lxml
trafilatura
newspaper3k
tqdm
pandas
<br>

🔍 Crawling Methods Compared
Library	Features	Strengths
newspaper3k	Article metadata, full text extraction	Easy-to-use, multilingual
trafilatura	Advanced content extraction for news articles	Fast, well-structured output
readability-lxml	Simplified DOM parsing for main content	Lightweight, good for blog/news
BeautifulSoup	Manual tag parsing	Full control over HTML parsing
<br>

🏁 How to Run
pip install -r requirements.txt
Then open the notebook:

jupyter notebook Permalink_Crawling_Lab.ipynb
Ensure your input Excel file (with permalinks) is properly loaded before running each method.

<br>
💡 Use Cases
News article aggregation
Content scraping for NLP or sentiment analysis
Comparative benchmarking of scraping tools
<br>

🧪 Sample Output
Each method outputs a cleaned version of the main article text in a new DataFrame column, enabling comparison of completeness and quality.

<br>

📝 Author
Jehyun Sung

<br>
