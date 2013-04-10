Javascript Web Scraper using IE Internet object
-----------------------------------------------

My "Pure Javascript Web Scraper - scraper.js" github sample only worked for web pages that accept being displayed within a frame. Pages like Google Search prevents this by using the X-Frame-Options response header. 


This javascript uses the Internet Explorer Application object to load Google Search. The scraper page must be loaded in Internet Explorer with security settings that allow activeX creation.
 