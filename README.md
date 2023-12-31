# WEB-SCRAPING-AMAZONS-BEST-SELLER-DATA-USING-PYTHON
This repository contains a collection of files and scripts focused on Web Scraping the top 30 best selling products in every category on Amazon India and a visualization performed in Tableau with the aim to gain a deeper understanding of consumer preferences and market trends.

* This project was performed in Jupyter Notebook

Project Files:
* Amazon Web Scraping.ipynb: This file contains the Python Script used to extract data from Amazon India's Website
* AmazonBestSellers.csv: This file contains the scraped data of the top 30 best selling products in every category as of 07/09/2023 performed using ScraperApi and the Python library BeautifulSoup
* Amazon_Web_Scraping_Cleaned_Data.csv: This file contains data after data cleaning was performed using the Python library Pandas
* Amazon Bestseller's Dashboard.twbx: This file contains the Dashboard created in Tableau

To run this project:
1. Clone or download this repository to your local machine
2. Ensure you have Anaconda downloaded on your computer or download it from here: https://www.anaconda.com/download
3. This project utilizes an api key to allow access to the Amazon website. Create an account in ScraperApi from this link: https://dashboard.scraperapi.com/login and replace the api key in the python code with your api key.
4. Open Anaconda and launch Jupyter Notebook.
5. Upload the file "Amazon Web Scraping.ipynb"
6. Run each code and your extracted data will be saved in a file named "AmazonBestSellers.csv". Take note that the data extracted from Amazon's best-selling website will differ from the one provided above as the data on the website is inherently dynamic and subject to constant changes due to various factors
7. The cleaned data will then be saved in a file names "Amazon_Web_Scraping_Cleaned_Data.csv"
   
## Results and Findings
* The data scraped and cleaned was visualized in Tableau. The insights gained can be found in the file "Report.pdf"
* The visualization on tableau can also be viewed online: https://public.tableau.com/app/profile/mahima.parekh/viz/AmazonBestsellersDashboard/Dashboard1?publish=yes

'Feel free to explore the provided the dashboard and modify them according to your requirements. The project can be further extended for a more in-depth analysis by adding/scraping additional Amazon products data to the dataset'
