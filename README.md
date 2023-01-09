# チャットボットニュース
`Flask`と `BeautifulSoup`の練習課題。
声で話しかけると、Webスクレイピングを行い、最近話題のオススメ記事を1つ教えてくれる。  
***

# Tips
```
items = soup.select(".entrylist-contents-title a") 
*リンクアンカー <a></a>を親のentrylist-contents-title範囲とした
```
## 起動確認
```
$ cd practice
$ python3 app.py
```
以下のURLで確認
```
http://localhost:5004
```
