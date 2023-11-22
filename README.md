# 2023 Corning AI challenge 💻
<br/>

#### 본 대회의 운영 방법 및 기간은 사전 공지 후 바뀔 수 있습니다. 본 웹사이트를 자주 확인하세요 


--------

#### (2023-11-22) !!!추가 공지사항!!! - 참가자들과의 대화 일정


어느덧 AI challenge 종료 시점이 다가오고 있습니다. 

그리하여 저희는 참가자분들을 모시고, 현재 진행하시는 프로젝트에 대해 간단한 설명/진행상황을 듣고자 합니다. 
목적은 해당 프로젝트를 수행하시며 어려운 점은 없으신 지 파악하고, 원활한 challenge 수행을 지원하고자 함입니다. 

프로젝트 주제에 대한 간단한 설명 (ppt 1~2) 정도를 공유해주시면 되고, 요청사항이 있으시면 알려주세요.
(중간 평가 등의 목적은 아니며, 선택한 세부 주제와 접근법 등을 간단히 공유하는 자리입니다.)
<br/><br/>
미팅 일정 : TBD, last updated 2023-11-22
|  &nbsp;&nbsp; | 11/27(월) | 11/28(화) | 11/29(수) | 11/30(수) | 12/01(금) |
|:--------|:--------:|--------:|:--------|:--------:|--------:|
| Inverse design |  &nbsp; | &nbsp; | &nbsp; | &nbsp; | &nbsp; |
| 나혼자 LLM |  &nbsp; | &nbsp; | &nbsp; | &nbsp; | &nbsp; |
| BBD |  &nbsp; | &nbsp; | &nbsp; | &nbsp; | &nbsp; |
| BIG212HO |  &nbsp; | 오후2-4 (단독) | &nbsp; | &nbsp; | &nbsp; |
| Closed AI |  &nbsp; | &nbsp; | &nbsp; | &nbsp; | &nbsp; |
| 예티 |  &nbsp; | &nbsp; | &nbsp; | &nbsp; | &nbsp; |
| PADON |  &nbsp; | &nbsp; | &nbsp; | &nbsp; | &nbsp; |
| HAI |  &nbsp; | &nbsp; | &nbsp; | &nbsp; | &nbsp; |
| MnMs |  &nbsp; | &nbsp; | &nbsp; | &nbsp; | &nbsp; |
| AI w.o. CS |  &nbsp; | &nbsp; | &nbsp; | &nbsp; | &nbsp; |


--------
<br/>

## 대회 개요 💬
1. 참가 자격 : AI를 이용한 문제 해결에 관심있는 한양대학교 대학생 / 대학원생 (팀 또는 개인, 팀 최대 인원은 3인으로 제한, 중복참여 불가능)
1. 대회 기간 : ⏰ 2023.10.18 ~ 2023.12.11 (🔗 [참가 신청 link](https://recruit.incruit.com/corning/job/2310100017))  &nbsp;&nbsp; | &nbsp;&nbsp;  (평가) ~ 2023.12.15 &nbsp;&nbsp; | &nbsp;&nbsp; (시상) 12월 4째 주  <br/> * 중간 리뷰는 선택 사항입니다. (2023.11.13 ~ 2023.11.24) <br/> * 참가신청 웹페이지 구성이 복잡합니다. [🔗 설명서](https://github.com/corning-ai-challenge/signup)를 참고하세요~<br/>
1. 수상 혜택 : 🥇 500만원 (1팀) / 🥈 200만원 (1팀) / 🥉 100만원 (3팀) &nbsp;&nbsp;|&nbsp;&nbsp; 해외 corning lab과의 교류 기회 제공<br/>
<br/><br/><br/><br/>

## Challenge items 🏃 (아래 주제 중 1개 선택)

#### 아래 3개 범주에 해당하면 세부주제의 제한은 없습니다. 단, 세부주제는 담당자와 사전 협의 후 진행하여야 합니다. 
#### 대회 중간에 주제 변경은 담당자와의 협의 후 가능합니다.
<br/>

1. Large language models (LLMs)을 이용한 query engine 작성 (🔗 [상세 page link](https://github.com/corning-ai-challenge/item1.git))

   Local LLMs를 이용하여, 다양한 파일 형태 (word, pdf, webpage 등)의 대용량 문서를 embedding. 사용자의 query를 유사도에 기반하여 처리하는 모델 개발. (개발된 시스템은 대화형 인터페이스를 갖고 있어야하며, refenence list도 함께 출력되어야함)

2. 생성형 AI를 이용한 inverse problem 해결 방법 제안 (🔗 [상세 page link](https://github.com/corning-ai-challenge/item2.git))
   
   생성형 AI를 이용하여, 결과 데이터(실험 / 시뮬레이션)로 부터 이를 야기한 물리적 법칙을 추론할 수 있는 모델 개발. 최종 결과에는 데이터와 학습된 모델 사이의 연관 관계룰 설명할 수 있는 자료가 포함 되어야 함 (XAI 등 이용).

3. Machine learning을 이용한 편미분 방정식 (partial differential equation, PDE)의 해석법 제안) (🔗 [상세 page link](https://github.com/corning-ai-challenge/item3.git))
   
   전통적인 수치해석 방법 대신 machine learning 기법 (PINN, Deep operator 등)을 이용하여, 편미분 방정식의 해를 추론할 수 있는 모델 개발. (어떠한 종류의 편미분 방정식을 사용해도 상관없으나, 해의 엄밀성을 기존 방식과 비교하여 제시하여야 함)
<br/><br/><br/><br/>


## 평가 기준 📝
1. 짧은 대회 기간을 고려하여, 문제 해결 방법의 참신함과 구현 정도를 평가 <br/> * 정성평가로 leaderboard 미운영 <br/> * 개발된 모델의 scalability, 기능 동작 여부 등을 중요하게 평가 예정 <br/> *  매주 월요일 오전, 본 페이지에 팀별 진척도 공지 
3. 동일 점수일 경우, commit 날짜가 빠른 순서로 수상자 선정
<br/><br/><br/><br/>


## 문의 ❓
문정환 프로 : 📧 moonj5(@)corning.com / 추후 참여 인원 대상으로 slack, discord 채널 공지
<br/> * GPU 자원이 필요한 경우 문정환 프로에게 e-mail로 신청 (사용 가능 자원 NVIDIA A100 40GB X 4ea, 한양대학교 인공지능대학원 제공)


