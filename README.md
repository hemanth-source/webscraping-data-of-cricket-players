

Cricket Stats Scraper – ICC Men's T20 World Cup 2024  

This repository contains a Python script that scrapes player statistics from the **ICC Men's T20 World Cup 2024** page on **Cricbuzz** using **BeautifulSoup** and **requests**. The extracted data is then saved into a CSV file for further analysis.  

 Features  
- Web Scraping: Extracts player statistics from Cricbuzz.  
- BeautifulSoup & Requests: Used to parse and navigate the HTML structure.  
- Data Processing: Extracts table headers and player stats dynamically.  
- Pandas Integration: Saves the structured data into a CSV file for analysis.  

 How It Works  
1. Fetch Data: The script sends a request to the Cricbuzz stats page.  
2. Parse HTML: Uses BeautifulSoup to locate the stats table.  
3. Extract Data: Captures player statistics and processes it into a structured format.  
4. Save as CSV: Stores the extracted data in a CSV file for easy access.  

 Installation  

pip install beautifulsoup4 requests pandas

 Usage  
Run the script using:  

python scraper.py

 Output  
A CSV file (`Companies.csv`) will be generated containing cricket player statistics.  
 
