<div align = "center">
<h1>📊 2023 Bigdata Platform - Final Team Project</h1>
  복지 사각지대 - 노인을 중심으로 한 데이터 분석
</div>


## 목차
- [프로젝트 개요](#프로젝트-개요)
- [데이터 수집](#데이터-수집)
- [데이터 분석](#데이터-분석)
- [팀원 소개 및 역할 분담](#팀원-소개-및-역할-분담)

## 프로젝트 개요
<br>
데이터 분석을 통해 복지 사각지대를 찾아냈다는 기사를 읽고 '복지 사각지대'에 대한 데이터 분석으로 주제를 구체화하게 되었으며,<br>
사회취약계층 중 현재 대한민국이 직면한 고령화 사회에 주목하게 되어 노인을 대상으로 데이터 수집 및 분석을 진행하였습니다.<br>
공공데이터, 국회입법예고, 유튜브 댓글, 네이버 뉴스와 같이 다양한 출처의 데이터를 활용하여 포괄적인 분석을 수행하고자 하였습니다.
<br>
<br>

## 데이터 수집
#### 1. 공공데이터
kosis 국가통계포털과 지방재정365 사이트에서 인구 통계와 노인 일자리 사업, 복지 예산 투입액에 대한 데이터를 수집하였습니다.
<br>

#### 2. 국회입법예고
BeautifulSoup과 Selenium을 이용하여 국회입법예고 사이트 (https://pal.assembly.go.kr) 에서<br>
제 19 ~ 21대까지의 기간 동안 ‘복지법’을 키워드로 지정하여 법률안의 명칭, 제안 이유 및 주요 내용, 시민들의 의견 제목을 수집하였습니다.<br>
각 기간 별로 220, 280, 390개씩 수집하여 총 890개의 데이터를 수집하였습니다.
<br>

#### 3. 유튜브 뉴스 영상 댓글
Google API를 활용하여 ‘노인 문제’, ‘노인 빈곤’ 등의 키워드로 댓글이 많은 뉴스 영상을 선택하여 유튜브 댓글 데이터를 수집하였습니다.<br>
2016년 ~ 2017년 뉴스 댓글 데이터 853개, 2023년 뉴스 댓글 데이터 857개로 총 1710개의 데이터를 수집하였습니다.
<br>

#### 4. 네이버 뉴스 기사
BeautifulSoup를 이용해 네이버 기사 본문을 기간과 키워드에 따라 세분화하여 수집하였습니다.<br> 
다수의 키워드를 url 중복 없이 기간 별로 검색하고, HTML 파싱 후 기사 전처리를 진행하였습니다.<br> 
Konlpy를 사용해 명사 추출 후 불용어, 검색 키워드, 한 글자는 제외하여 데이터를 저장하였습니다.
<br>
<br>

## 데이터 분석
### 전체 구조

#### 1. 공공데이터

#### 2. 국회입법예고

#### 3. 유튜브 댓글을 이용한 감정 분석

#### 4. 네이버 뉴스 기사를 이용한 워드 클라우드



## 팀원 소개 및 역할 분담
|  구연우(팀장)  |  김지혜  |  이재희  |  유지연  |
|:---:|:---:|:---:|:---:|
| 국회입법예고 데이터 수집 및 분석 | HDFS, 네이버 뉴스 기사 수집 및 분석 | 공공데이터 수집 및 분석 | 유튜브 댓글 수집 및 분석 |
