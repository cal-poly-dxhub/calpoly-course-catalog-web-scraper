# Collaboration

Thanks for your interest in our solution. Having specific examples of replication and cloning allows us to continue to grow and scale our work. If you clone or download this repository, kindly shoot us a quick email to let us know you are interested in this work!

[wwps-cic@amazon.com]

---

# Disclaimers 

Customers are responsible for making their own independent assessment of the information in this document. 

This document: 

(a) is for informational purposes only, 

(b) references AWS product offerings and practices, which are subject to change without notice, 

(c) does not create any commitments or assurances from AWS and its affiliates, suppliers or licensors. AWS products or services are provided "as is" without warranties, representations, or conditions of any kind, whether express or implied. The responsibilities and liabilities of AWS to its customers are controlled by AWS agreements, and this document is not part of, nor does it modify, any agreement between AWS and its customers, and 

(d) is not to be considered a recommendation or viewpoint of AWS. 

Additionally, you are solely responsible for testing, security and optimizing all code and assets on GitHub repo, and all such code and assets should be considered: 

(a) as-is and without warranties or representations of any kind, 

(b) not suitable for production environments, or on production or other critical data, and 

(c) to include shortcuts in order to support rapid prototyping such as, but not limited to, relaxed authentication and authorization and a lack of strict adherence to security best practices. 

All work produced is open source. More information can be found in the GitHub repo.
# Cal Poly Course Catalog Scraper

This project demonstrates how to scrape and extract course information from the Cal Poly course catalog website.

## Contact

**Instructor**: Nick Riley - njriley@calpoly.edu

## Video

[Click here to launch the lesson](https://csuai-summer-camp-public-content.s3.us-east-1.amazonaws.com/csuai_calpoly_webscraping_demo.mp4)
## What You'll Learn

- Web scraping with Python using BeautifulSoup
- Extracting structured data from HTML pages
- Processing and organizing course information
- Working with JSON data

## Getting Started

Follow these steps in order:

### 1. Clone the Repository

```bash
git clone https://github.com/cal-poly-dxhub/catalog-web-scraper.git
cd major_information_scraper
```

### 2. Create a Virtual Environment

For macOS/Linux:
```bash
python -m venv venv
source venv/bin/activate
```

For Windows:
```bash
python -m venv venv
venv\Scripts\activate
```

### 3. Install Required Packages

```bash
pip install -r requirements.txt
```

### 4. Run the Web Downloader

```bash
python web_downloader.py
```

### 5. Run the Data Parser to view content
*Note: You can also view the data in the generated JSON file from step 4.*
```bash
python data_parser.py
```

This will:
1. Fetch all department links from the Cal Poly course catalog
2. Extract course information for each department
3. Save the results to a JSON file (course_info.json)

## Common Issues

- **Rate Limiting**: Be respectful of the website's resources by not making too many requests too quickly
- **HTML Structure Changes**: If the website structure changes, the scraper may need to be updated
- **Network Issues**: Ensure you have a stable internet connection
- **Missing Data**: Some courses may have incomplete information

## Learn More

- [BeautifulSoup Documentation](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)
- [Requests Library](https://docs.python-requests.org/en/latest/)
- [Web Scraping Best Practices](https://www.scrapehero.com/how-to-prevent-getting-blacklisted-while-scraping/)
