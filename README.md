# Striver LeetCode Problem Scraper

This is a web scraper built with Puppeteer to scrape LeetCode problems from the Striver's website.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your/repository.git
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

## Usage

1. Import the scraper functions into your project:

   ```javascript
   const scraper = require("./path/to/scraper.js");
   ```

2. Use the scraper functions to scrape LeetCode problems:

   ```javascript
   const problems = await scraper.scrapeStriver191Probs("https://link/to/striver191");
   ```

3. Save the scraped data to a JSON file:

   ```javascript
   scraper.saveProblemstoJSON("problems.json", "./data", problems);
   ```

## Functions

### scrapeStriver191Probs(url: string)

Scrapes LeetCode problems from Striver's 191 list.

- `url`: The URL of Striver's 191 list.

### scrapeStriverDSAbegineer(url: string)

Scrapes LeetCode problems from Striver's DSA beginner list.

- `url`: The URL of Striver's DSA beginner list.

### scrapeStriverExpertProbs(url: string)

Scrapes LeetCode problems from Striver's expert list.

- `url`: The URL of Striver's expert list.

### saveProblemstoJSON(filename: string, dirLocation: string, data: object[])

Saves the scraped data to a JSON file.

- `filename`: The name of the JSON file.
- `dirLocation`: The directory location where the file will be saved.
- `data`: The data to be saved in the JSON file.

---
