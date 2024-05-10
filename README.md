# Final - 韓流來襲 宅經濟下台灣觀眾Netflix觀劇全解析

## 資料內容
### 資料爬取與前處理
#### 01.0-Search_Netflix_Information.Rmd
Collect content from the FlixPatrol website.
#### 01.1-Search_Netflix_Information.Rmd
Collect information from TMDB and search for detailed information about TV dramas.

#### FlixPatrol_df.xlsx
Join data obtained from FlixPatrol with TMDB information and upload it to a Google Spreadsheet for manual review and processing. (Download the fully processed file as an Excel sheet and store it here.)

#### 01.2-Netflix_add_zh_name.Rmd
After retrieving the manually checked and labeled tables for the Taiwan and Korea regions, compare them with data from TMDB to extract the Chinese titles. 
(Another manual review is needed to ensure accuracy.)

#### 02-Scrap_TMDB_netflix_actor.Rmd
Collect the cast names for each show on TMDB. 
(This can likely be achieved using the TMDB API.)

#### 03.1-Dcard-parser.Rmd
To retrieve a list of articles from a specific section of Dcard.

#### 03.2-Dcard_content_analysis_KRNetflix.Rmd
To collect the full text and basic information (such as the number of comments and likes) of a specific article from Dcard.

### 資料分析與視覺化
#### combinedfinal_twkr.Rmd
Preliminary data visualization file.


#### Netflix_countries.Rmd
For enhancing images.





## Presentation

Final：https://alan000322.github.io/KoreaDrama-TaiwanNetflixAnalysis/

報題：
[期中報題連結](https://docs.google.com/presentation/d/1YSgPmqzaFSmbVI4q67f7RHvS85JjXmjs/edit?usp=sharing&ouid=106392091722319456192&rtpof=true&sd=true)

期末報告：
[期中報題連結](https://docs.google.com/presentation/d/1YSgPmqzaFSmbVI4q67f7RHvS85JjXmjs/edit?usp=sharing&ouid=106392091722319456192&rtpof=true&sd=true)



## Notion Backup

[Notion Backup](https://petalite-justice-4cb.notion.site/Final-Netflix-ca70a86d209a462395ab25c143d823fa)



## Reference
[Netflix 紅什麼？從排名數據帶你一次看清楚](https://medium.com/dd-story-hub/netflix-%E7%B4%85%E4%BB%80%E9%BA%BC-%E5%BE%9E%E6%8E%92%E5%90%8D%E6%95%B8%E6%93%9A%E5%B8%B6%E4%BD%A0%E4%B8%80%E6%AC%A1%E7%9C%8B%E6%B8%85%E6%A5%9A-fbdcff623b5e)

[Netflix 排行榜揭密：韓劇爆發、日劇起飛，臺劇新出路在哪裡？](https://www.readr.tw/post/2893)

[中國流行語滲透台灣？從 Dcard 數據窺見年輕人網路用語趨勢](https://www.readr.tw/post/2836)

