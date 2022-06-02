B4X實驗: web crawler網路爬蟲/抓取網頁內容(B4J MiniHtmlParser)
參考資料:
https://www.webscrapingpro.tw/what-is-web-scraping/
https://www.b4x.com/android/forum/threads/b4x-minihtmlparser-simple-html-parser-implemented-with-b4x.118590/#content MiniHtmlParser範例




1.與python爬蟲的差異??
https://ithelp.ithome.com.tw/articles/10202121

2.LIB
MiniHtmlParser
jOkHttpUtils2

3.遇到的問題
j.Download("https://www.twse.com.tw/exchangeReport/STOCK_DAY?response=html&date=20220301&stockNo=2049") 出現底下錯誤時
javax.net.ssl.SSLHandshakeException: PKIX path building failed: sun.security.provider.certpath.SunCertPathBuilderException: unable to find valid certification path to requested target


https://www.b4x.com/android/forum/threads/httpjob-does-not-step-in-if-j-success-statement.127655/#post-799542 參考這個解決

4.程式碼解說
https://github.com/eric19740521/b4x20220602
