# premier league 승패 비교 분석 프로젝트
----------------
## 프로젝트 소개
>이 프로젝트는 프리미어리그(영국 축구의 최상위 리그)에 뛰었던 팀들에 대한 성적을 분석한 것이다. 각 팀별 승,무,패의 비율과 골 수를 분석한 것이며 이 프로젝트의 최종 목표는 <U>**데이터를 활용하여 정보를 시각화**</U>하는 것이다.

>또한 이 프로젝트를 통해 프리미어리그 축구팀 중 관심이 있는 사람이 자신이 좋아하는 팀에 대한 시각적인 정보를 얻을 수 있다.

## 진행 과정
### 1. 주제 선정 이유
> 프리미어리그 축구팀 중 관심이 가는 팀에 대한 정보를 찾아보고 팀들에 대한 승률 및 팀별 골 수를 알아보고 싶었다.

### 2. 데이터 소개
> 선정한 데이터 : kaggle에서 [1993~2022까지의 프리미어리그 성적](https://www.kaggle.com/datasets/irkaal/english-premier-league-results?resource=download)을 다운로드 하였다.

> 데이터에서 사용한 내용들

|목록|내용|설명|
|------|---|---|
|Season|Match Season|매치 시즌|
|HomeTeam|Home Team|홈 팀|
|AwayTeam|Away Team|원정 팀|
|FTHG|Full Time Home Team Goals|홈 팀 풀타임 골|
|FTAG|Full Time Away Team Goals|원정 팀 풀타임 골|

### 3. 데이터 전처리 & 분석 및 시각화
* 1993~2022년까지 데이터를 1개의 파일로 종합
* 데이터의 내용에서 필요로하는 내용만을 추출 => Season , HomeTeam , FTHG , FTAG을 통해 팀들의 성적을 분석함.
* 현황 분석 및 시각화
  *  1993년부터 2022까지 프리미어리그를 뛰었던 팀 별 승패 여부(예시 : 홈팀 - 맨유 / 원정 팀 - 토트넘)
  
     <img width="313" alt="승부 유무" src="https://github.com/user-attachments/assets/216607e1-e010-4bb4-a126-81406a0c4d2f" />

  *  프리미어리그 출범이후 뛰었던 팀들에 대한 데이터 표1(팀별 골 수)
   
     <img width="340" alt="팀별 골 수" src="https://github.com/user-attachments/assets/5058afeb-5d9f-478e-8f87-09d831b0d75c" />

  *  프리미어리그 출범이후 뛰었던 팀들에 대한 데이터 표2(팀별 전체 득실)

      <img width="334" alt="팀별 전체 득실" src="https://github.com/user-attachments/assets/1f7f2cc8-a394-41c1-85b2-86d9799b23a2" />

  *  프리미어리그 출범이후 뛰었던 팀들에 대한 데이터 표3(팀별 승률)

     <img width="339" alt="팀별 승률" src="https://github.com/user-attachments/assets/e312c0e9-39a6-4630-bead-db5a42a2e467" />


### 4. 데이터 코드 바로가기
> [데이터 코드](https://github.com/monolail/-Premier-League-win-loss-analysis/blob/main/Term_Project_7%EC%B0%A8_%EA%B3%84%ED%9A%8D%EC%84%9C_2022105488_%EC%9D%B4%ED%98%B8%EC%A4%80.ipynb)

### 5. 프로젝트를 진행한 후 느낀점
1. 프로젝트를 진행하며 pandas,matplotlib,seaborn 등 파이썬의 다양한 라이브러리를 직접 만져봄으로써 다양한 라이브러리에 대한 지식을 쌓을 수 있었다.
2. 라이브러리에 대한 지식이 아직 부족하여 상당 부분에서 다른 사람들의 도움 또는 인터넷에서 직접 찾아가며 코드를 작성하였기 때문에 실력적인 부분에서 파이썬을 다루는 것에 아직 미흡하다고 느꼈다.
