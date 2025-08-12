# 🟦 SK네트웍스 Family AI 캠프 17기 2차 프로젝트_ 4Team 🟦



#  1. 팀 소개
### ▶️ 팀명 :  **공공삼**

'공공삼'은 00년생 3명과 03년생 1명이 하나가 되어 팀을 이루었다는 뜻입니다. 

또, 세 가지 '공'인 공유, 공감, 공조를 핵심가치로 조화로운 팀을 이루겠다는 의미를 담았습니다. 

<br>
<br>

### ▶️ 팀원 소개 
|이름|이름|이름|이름|
|:---|:---|:---|:---|
|[김주영](https://github.com/samkim7788)|[전상아](https://github.com/sang-a-le)|[조해리](https://github.com/Haer111)|[최우진](https://github.com/CHUH00)|
|:--------------------------------------:|:--------------------------------------:|:-------------------------------------:|:---------------------------------------:|:---------------------------------------:|
|<img width="400" height="400" alt="C-QmMK2s_400x400" src="https://github.com/user-attachments/assets/ceacd5be-96f2-49d5-9546-eaa7cfe67c74" />|
<br>
<br>

-----

# 2. 프로젝트 개요

### ▶️ 프로젝트 명 
# **떠날까? 말까?**
SNS 사용자 데이터를 기반으로 페이스북 이탈 가능성 예측 모델 제공

<br>
<br>

### ▶️ 프로젝트 소개 
해당 프로젝트는 SNS 사용자 데이터를 기반으로 개인 특성을 분석하여 향후 플랫폼 이탈 가능성을 예측하는 것을 목표로 함. 특히, 페이스북을 1순위로 선택한 사용자를 기반으로 페이스북 사용자 이탈 가능성 예측

<br>
<br>

### ▶️ 프로젝트 필요성(배경)

<img width="551" height="210" alt="image" src="https://github.com/user-attachments/assets/3954c807-02cf-4edb-ab48-04ec4bec4a9d" />

> https://www.chosun.com/economy/tech_it/2023/03/10/NEL65GJO2ZGUXJHVGNCAC4Y354/


> 국내 페이스북 월 이용자가 처음으로 1000만명 이하로 떨어졌다. 사진이나 짧은 동영상 위주의 소셜미디어를 선호하는 10·20대 이용자의 이탈이 가속화하고 있기 때문으로 풀이된다.
* 조선일보, 변희원, 2023.03.10


위의 기사 내용과 같이 2023년 국내 페이스북 월 이용자가 처음으로 1000만명 이하로 떨어지는 등 페이스북 사용자가 지속적으로 감소하는 양상을 보이고 있습니다. 

<br>
<br>

<img width="800" height="500" src='https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN17-2nd-4Team/blob/main/image/%ED%8E%98%EC%9D%B4%EC%8A%A4%EB%B6%81%20%EC%9D%B4%EC%9A%A9%20%EA%B7%B8%EB%9E%98%ED%94%84%201.jpg'>

> https://www.i-boss.co.kr/ab-6141-59928
> 출처 : 오픈서베이 소셜미디어·검색포털 트렌드 리포트 2023

위의 그래프는 2023년 발표된 오픈서베이의 소셜미디어·검색포털 트렌드 리포트에서 발표된 그래프로 최근 일주일 내 사용한 소셜네트워크 시스템 순위 중 페이스북이 22.6%로 7위를 기록하는 등 동일한 리포트에서 3위를 기록했던 것에 비해 많이 떨어진 순위를 보이고 있습니다.

<br>
<br>

<img width="670" height="627" alt="image" src="https://github.com/user-attachments/assets/13150251-0be3-43a7-96bd-6e85accadd69" />

> https://www.wiseapp.co.kr/insight/detail/517
> 출처 : 2024. 와이즈앱·리테일 '희비 엇갈린 SNS 앱 인스타그램 vs 페이스북 비교'

<br>
<br>

| | |
|:---|:---|
|<img width="600" height="300" alt="image" src="https://github.com/user-attachments/assets/639bc8a7-162e-41fd-b1b6-89720eb2fd2c" />|<img width="600" height="300" alt="image" src="https://github.com/user-attachments/assets/86dc6a9c-85ed-4db8-a7c7-95c873108c5d" />|
| 페이스북 앱 사용자 및 사용시간 추이 | 인스타그램, 페이스북 앱 월간 사용자 추이 |


위의 그래프와 같이 페이스북의 사용 추이가 계속 감소되고 있습니다. 


요즘의 2030 세대의 경우, 학창시절 페이스북을 가장 주된 SNS로 사용했던 세대이기도 하지만 페이스북 이탈률이 가장 많은 세대라는 것을 확인할 수 있습니다. 
이에 따라 저희는 SNS 사용자의 개인 특성 데이터를 기반으로 페이스북 이탈률 예측을 하고자 합니다. 

<br>
<br>

### ▶️ 프로젝트 목표 


<br>
<br>

### ▶️ 수집데이터 설명
🔹[ 자동차등록현황보고 ]
- 출처: 국토교통부 통계누리
- 수집 방법: 국토교통부 통계누리에서 제공하는 연도별 통계 자료 엑셀 파일 다운로드
- 데이터 출처 및 범위
   - 수집 데이터 기간: 2020년 1월 ~ 2024년 12월
   - 데이터 규모: 약 16,320여 개의 데이터
   - 지역적 범위: 전국
   - 주요 변수
      : 연도, 지역, 연료종류, 등록현황
- 데이터 설명
     : 국토교통부에서 대한민국 교통행정의 기초자료로 활용하기 위해 시·도별로 등록된 자동차의 제반사항을 파악한 자료로 지역별 등록 차량 현황 자료임.
       연도별 차량 수와 분포(차종, 연료별)를 지역별 기준에 따라 등록 현황을 판단할 수 있으며, 본 프로젝트에서는 이 데이터를 기반으로 지역별 보조금 변동이 친환경차량에 주는 영향 파악에 활용하였음.

<br>
<br>

-----

# 3. 기술 스택
|Python|MySQL|Github|Pandas|Matplotlib|Streamlit|Selenium|
|---|---|:---|---|---|---|---|
|<img src="https://img.shields.io/badge/python-3776AB?style=for-the-badge&logo=python&logoColor=white">|<img src="https://img.shields.io/badge/mysql-4479A1?style=for-the-badge&logo=mysql&logoColor=white">|<img src="https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white"> <img src="https://img.shields.io/badge/git-F05032?style=for-the-badge&logo=git&logoColor=white">|<img src="https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white">|<img src='https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black'>|<img src='https://img.shields.io/badge/Streamlit-%23FE4B4B.svg?style=for-the-badge&logo=streamlit&logoColor=white'>|<img src='https://img.shields.io/badge/-selenium-%43B02A?style=for-the-badge&logo=selenium&logoColor=white'>|

<br>
<br>

-----

# 4. WBS
![WBS이미지](https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN17-1st-3Team/blob/main/image/streamlit/WBS.png)

<br>
<br>

-----

# 5. 요구사항 명세서
![요구사항이미지](https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN17-1st-3Team/blob/main/image/streamlit_2/%EC%9A%94%EA%B5%AC%EC%82%AC%ED%95%AD%EB%AA%85%EC%84%B8%EC%84%9C_2.png)
<br>
<br>

-----

# 6. ERD
![1차 프로젝트 ERD](https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN17-1st-3Team/blob/main/image/streamlit_2/erd.png)
<br>
<br>

-----

# 7. 수행결과(시연 페이지)
##              [STREAMLIT 구현화면]
## ▶️ 연도별, 지역별 친환경 차량 현황 및 보조금 현황 시각화 

# 8. 한 줄 회고
|이름|내용|
|:---:|:---|
