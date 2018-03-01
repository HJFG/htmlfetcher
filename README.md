# HTML Parsing

No pain HTML fetching library. 

A light wrapper of selenium.

For page with a lot of ajax.


## Installation

```python
pip install htmlfetcher
```

download browser: [https://github.com/mozilla/geckodriver/releases](https://github.com/mozilla/geckodriver/releases)

## Usage

```python
from htmlfetcher import HTMLFetcher

fetcher = HTMLFetcher(browser='/home/bug/桌面/geckodriver')
text = fetcher.get('http://zhaopin.baidu.com/quanzhi?tid=4139&ie=utf8&oe=utf8&query=python&city_sug=%E6%88%90%E9%83%BD')
fetcher.close()

print(text)
```
