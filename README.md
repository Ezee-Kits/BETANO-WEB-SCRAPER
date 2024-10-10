# Betano Betting Scraper

This **Betano Betting Scraper** automates the process of extracting betting data from the Betano platform. The script is designed to collect odds for various sports matches, making it a valuable tool for identifying betting opportunities and potential arbitrage situations.

## 📌 Features

- **Real-Time Data Extraction**: Gathers live betting data for upcoming matches on Betano.
- **Multi-Market Support**: Extracts odds for various betting markets, including match results and total goals.
- **User-Friendly Structure**: The code is organized and easy for developers to understand and modify.
- **CSV Output**: Saves extracted betting data in a structured CSV format for easy analysis.
- **Data Deduplication**: Automatically removes duplicate entries to ensure clean data storage.

## 🚀 How It Works

1. **Initialization**: The script initializes the Selenium WebDriver to open the Betano website.
2. **Scrolling**: It scrolls through the page to load all available betting options.
3. **Data Extraction**: The script captures the match time, home team, away team, and odds for each match.
4. **Output**: The results are saved in a CSV file for further analysis.

### Key Components:

- **Web Scraping**: Utilizes Selenium and BeautifulSoup for navigating the website and extracting data.
- **Data Structuring**: Organizes the scraped data into a dictionary format for easy saving.
- **CSV File Management**: Handles the creation and management of CSV files for output.

## 🛠️ Requirements

Before running the script, ensure the following packages are installed:

- **Python 3.x**
- **Selenium**
- **BeautifulSoup4**
- **Pandas**
- **lxml**

Install the required packages using pip:
```bash
pip install selenium beautifulsoup4 pandas lxml
```

## 🏃 How to Run the Script

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/YourUsername/Betano-Betting-Scraper.git
   ```

2. **Set up ChromeDriver**:  
   Download and install [ChromeDriver](https://sites.google.com/a/chromium.org/chromedriver/) for your browser. Ensure the ChromeDriver is in your system path.

3. **Run the Python Script**:
   ```bash
   python betano_scraper.py
   ```

4. **View Results**:  
   The scraped data will be saved in a CSV file located at the specified path.

## 📁 Output

The output CSV file will contain the following fields:
- **TIME**: The scheduled time of the match.
- **HOME TEAM**: The name of the home team.
- **AWAY TEAM**: The name of the away team.
- **HOME ODD**: Odds for the home team to win.
- **DRAW ODD**: Odds for a draw.
- **AWAY ODD**: Odds for the away team to win.
- **BOOKMAKER**: The name of the bookmaker (in this case, Betano).

## 🔧 Future Improvements

- **Error Handling**: Implement more robust error handling to manage unexpected changes in the website structure.
- **Enhanced Data Analysis**: Integrate data analysis tools for better insights into betting patterns.
- **User Interface**: Develop a graphical user interface (GUI) for easier user interaction.
- **Mobile Compatibility**: Adapt the script for mobile devices to facilitate on-the-go data extraction.

## 📝 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## 🤝 Contributing

Feel free to contribute by opening issues, suggesting improvements, or submitting pull requests. All feedback is welcome!
