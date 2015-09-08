Name:           SmeegeScrape
Version:        0.6
Date:           01/27/2014
Author:         Smeege
Contact:        SmeegeSec@gmail.com

Description:    SmeegeScrape.py is a simple python script to scrape text from various sources including local files and web pages, and turn the text into a custom word list.  A customized word list has many uses, from web application testing to password cracking, having a specific set of words to use against a target can increase efficiency and effectiveness during a penetration test.  I realize there are other text scrapers publicly available however I feel this script is simple, efficient, and specific enough to warrant its own release. This script is able to read almost any file which has cleartext in it that python can open.  I have also included support for file formats such as pdf, html, docx, and pptx. 

This script now requires NLTK v. 2.0.4 as recent updates to NLTK have removed certain functions.  You can run the following command to install the old version: 'sudo pip install -Iv nltk==2.0.4'.  For more information see FAQ #17 at http://pitt.edu/~naraehan/python2/faq.html.
