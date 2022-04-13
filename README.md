# 독자맞춤형 하이브리드 도서 추천 시스템

<aside>
💡 AI 서비스개발 프로젝트
[TOC]



# 프로젝트 주제

 📚 독자의 상황 및 회원 여부에 따른 콘텐츠/협업필터링 도서 추천 시스템



## **1. 프로젝트 소개**

### 💭 **배경**

- 기존의 도서 추천 시스템은 판매량 기반의 베스트 셀러 위주
- 또한, 카테고리를 이용할 수 있지만 선택의 폭이 좁음.



### ⭐ **목적**

❗ 더 세분화 된 개인의 상황 및 관심사 기반 검색 가능한 추천 시스템을 구현해보자



### 🗓️ **프로젝트 기간**

- 2022년 03월 15일 ~ 2022년 03월 31일



### 💽 데이터수집

- 알라딘 OpenAPI
- 알라딘 : 도서 ISBN 수집
- yes24 : 리뷰 관련 데이터 수집



---

## **2. Tech**

|               |                                                        |
| --- | --- |
| 사용언어 | Python |
| 1. 데이터수집 | selenium, BeatifulSoup |
| 2. 자연어처리 | konlpy , Mecab, nltk, gensim, sklearn, Word2Vec, TFIDF |
| 3. 추천시스템 | 컨텐츠기반 필터링, MF 기반 잠재요인 협업 필터링 |
| 4. 시각화 | matplotlib, wordcloud |



## 3. 검색 및 추천 프로그램 실행

프로그램 실행 도식화

![image-20220413221425974](../../../../AppData/Local/Temp/Temp1_Export-a837871f-cbe8-4c9c-90e0-e74b821bba58.zip/독자맞추 0d22b.assets/image-20220413221425974.png)

1. 사용자가 원하는 키워드 검색

<img src="../../../../AppData/Local/Temp/Temp1_Export-a837871f-cbe8-4c9c-90e0-e74b821bba58.zip/독자맞추 0d22b.assets/Untitled (1).png" style="zoom: 67%;" />



2. 추천 시스템 진행 중

<img src="../../../../AppData/Local/Temp/Temp1_Export-a837871f-cbe8-4c9c-90e0-e74b821bba58.zip/독자맞추 0d22b.assets/Untitled (2).png" style="zoom:67%;" />



3. 결과

<img src="../../../../AppData/Local/Temp/Temp1_Export-a837871f-cbe8-4c9c-90e0-e74b821bba58.zip/독자맞추 0d22b.assets/Untitled (3).png" style="zoom:67%;" />

---



# 💫 포트폴리오(notion)

https://fluttering-laborer-622.notion.site/66d044c0669c4f2db26c47da37834e9b



---

# :computer: Code

[Hongbi-Kim/Project_book_recommendation: 독자의 상황 및 회원 여부에 따른 콘텐츠/협업필터링 도서 추천 시스템 (github.com)](https://github.com/Hongbi-Kim/Project_book_recommendation)



# 🏆 대회결과

- 멀티캠퍼스에서 실시한 K-Digital Training 과정 <AI 서비스 개발 프로젝트>에서 최우수상 수상.