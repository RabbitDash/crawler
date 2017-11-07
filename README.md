# newscrawler

[To my collaborator] My Target is to crawl articles from this page: http://china.caixin.com/anticorruption/

[Original]

[![Join the chat at https://gitter.im/tankle/newscrawler](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/tankle/newscrawler?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
新闻网站爬虫,目前能够爬取网易，新浪，qq, sohu等三家网站的新闻页面。



##Using:

    python runspiders.py

##json file

The news file saved as json file:

newsId: the news's id

source: the source of the news , such as news.163.com, news.sina.com.cn or news.qq.com

date: the creation time of news, 20150529

contents:

link: the link of news

title: the title of news

passage: the content of news


The title and passage are encode as unicode, so you need transform it when load it.

##Other:
save2xml.py is used to changing the json to xml type. 

The xml file can be tagged by [TemporaliaChTagger](https://github.com/ntcirtemporalia/TemporaliaChTagger.git).


###Reference
[news-combinator](https://github.com/fanfank/news-combinator.git)
