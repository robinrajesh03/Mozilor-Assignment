# Mozilor Assignment
# Agency Eligibility Checker

This solution evaluates agency websites to determine if they offer services like web design, web development, SEO, and digital marketing. Based on the evaluation, the project stores the decision in a CSV file and sends an email notification to the agency.

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

---

### Python Libraries

Install the required libraries using:

```bash
pip install selenium beautifulsoup4 google-generativeai
```
---

## Usage

Before running the code we require to do the following:
1. **Install Webdriver**: In order to use Selenium we need to download appropriate webdriver (ex. Chromedriver) and keep it in the directory.
2. **Create Environment Variables**: Create environment variables for (`api_key`) and (`email_password`) and add path.

By updating the (`websites`) list inside (`main()`) function with website names, URLs, and contact emails, we can try for various agencies.

---   

## Output

Link to the demo video : [Demo](https://drive.google.com/file/d/11w7YIlg2wYMrfXid8bxEOGVLfe3lOCr6/view)
