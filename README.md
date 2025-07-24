# Cal Poly Course Catalog Scraper

This project demonstrates how to scrape and extract course information from the Cal Poly course catalog website.

## Contact

**Instructor**: Nick Riley - njriley@amazon.com

## Video

[Click here to launch the lesson](https://csuai-summer-camp-public-content.s3.us-east-1.amazonaws.com/csuai_calpoly_webscraping_demo.mp4?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAY2KA5QFENURW2E3L%2F20250724%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20250724T162454Z&X-Amz-Expires=300&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEAkaCXVzLWVhc3QtMSJHMEUCIFOmYeyzCSe7FX%2Fi68yDbVWFYG8NSsMAIlfn94BDAHuEAiEAgxg1HTShBA5dbqJzqhGlgSFlduoPG3OU5Hhy4KrWttIqygMIMRACGgw2MDYyNjM0MTEwMTYiDEn1M%2FZ76jdgVBmE8SqnA3uqZzaXTXdBQ40NMzT92EtigTCpA1GkjXAd1T2M%2BY7B9dDC0je57kyK1EauHi9EKQBNje2F5xRLlgKR0QtJiM9bc9gB6RjmvsYK2ockWbWGloIqiLETfZg9ETEmPgFSz28RvGCt7FFQyLjoRUg5KgKiVYk%2BrlqDfAGPdRi1FK%2FlAIO3%2BBl4RmWzajKimd8H8lWkfGYfbjSOEsXQQnyYN8f2u0yKT9jASzsnYsKi27eb4icjOriNgcsbmYTtZnVe1007K7v%2BsCrDra5jZ5z3UAetA%2FjMMkRLrxBVHvFf1kLj65vj2Uu1TvoJIma5tjLI%2BQfz6b%2BRfz2Sq3Z03b74VRti9Hagwo6zIOvyRXfwfNkINF469iT9ghjs0fi5KEsyYD657IjXNkYRTe2xMWagx0qupEcRYKLV9p7BVTXXpDuhJkCRIsE%2BYWrl9%2B2a0maCso6D%2FCIFhhcOVEp%2FQAxTBGOsjKs32BVTgz7xZmCG5iH84rgEnRmuaE%2FkzqHdSPwLNL0r1388EDh1ixinUUVEViO4MqQPB6xqlDsiHqKCiZ01%2BZ2M%2BZl97jCnt4nEBjqUAid04Cr8aImrqNPd0yDqo6u%2B9x30jGofvJK5jiHxs3oNF2yeHs%2FGsNYonYkxP4B3OuZ9pNCWzRWGlFG%2BWrwOx4QhQ%2BE7Gpkui0QwiNn5l2a7Rq9uKX0oBPuba08z3l5igNWgLpillWZbd1FnngMqqwP59fO0XLuzZ90cH%2Bn8zSbGuH0nT9Jo%2B%2BWLdpnUBWJmuQrnhoFJ8D%2FosqQLeqkolJztW6MQTPaVaTPkwp2A%2FEDKBSWmI5eS%2FS0ZDrlmWfnzAj8njGBCIjYEckUQc9%2F%2BIlSGttpduDEDqPwtWVKAYQxeK%2B8W%2B4sLWoDi%2FzegRFF18GfIS6csbdq2W0xhYJ6xRWNxwn47xpSrEr0kirmlVdQ6lR9egA%3D%3D&X-Amz-Signature=7e3ffaaf6e2901adb87cadc91cf903f157c7250386ff78231cd0c06b7685edb0&X-Amz-SignedHeaders=host&response-content-disposition=inline){:target="_blank"}

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
