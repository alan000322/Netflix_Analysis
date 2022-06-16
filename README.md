# Final - 韓流來襲 宅經濟下台灣觀眾Netflix觀劇全解析

## 資料內容
### 資料爬取與前處理
#### 01.0-Search_Netflix_Information.Rmd
收集 FlixPatrol 網站內容。 
#### 01.1-Search_Netflix_Information.Rmd
收集 TMDB 上的資訊，搜尋戲劇的詳細資訊。

#### FlixPatrol_df.xlsx
將 FlixPatrol 取得的資料與 TMDB join。並丟到 Google Spreadsheet 上進行人工檢查與加工處理。（本檔案將整個加工處理後的表下載成 excel 放置到這裡）

#### 01.2-Netflix_add_zh_name.Rmd
將人工檢查、標記好的台灣站、韓國站的表取得後，與 TMDB 網站對照，擷取中文劇名。
（需再次人工檢查是否有誤）

#### 02-Scrap_TMDB_netflix_actor.Rmd
收集 TMDB 上每一齣劇的演員名稱
（其實應該也可以用 TMDB API 達成）

#### 03.1-Dcard-parser.Rmd
取得 Dcard 特定版面的文章列表

#### 03.2-Dcard_content_analysis_KRNetflix.Rmd
取得 Dcard 特定文章的內容全文與基本資訊（留言數、按讚數等）

### 資料分析與視覺化
#### combinedfinal_twkr.Rmd
初步資料視覺化的檔案

#### Netflix_countries.Rmd
美化圖片使用



## 報告簡報

報導：https://alan000322.github.io/KoreaDrama-TaiwanNetflixAnalysis/

報題：
[期中報題連結](https://docs.google.com/presentation/d/1YSgPmqzaFSmbVI4q67f7RHvS85JjXmjs/edit?usp=sharing&ouid=106392091722319456192&rtpof=true&sd=true)

期末報告：
[期中報題連結](https://docs.google.com/presentation/d/1YSgPmqzaFSmbVI4q67f7RHvS85JjXmjs/edit?usp=sharing&ouid=106392091722319456192&rtpof=true&sd=true)



## NOTION 進度整理

[Notion 整理](https://petalite-justice-4cb.notion.site/Final-Netflix-ca70a86d209a462395ab25c143d823fa)



## 參考資料
[Netflix 紅什麼？從排名數據帶你一次看清楚](https://medium.com/dd-story-hub/netflix-%E7%B4%85%E4%BB%80%E9%BA%BC-%E5%BE%9E%E6%8E%92%E5%90%8D%E6%95%B8%E6%93%9A%E5%B8%B6%E4%BD%A0%E4%B8%80%E6%AC%A1%E7%9C%8B%E6%B8%85%E6%A5%9A-fbdcff623b5e)

[Netflix 排行榜揭密：韓劇爆發、日劇起飛，臺劇新出路在哪裡？](https://www.readr.tw/post/2893)

[中國流行語滲透台灣？從 Dcard 數據窺見年輕人網路用語趨勢](https://www.readr.tw/post/2836)

