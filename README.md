# Mozilor Assignment
# Agency Eligibility Checker

This project evaluates agency websites to determine if they offer services like web design, web development, SEO, and digital marketing. Based on the evaluation, the project stores the decision in a CSV file and sends an email notification to the agency.

---

## Features

1. **Web Scraping**: Extracts the first few paragraphs of a webpage using Selenium and BeautifulSoup.
2. **AI Decision Making**: Uses Google Generative AI to determine if the website qualifies as an agency offering specific services.
3. **Data Storage**: Logs decisions (Approved or Declined) in a CSV file.
4. **Email to Agency**: Sends an email to the agency regarding their eligibility status.

---

## Requirements

- Python 3.7 or higher
- Google Generative AI API key
- Google Chrome and ChromeDriver
- Gmail account for email notifications

### Python Libraries

Install the required libraries using:

```bash
pip install selenium beautifulsoup4 google-generativeai
