# GitHub_Scrap

Overview:
  This project scrapes GitHub Topics and their repositories using BeautifulSoup. It collects details such as:
  
    Topic names
    
    Topic descriptions
    
    Repository owners
    
    Repository names
    
    Repository links
    
    Star counts

  The extracted data is then saved into CSV files for further analysis.

Features:

  ✅ Scrapes GitHub topics and repositories
  
  ✅ Extracts repository metadata (name, owner, stars, and URL)
  
  ✅ Saves data into structured CSV files
  
  ✅ Handles errors and avoids redundant requests

Installation:

  Clone this repository
  
    git clone https://github.com/yourusername/github-topic-scraper.git
  
  Navigate to the project folder:
  
    cd github-topic-scraper
  
  Install required dependencies:
  
    pip install -r requirements.txt

Usage:

  Run the script using:
  
    python script.py
  
  The script will scrape GitHub topics and repositories every hour and save the data in CSV files:
  
    GitHub_Scrap.csv → Topic details
    
    GitHub_Repositories.csv → Repository details 
    
    Dependencies
    
    requests 
    
    beautifulsoup4
    
    pandas
    
    matplotlib
    
    seaborn
    
    
Output:

  The script generates two CSV files:
  
    GitHub_Scrap.csv → Contains topic names, descriptions, and links.
    
    GitHub_Repositories.csv → Contains repository details, including owner, name, stars, and URL.
    
Contributing:

    Feel free to fork this repository and submit pull requests.

License:

  This project is licensed under the MIT License.
