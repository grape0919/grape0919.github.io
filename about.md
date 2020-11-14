---
layout: article
titles:
  # @start locale config
  en      : &EN       About
  en-GB   : *EN
  en-US   : *EN
  en-CA   : *EN
  en-AU   : *EN
  zh-Hans : &ZH_HANS  关于
  zh      : *ZH_HANS
  zh-CN   : *ZH_HANS
  zh-SG   : *ZH_HANS
  zh-Hant : &ZH_HANT  關於
  zh-TW   : *ZH_HANT
  zh-HK   : *ZH_HANT
  ko      : &KO       소개
  ko-KR   : *KO
  fr      : &FR       À propos  
  fr-BE   : *FR
  fr-CA   : *FR
  fr-CH   : *FR
  fr-FR   : *FR
  fr-LU   : *FR
  # @end locale config
key: page-about
---

# Fabulous dev

![icon](/assets/grape.png){:.circle.shadow}

## Hong-kyo Kim
 
 - Interest : `NLP(Natural Language Processing)`{:.info} `Deep Learning`{:.warning}
 - Programming Languages : `C`{:.info} `C++`{:.warning} `java`{:.error} `python`{:.success}
 - Frame work : `MFC(C++)`{:.info} `SWING(java)`{:.warning} `PyQ5t(python)`{:.error} `Flask(python)`{:.success}
 - OS : `Windows`{:.info} `Linux`{:.warning}

## Career
---
__NHN diquest__

2018.04 ~

---

### 1. LGUPLUS 언어 분석 서비스 개발 (2020-06-22~진행중)
 - 트랜드 키워드 분석
 - 뉴스 기사 제목 분석 후 요약 키워드/조합 모듈 개발
 - 연관어 분석 개발
 - 통계 분석(mann-kendall, change-rate) 모듈 개발

### 2.  Semantic Analyzer 개발 (2020-04-15~진행중)
 - 카테고리 별 사전 분리 개발
 - 일괄 분석 기능 개발
 - 일괄 분석 후 개체명 데이터 통계/분석 모듈 개발
 - 일괄 분석 후 연관어분석 모듈 개발
 - 개발된 딥러닝 개체명 분석기 연계 개발
 - 사업별 버그 / 이슈 대응

### 3. 라이나 생명 TMR Assistant 개발 (2019-07-22~2020-04-14)
 - 대화분석, 언어분석 솔루션, 검색 솔루션, Open knowledge 솔루션 설치 및  커스터마이징
 - 솔루션 버그/이슈 대응
 - 상담사와 고객 간 대화(stt)를 분석하여, 현재 대화중인 상황에 맞는 상품정보 및  질병 정보 제공
 - 상담사 교육 컨텐츠 채점 모듈(stt 데이터 분석하여 정답과 얼마나 일치하는지)  개발
 - Open knowledge 검색 REST api 개발
 - 문장 분리기 개발

### 4. Semantic Analyzer 개발 (2019-04-01~2019-07-21)
 - 기존 Semantic Analyzer 코드 분석
 - Semantic Analyzer 3 -≫ 4 로 업그레이드
 - 형태소 분석기, 개체명 추출기, 문법 관계 추출기 등 도메인 별로 사용 가능하도록  카테고리 기능 추가
 - 형태소 분석기 : 불용어 처리 기능 개발
 - 개체명 추출기 : 정규식을 이용하여 개체명 추출 기능 개발
 - 개체명 추출기 : 규칙 기반 개체명 추출 로직 오류 수정
 - 다중화(Multiplexing) : 여러 서버(분석기)에서 같은 싱크로 사전 생성, 분석  가능하도록 설계 및 개발
 - 웹관리도구 또는 다른 솔루션에서 사용 가능하도록 api 개발
 - Jenkins ci/cd 구성

### 5. Chatbot 솔루션 유틸리티 개발 (2019-04-01~2019-07-22)
 - 솔루션 사용시 설치 후 콘솔에서 초기 데이터베이스 설정 또는 커넥션 테스트를 CUI를 통해 쉽게 설정할 수 있도록 개발

### 6. 국민연금 사내 Chatbot 개발 (2018-10-25~2019-02-28)
 - Chatbot 솔루션 설치
 - Chatbot 솔루션-java-client 활용 서비스 개발
 - rest-api 개발
 - db 데이터 동이화를 위한 이관 쉘스크립트 개발
 - https://www.youtube.com/watch?v=t-7Oxifu03c

### 7. 삼성카드 Chatbot 서비스 개발 (2018-09-10~2018-10-19)
 - Chatbot 솔루션 java-client를 사용한 서비스 개발
 - 기간계 연계 서비스 개발
 - 삼성카드 Chatbot ‘샘’ 서비스 개발
 - https://youtu.be/3El5VEydgSg

### 8. 카테고리 검증 모듈 개발 (2018-07-01~2018-07-31)
 - 사용자가 직접 정의한 카테고리의 개수가 많아 졌을 때 카테고리 추가시 적정  카테고리를 추천해주는 모듈 개발
 - 예)
>_현재까지 구축된 카테고리_
```
A≫B≫C
A≫B≫D
A≫B≫E≫F
```
>_사용자 입력_
```
A≫D≫G -≫ 추천 A≫B≫D≫G
F≫E≫B≫A≫H -≫ 추천 A≫B≫E≫F≫H
```

### 9. 딥러닝 오타보정에 데이터 정제 (2018-06-01~2018-06-28)
 - 딥러닝 오타보정에 쓰이는 데이터를 정제하여 오타보정 정확도를 올려주도록 정제  모듈 개발.
 - 학습데이터에서 어절을 수집 후 불필요 문자, 어절을 분석하고 제거하도록 개발