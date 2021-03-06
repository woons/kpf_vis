## 데이터저널리즘(기초) 데이터시각화
##### 2017. 4. 27. Fri
----------
https://docs.google.com/spreadsheets/d/13Z4aKlOlLvYYipa73db-7Odf5JMGdm3k75s-0wXomEc/edit#gid=0
#### 강의 개요
+ 데이터시각화를 위한 데이터 리터러시 (Data Literacy)
+ 정성적 데이터의 정량화 그리고 시각화
  + 카테고리(factor) 데이터를 어떻게 정량화 할 것인가
  + 어떤 유형의 차트를 활용하고 유의점은 무엇인가
  + 웹에 있는 데이터를 가지고와서 간단한 정제 후에 시각화
+ 맵핑시각화 
  + Google Spreadsheet를 활용한 간단한 위경도 변환
  + Carto를 활용한 맵핑시각화  
    + [실습1](https://woons.carto.com/builder/9497ebfe-f8bc-11e6-8294-0e3ff518bd15/embed)
    + [실습2](https://woons.carto.com/builder/ab10af62-2b0f-11e7-a3d4-0e3a376473ab/embed)
 ----------
 
 #### 샘플 데이터 (위의 폴더 참고)
+ Google Spreadsheet
+ CSV
  + restraunt.csv
  + earthquake.csv
 
 ----------
#### 활용할 툴 (tool)
+ Infogram(https://infogr.am)
+ Carto(http://carto.com)
+ Google Spreadshhet

#### 참고

=IMPORTHTML("https://en.wikipedia.org/wiki/World_population", "table", 14)
=IMPORTXML("http://www.nytimes.com", "//h2[@class='story-heading']")
데이터 수집 실습1 : https://goo.gl/3oOvIx
=IMPORTXML("http://score.sports.media.daum.net/record/baseball/kbo/brnk.daum", "//td[@class='txt_league']")
데이터 수집 실습2 : https://goo.gl/3oOvIx
=IMPORTXML(A2, "//td[@class='post_subject']")
데이터 정제 실습2 : https://goo.gl/vvl5Dv
(.+)

https://docs.google.com/spreadsheets/d/1I2sgWbJK5jJ9I9cMApGKKxoxNg6lbp6mi6IJ6jkWL3k/edit?usp=sharing
