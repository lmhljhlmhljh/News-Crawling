# News-Crawling

### The team '딥문학도'
- I am involved in the team '딥문학도' where tries to make model which forms the CSAT.
- CSAT is the biggest exam evaluating high school students.
- We are thinking about 'Could AI or computer make CSAT exams properly?'
- or 'Can computer evaluate human being?'

### The reason why I do crawling a bunch of news from several news firm
- To make 'What is the topic/main argument of the passage?', we need model to learn topic selection in the selected passages.
- Newspaper reveals its topic explicitly, and headline shows the essence of the contents.
- So, I did crawl headline and the content of the news.

### How to Crawl? or the Method

#### 1. Using Feedspot
- Going to Feedspot (Feedspot gives you the 1 month amount news from such site)
- Use Selenium to get Urls of each site.
- Use Urllib and BS4(BeautifulSoup) to get the headline and the content.

#### 2. news from American, British firm
- each site has 'Read More' and click it
- There is the button 'next page', and I use that
- Use Selenium and get Urls from each pages, and move to next page automatically
- Use Urllib and BS4(BeautifulSoup) to get the headline and the content.

#### 3. news from Korean firms
- each site has formula and we don't need to use Selenium
- Use Urllib and BS4(BeautifulSoup) to get Urls
- Use Urllib and BS4(BeautifulSoup) to get the headline and the content.
- I do crawl in South Korea, and it was much faster than news from abroad because of the internet issues

