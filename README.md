# Web-Scraping-and-nltk
We will scrape novels from the website Project Gutenberg(which basically contains a large corpus of books) using the Python package requests. We have extracted the novels from this web data using Beautiful Soup. Then we dive in to analyzing the novels using the Natural Language ToolKit (nltk).We have then searched for the most frequent words and there frequency distribution. Text is freely available online at Project Gutenberg. We  found a novel and then stored the relevant URL in our Python namespace  Now that we got the URL, we fetched the HTML content of the website. For this we will use Package Requests.
To get the text from HTML, we have used package BeautifulSoup.

Then we used NLTK to:

1)Tokenize the text   
The text was split  into a list a words. Essentially, we splitted off the parts of the text that are separated by whitespaces.
2)Remove stopwords 
Then,we  removed the  words that appear a lot in the English language such as 'the', 'of' and 'a' (known as stopwords) because they're not so interesting.

At last, plotted a frequency histogram of words in our novel using NLTK.
