
# JaYoung Kim 포트폴리오
> 

</br>

## :pushpin: Intro
🌟다양한 프로젝트와 환경에 유연성을 가진 백엔드 개발자로서, 
🌟끊임없는 학습과 커뮤니케이션을 통해 동료들과 함께 성장하는 것을 가장 중요하게 여깁니다. 
🌟어제보다 더 나은 내 자신을 만들기 위해 끝없는 노력을 기울이며, 
🌟호기심의 물음표에 답을 찾을 때까지 담대하게 질문하는 열정 넘치는 개발자입니다.



</br>

## :pushpin:기술스택


![image](https://github.com/memorygreen/portfolio/assets/108516942/4bedc042-7458-41a7-be8d-4aa8c6ba8532)
</br>

## :pushpin: Contact
- 이메일: setterdayz0720@naver.com
- 블로그: #
- 깃헙: https://github.com/memorygreen/

</br>

## :pushpin: Projects

### 1. 첫 번째 프로젝트(https://github.com/memorygreen/project
>팀 프로젝트 
>개발 기간: 2024.03.22 ~ 2024. 04.05

>  
>기술 스택:
<img src="https://img.shields.io/badge/JAVA-007396?style=for-the-badge&logo=java&logoColor=white"/> <img src="https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=Spring&logoColor=white"> <img src="https://img.shields.io/badge/html-E34F26?style=for-the-badge&logo=html5&logoColor=white"/> <img src="https://img.shields.io/badge/css-1572B6?style=for-the-badge&logo=css3&logoColor=white"/> <img src="https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"/> <img src="https://img.shields.io/badge/mysql-4479A1?style=for-the-badge&logo=mysql&logoColor=white"/>




>  
>[프로젝트 상세 설명](https://github.com/memorygreen/project) 참고

  >### :pushpin: 중고스쿨
> 중고등학생을 위한 중고거래 플랫폼 웹사이트

</br>


<details>
  
## 1. 제작 기간 & 참여 인원
- 2024년 3월 22일 ~ 4월 5일
- 팀 프로젝트 (김자영, 박민, 이다은, 임지훈, 천지원)

</br>

## 2. 사용 기술
#### `Back-end`
  - Java 8
  - Spring
  - MySQL 4.0
#### `Front-end`
  - Html/Css
  - Javscript

</br>

## 3. ERD 설계
![오버라이딩_20240408_181241](https://github.com/memorygreen/portfolio/assets/108516942/59c55701-10e6-4632-ae7d-6f446e9691b9)



## 4. 핵심 기능
이 서비스의 핵심 기능은 학교 인증과 청소년 연령제한, 욕설/비속어 필터링 기능입니다. 
사용자는 학생증 인증을 통해 학교 인증 후 서비스를 이용할 수 있으며, 청소년 연령을 제한할 수 있습니다.
또한 채팅 스타일의 댓글기능을 구현하여 사용자가 채팅을 하는 듯 몰입하여 댓글을 작성할 수 있습니다.


<details>
<summary><b>핵심 기능 설명 펼치기</b></summary>
<div markdown="1">

### 4.1. 전체 흐름
![image](https://github.com/memorygreen/portfolio/assets/108516942/36a11ec3-03ae-4df4-93a5-d3c3467cc6e3)

![image](https://github.com/memorygreen/portfolio/assets/108516942/ef8d09c8-7dc1-42c3-b0f2-e9b0722924c2)

### 4.2. 욕설/비속어 필터링
![image](https://github.com/memorygreen/portfolio/assets/108516942/fc4f16b0-ad91-47dc-a624-4ce51ae8a9a9)
![image](https://github.com/memorygreen/portfolio/assets/108516942/3a56bac0-719d-4327-9412-c21452475276)



- **상품 등록** :pushpin: [코드 확인]
  - Controller에서는 요청을 화면단에서 넘어온 요청을 받고, Mapper 계층에 로직 처리를 위임합니다.

- **욕설/비속어 필터링** :pushpin: [코드 확인]
  - 

- **등록 제한 팝업** :pushpin: [코드 확인]()
  - 상품 게시글의 제목 또는 상품 설명에 욕설/비속어가 포함되어있으면 재작성을 요청하는 팝업창을 전송합니다.

### 4.3. 댓글기능
![Uploading image.png…]()
![image](https://github.com/memorygreen/portfolio/assets/108516942/c03a8aff-516f-48e3-9212-3d6b94c4be0a)

- **작성자에 따른 상이한 디자인 및 정렬** :pushpin: [코드 확인](https://github.com/JungHyung2/gitio.io/blob/d35d29b64c0e8b9653862bdcc1e6b997d2436ec9/index.html#L57C1-L57C202)
  - 댓글 작성자 화면에서는 자신의 댓글이 초록색 말풍선과 더불어 "나"라는 글자와 함께 표시됩니다.
  - 다른 사람이 쓴 댓글은 회색 말풍선으로 표시되며, 판매자가 작성한 댓글은 "판매자"라는 글자와 함께 표시됩니다.


</br>

## 5. 핵심 트러블 슈팅
### 5.1. 학교 선택시 위치 인식 불가
![image](https://github.com/memorygreen/portfolio/assets/108516942/8382410a-6f31-426f-b38b-d06830f437ba)
- 사용자의 위치와 그로부터 반경2km이내에 있는 학교를 표시하여 지도에 표시하려 했으나, 사용자의 위치와 주변 거리를 분석하여 추천해줄 수 있는 머신러닝을 구현하기에는 물리적인 한계에 봉착했습니다.
- 따라서 사용자의 위치와 주변 학교의 고정 경도와 위도를 사용하여 대체


</br>


</details>

</details>
</br>



### 2. [두 번째 프로젝트](https://github.com/JungHyung2/gitio.io)
>두 번째 프로젝트 간략 소개  (팀 프로젝트)  
>개발 기간: 2023.1.29 ~ 2023.1.31
>  
>기술 스택:  
>Java 8 / Oracle SQL
><img src="https://img.shields.io/badge/JAVA-007396?style=for-the-badge&logo=java&logoColor=white"/> <img src="https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=oracle&logoColor=black"/>
>  
>[프로젝트 상세 설명]([https://github.com/JungHyung2/gitio.io](https://github.com/2021-SMHRD-KDT-AI-18/jyTeamRepo)) 참고
  >### :pushpin: MVC 패턴을 활용한 코인 노래 맞추기


</br>

---
## :pushpin:교육 및 경력사항/ 자격증


## 자격증
### 개발
|    자격증 획득일    |       자격증명       |        발급기관         |
|:-------------------:|:-------------------:|:----------------------:|
|      2023.06        |    정보처리기사      |   한국산업인력공단    |
|      2022.11        |      SQL 개발자 (SQLD)     | 한국데이터산업진흥원  |
|      2024.03        |     리눅스마스터 2급  | 한국정보통신진흥협회  |
|      2024.03        |   네트워크관리사 2급  | 한국정보통신자격협회  |

### 데이터분석
|    자격증 획득일    |       자격증명       |        발급기관         |
|:-------------------:|:-------------------:|:----------------------:|
|      2022.12        |  빅데이터분석기사    |  한국데이터산업진흥원  |
|      2022.02        |  데이터분석 준전문가 (ADsP) | 한국데이터산업진흥원  |

### 문서작성 능력

|    자격증 획득일    |       자격증명       |        발급기관         |
|:-------------------:|:-------------------:|:----------------------:|
|      2023.11        |   컴퓨터활용능력 1급  |      대한상공회의소     |
|      2023.09        |    사회조사분석사 2급 |   한국산업인력공단    |
|      2019.09        |     워드프로세서 1급 |   대한상공회의소    |

### 클라우드

|    자격증 획득일    |       자격증명       |        발급기관         |
|:-------------------:|:-------------------:|:----------------------:|
|      2022.12        |   AZ-900: Microsoft Azure | Microsoft |

### 기타

|    자격증 획득일    |       자격증명       |        발급기관         |
|:-------------------:|:-------------------:|:----------------------:|
|      2021.06        |   유통관리사 2급     |     대한상공회의소     |
|      2021.06        |    상공회의소 한자 3급 | 대한상공회의소     |
|      2019.10        | 한국사능력검정시험 2급 |  국사편찬위원회   |
|      2022.07        |  ACU(Autodesk Certified User) | Autodesk |
|      2023.07        | 산업안전기사(필기 합격) | 한국산업인력공단 |

### 어학
|    자격증 획득일    |       자격증명       |        발급기관         |
|:-------------------:|:-------------------:|:----------------------:|
|      2022.07        |   JLPT(일본어능력시험)     |     일본국제교류기금     |

---

## 교육 및 경력사항

|     기간     |       기관명       |    내용      |
|:----------------:|:------------------:|:------------------------------:|
| 2023.12 – 2024.06 | 스마트인재개발원 | 인공지능 융합서비스 개발자 과정 |
| 2022.12 – 2023.12 | 전남대학교 산학협력단 | 대학원 교육연구팀 행정지원 업무(직책: 연구지원조교) |
| 2018.03 – 2023.02 | 전남대학교 | 경제학과/경영학과 (부전공:일어일문학과) |
| 2022.11 – 2022.12 | 한국산업기술협회 | 빅데이터 활용 자바프레임워크 개발자 양성과정 |
| 2022.01 – 2022.03 | 한국산업기술협회 | 스마트공장 현장 엔지니어 전문가 양성과정 |




## :pushpin:기타
