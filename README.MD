LAB - Class 17
# Project: Web Scraping
**Author:** Michelle Salazar
----
## Problem Domain
### Feature Tasks and Requirements
<ul><li>
Scrape a Wikipedia page of your choosing and record which passages need citations.
</li><li>Your web scraper should report the number of citations needed.
</li><li>Your web scraper should identify those cases AND include the relevant passage.
</li><li>
E.g. Citation needed for “lorem spam and impsum eggs”
</li><li>
Consider the “relevant passage” to be the parent element that contains the passage, often a paragraph element.
</li></ul>

### Implementation Notes
<ul><li>
Module must be named scraper.py
<ul><li
Create function named get_citations_needed_count
</li><li>
takes in a url string and returns an integer.
</li><li>
Create function named get_citations_needed_report
</li><li>
takes in a url string and returns a report string
</li><li>
the string should be formatted with each citation listed in the order found.
</li></ul>

## Links and Resources

• back-end server url (when applicable)<br>

• front-end application (when applicable)

## Setup

cat requirements.txt
pip install pytest

**PORT -** Port Number

**DATABASE_URL -** URL to the running Postgres instance/db

*How to initialize/run your application (where applicable)*

• e.g. python main.py

## How to use your library (where applicable)

## User Acceptance Tests

The application must:
<ul><li>
encrypt a string with a given shift </li><li>
decrypt a previously encrypted string with the same shift.</li><li>
encryption should handle upper and lower case letters.</li><li>
encryption should allow non-alpha characters but ignore them, including white space.</li><li>
decrypt encrypted version of It was the best of times, it was the worst of times. WITHOUT knowing the shift used.</li><li>
refer to supplied unit tests.</li></ul>

## Links

---
*Notes:*
