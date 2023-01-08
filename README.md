# 😎 교원투어 > 제휴서비스 API
> 교원투어에는 "여행이지" 라는 여행상품을 판매하는 자체 B2C사이트가 존재하지만 매출향상의 목적으로 다른 채널(제휴사)과의 계약을 통해 교원투어의 여행상품을 노출하고 판매하기 위한
제휴사 - 교원투어간의 행사 노출, 행사정보 갱신 및 예약 연동 API 프로젝트입니다.

## 💻TOOL
> SPRING,ORACLE

## ✨INFO
🌱 상품(행사) LIST API
> * 제휴사에 노출할 행사 리스트 정보를 전송하는 API
> * 해당 제휴처에 판매 가능한 행사 데이터를 전송하기 위한 목적

<div>
   <img src="https://user-images.githubusercontent.com/87461392/211046385-714a3631-9973-4f4a-b4d6-9c0b2f245835.PNG"  width="400" height="700"/>
   <img src="https://user-images.githubusercontent.com/87461392/211057723-03e31318-1b55-467b-b31d-0b7ebd8f3a4a.PNG"  width="400" height="700"/>
</div>
<br/>

🌱 행사정보갱신 API
> * 각 제휴처에서 고객이 상품을 클릭하여 상세페이지에 진입하였을때 실시간 호출을 통해 해당 행사의 상세 데이터를 응답하는 API <br/>
> * 비용, 잔여좌석 등 실시간으로 변동되는 데이터를 갱신하기 위한 목적

<div>
   <img src="https://user-images.githubusercontent.com/87461392/211048678-ae99383c-c99e-49fb-80fa-209c87b27679.PNG"  width="400" height="700"/>
   <img src="https://user-images.githubusercontent.com/87461392/211048826-e41660ad-b9d2-45c9-942c-8bba41629ae4.PNG"  width="400" height="700"/>
</div>
<br/>

🌱 예약연동 API
> * 각 제휴처에서 전송하는 교원투어 상품의 예약 정보를 수신하는 API
> * 외부채널(제휴사)에서의 예약 데이터를 내부에서 예약처리 및 관리하기 위한 목적


## 👯Copyright
* API 예시 사진 - 출처 : 트립스토어 [[이동하기](https://www.tripstore.kr/)]

## 😄TAKEAWAYS

1. (DB)-JOIN과 SUBQUERY 및 함수를 사용하는 방법 및 INDEX의 중요성
2. XML / JSON 자료구조에 대한 이해
3. DATA-PARSING에 대한 이해 
4. REST-API호출을 위한 SPRING RestTemplate 사용법
5. Spring Batch의 개념 및 구조에 대한 이해
6. HTTP(S)통신 및 통신을 위한 방화벽 관련 지식
7. 로직의 모듈화 및 EXCEPTION 공통화의 중요성

## 🔲REVIEW
첫 BACK-End 프로젝트를 진행하며 REST-API에 대해 이해할 수 있었고, 무엇보다 DB QUERY의 중요성도 느낄 수 있었습니다. 더불어 DATA-PARSING에 대해 학습할 수 있었습니다.
개인적으로 메인기능을 처음부터 끝까지 스스로 구현해 볼 수 있었던 좋은 경험이었고 큰 문제없이 구현하였다는점에서 만족하지만 세부적으로는 코드 최적화 부분에서 많이 아쉬움이 남는 것 같아 이후 프로젝트에서는 부족한 부분을 좀 더 보완하여 성장하고 싶은 다짐을 갖게 해준 PROJECT였습니다.

