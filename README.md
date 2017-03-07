�# web-scRaping
### A project for the Cardiff R Group (Hugh Sweeney)

#### R Code to scrape a website

Considerations:
- choice of tools: rvest, RSelenium etc;
- choice of website;
- web_site_ or web_page?
- generalising to multiple web sites, types of web site, non-web sites...
- problems to consider:
- - broken HTML;
- - how to detect if the web page structure has changesd?
- - www.no1currency.com doesn't reveal all the page content in view-source; I think the use of <script type="text/template" ...> is the cause.
- - sites actively or inadvertently impeding web scraping (e.g., captcha, loading via JS)

