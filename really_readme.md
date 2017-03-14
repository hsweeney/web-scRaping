# web-scRaping

## A project for the Cardiff R Group (Hugh Sweeney)

My interest is in automation. I want to create a tool that can be run automatically, e.g., as a cron job or other scheduled task. It will

- verify existence of the web site;
- verify that the web page structure is as expected;
- find the chosen data;
- extract and save the data.

Presentation or analysis of the data is left to another app.


## R Code to scrape a website

Considerations:

- choice of tools: rvest, RSelenium etc;
- choice of website;
- web__site__ or web__page__?
- generalising to multiple web sites, types of web site, non-web sites...
- problems to consider:
  - broken HTML;
  - how to detect if the web page structure has changed?
  - www.no1currency.com doesn't reveal all the page content in view-source; I think the use of <script type="text/template" ...> is the cause.
  - sites actively or inadvertently impeding web scraping (e.g., captcha, loading via JS)
