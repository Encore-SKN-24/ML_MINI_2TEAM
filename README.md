# SKN24-ML_MINI_2TEAM
## 🧀시골쥐들의 서울내기🐭
*"서울시 전세사기 위험 머신 러닝 모델"*

## 1. 팀 소개

## 1-1.팀명
### 🧀시골쥐들🐭

## 1-2. 팀원
|   이름   | GitHub            | 
|:--------:|:-----------------:|
| 권민세 | [KweonMinSe0109](https://github.com/KweonMinSe0109) |
| 김정현 | [Jeich-16](https://github.com/Jeich-16) |
| 박영훈 | [aprkaos56](https://github.com/aprkaos56) |
| 황인규 | [hwang-in-kyu](https://github.com/hwang-in-kyu) |

---

## 2. 📋 프로젝트 개요
<img width="805" height="821" alt="image" src="https://github.com/user-attachments/assets/b5732ffc-5c08-4462-a309-9d6532e0e6d0" />

자료: https://housinginfo.seoul.go.kr/hmpg/homa/trou/homaDetail.do


> 본 프로젝트는 서울시 전세 실거래 및 공공 데이터를 활용하여 전세사기 발생 가능성을 정량적으로 분석하고, 머신러닝 기반 위험 예측 모델을 구축하는 것을 목표로 합니다.
단순 통계 시각화를 넘어, 개별 매물 단위에서 ‘전세사기 위험 확률’을 사전에 예측하는 데이터 기반 의사결정 지원 시스템을 구현합니다.
이를 통해 임차인이 보다 안전한 주거 선택을 할 수 있도록 지원하고자 합니다.

## 2-1. 프로젝트 소개
> 서울에서 자취와 독립을 시작하는 청년·사회초년생에게 전세 계약은 매력적인 선택지이지만, 동시에 전세사기라는 구조적 위험에 노출되어 있습니다.
기존 부동산 플랫폼은 매물 정보와 가격 정보는 제공하지만, 해당 매물이 얼마나 위험한지에 대한 ‘정량적 판단 기준’은 제시하지 못합니다.
저희 팀은 이러한 문제의식에서 출발하여, 공공 데이터를 통합 분석하고 위험 요인을 도출하며 머신러닝 모델을 활용해
“이 집은 위험한가?”를 확률로 예측하는 시스템을 구상했습니다.
즉, 단순 정보 제공이 아닌 ‘예측 기반 안전 가이드’를 만드는 것이 본 프로젝트의 핵심입니다.

## 2-1. 🖼️ 프로젝트 필요성(배경)
#### 사회적 문제 심화:
>  깡통전세 및 전세사기 피해가 여전히 발생하고 있으며, 청년층과 서민층의 주거 불안정이 심화되고 있습니다.
#### <img width="600" height="500" alt="image" src="https://github.com/user-attachments/assets/e56a9aa3-c1a3-4b50-aacb-23f68025671e" />
#### 출처: https://imnews.imbc.com/news/2025/econo/article/6781511_36737.html

#### 정보의 비대칭성:
>  전세 플랫폼과 HUG 보증제도로 물리적·법적 정보 접근성은 개선됐지만, 임대인의 재무상태나 과거 사고 이력 등 핵심 위험 정보는 여전히 비공개이기 때문에 구조적 정보 비대칭은 완전히 해소되지 않았습니다.
#### 사후 처리가 아닌 사전 예방 필요:
>  사고 발생 후의 대처보다, 공공 데이터를 활용한 선제적 위험 감지 시스템이 절실한 시점입니다.

---

## 2-2. 🎯 프로젝트 목표
#### 데이터 통합 분석:
 > 실거래가, 전세가율, 해당 동 평균 전세가 등 흩어져 있는 데이터를 하나로 통합합니다.
  
#### 핵심 위험 인자 도출:
 > 데이터 통합 분석으로 얻은 정보를 활용하여 실제 사기에 가장 큰 영향을 미치는 요인이 무엇인지 통계적으로 밝혀내는 것입니다.
  
#### 머신러닝 기반 위험 예측:
 > 2025년 서울시 부동산 거래 데이터를 분석하여, 전세사기 위험 여부 예측 및 위험 확률(%)을 수행하는 예측 모델을 개발합니다.

#### 사용자 친화적 시각화/서비스 구현
> 위험도를 직관적으로 이해할 수 있도록 위험 등급, 위험 확률 등을 시각화하여 실질적인 의사결정을 지원합니다.

---

## 3. 🧰 기술 스택
| 분류                 | 기술/도구                                                                 |
|----------------------|------------------------------------------------------------------------------|
| 언어          |![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)                                                        |
| 라이브러리   | ![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white) ![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white) ![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=for-the-badge&logo=python&logoColor=white) ![Seaborn](https://img.shields.io/badge/Seaborn-4479A1?style=for-the-badge&logo=python&logoColor=white) ![Scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)                                                     |
| 협업 툴       | ![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white) ![Notion](https://img.shields.io/badge/Notion-%23000000.svg?style=for-the-badge&logo=notion&logoColor=white)                                                   |                                                |

---

## 4. ✅ 데이터 출처
> 서울특별시 자치구별 전세사기 발생건수 (https://data.seoul.go.kr/dataList/OA-22867/F/1/datasetView.do)

> 서울특별시 실거래가/전월세가 공개시스템 (https://rt.molit.go.kr/pt/xls/xls.do?&mobileAt=) 

---

## 5. ✅ 데이터 전처리
#### 1. 각 컬럼 별 값 확인
#### <img width="1295" height="603" alt="image" src="https://github.com/user-attachments/assets/a14ffc8a-c3e6-4607-92c3-6b387f8d409a" />


## 5-1. ✅ ML 데이터 전처리(Part. 1)
#### 1. Logistic Regression (로지스틱 회귀)
#### <img width="1129" height="316" alt="image" src="https://github.com/user-attachments/assets/bfcfc37f-62ef-4571-a7f6-54a4f9de86f8" />

#### <img width="897" height="687" alt="image" src="https://github.com/user-attachments/assets/db4d423e-b39d-4217-8484-507d9b98e5f1" />
#### 출처: [https://imnews.imbc.com/news/2025/econo/article/6781511_36737.html](https://www.khug.or.kr/hug/web/cs/no/csno000001.jsp?id=16&mode=S&articleId=35430) HUG(주택도시보증공사)

#### <img width="1569" height="564" alt="image" src="https://github.com/user-attachments/assets/8ade5236-3973-4157-b97a-c7b9a8c5d57f" />

#### <img width="269" height="318" alt="image" src="https://github.com/user-attachments/assets/a5261dc9-c978-4c9e-9504-cc1f6732e810" />

#### 2. 전세가율 - 건물나이 시각화 자료
#### <img width="577" height="656" alt="image" src="https://github.com/user-attachments/assets/d5a1190b-ea19-43d2-bab7-0c4cfe9a8925" />

#### 3. y값 설정 및 전처리 과정
#### <img width="809" height="597" alt="image" src="https://github.com/user-attachments/assets/b9a8a67d-73bf-4bb8-8fec-6d3954b9edf0" />

#### class_weight='balanced'를 적용하기 전
#### <img width="297" height="131" alt="image" src="https://github.com/user-attachments/assets/bdd1d8ff-0213-48d7-bbc8-c94e099e6311" />


#### class_weight='balanced'를 적용한 후
#### <img width="427" height="195" alt="image" src="https://github.com/user-attachments/assets/7bcc43a2-0c17-4cb1-a504-b26c4f607dcb" />
#### <img width="573" height="347" alt="image" src="https://github.com/user-attachments/assets/fc301e65-6e3c-425d-943b-01cc41f3c8a8" />



#### 4. Random Forest (랜덤 포레스트)
#### <img width="471" height="433" alt="image" src="https://github.com/user-attachments/assets/48881e40-536d-4c3e-8027-5dce0840f2c7" />

#### <img width="445" height="271" alt="image" src="https://github.com/user-attachments/assets/0f127974-c30b-46f6-a60a-6c13bdba85c7" />


#### 5. 회귀 분석
#### <img width="883" height="360" alt="image" src="https://github.com/user-attachments/assets/c1fb5faa-5f96-42d4-ac0d-b31c812f53ec" />

#### <img width="895" height="412" alt="image" src="https://github.com/user-attachments/assets/9b46b928-0019-435c-903f-dce41efa3c43" />


#### 6. 실제-예측 값 도출 결과

#### <img width="427" height="592" alt="image" src="https://github.com/user-attachments/assets/912f4b6a-f16e-4b4d-82f8-0f5bb0235200" />



## 5-2. ✅ ML 데이터 전처리(Part. 2)
#### <img width="1330" height="512" alt="01" src="https://github.com/user-attachments/assets/368824dc-a22c-4fa3-a9a3-c88b52ec821a" />
#### <img width="871" height="467" alt="05" src="https://github.com/user-attachments/assets/8935bef7-a04e-4cd0-96d5-77710fcda4f0" />
#### <img width="1632" height="567" alt="06" src="https://github.com/user-attachments/assets/d346ba29-7481-4a73-bd20-0de1935a788a" />
#### 1. KNN
#### <img width="875" height="408" alt="07" src="https://github.com/user-attachments/assets/dc71fa42-2c4e-4b45-b550-74b61b620972" />
#### <img width="1007" height="507" alt="08" src="https://github.com/user-attachments/assets/cfb2265f-f249-4d85-8f8a-f16847d202e6" />
#### <img width="1231" height="617" alt="10" src="https://github.com/user-attachments/assets/99a59c8e-a077-4713-b421-cdff40c2afff" />
#### <img width="863" height="492" alt="11" src="https://github.com/user-attachments/assets/82d29d21-0e35-4ca8-b5a8-8b8f25500e78" />
#### <img width="805" height="45" alt="12" src="https://github.com/user-attachments/assets/69384ed0-2de4-489e-ad55-3cd5e4d0adbd" />
#### 2. XGBoost
#### <img width="742" height="336" alt="15" src="https://github.com/user-attachments/assets/08cff1fe-20b7-451b-bb50-2700eccc59a9" />
#### <img width="787" height="592" alt="16" src="https://github.com/user-attachments/assets/a34fcfef-6ca8-4efc-af2c-604b19e474bf" />
#### <img width="1061" height="533" alt="17" src="https://github.com/user-attachments/assets/4db6b7d8-f476-4515-858a-816944433def" />
#### <img width="617" height="78" alt="18" src="https://github.com/user-attachments/assets/57336cdf-7808-43f8-9198-45da3f150916" />
#### <img width="551" height="71" alt="19" src="https://github.com/user-attachments/assets/e707cee5-eb1f-42e8-bf2d-9fcfe739dda6" />
#### <img width="1016" height="81" alt="20" src="https://github.com/user-attachments/assets/7255c902-7a2e-414c-a82c-f219a220a91a" />
#### <img width="490" height="67" alt="21" src="https://github.com/user-attachments/assets/6f8c83b5-e99f-4d1b-b3c9-5d2333a24c3b" />
#### <img width="797" height="43" alt="22" src="https://github.com/user-attachments/assets/31d3488b-8094-47bc-8672-b4e4e261b9c7" />
#### <img width="1012" height="543" alt="23" src="https://github.com/user-attachments/assets/caca8253-6225-40f6-8324-8baf247739cb" />




## 6. ℹ️ 인사이트 도출 
> Logistic Regression, Random Forest, XGBoost 모델을 비교 실험한 결과, 전세사기 위험은 통계적 패턴을 통해 충분히 분류 가능함을 확인했습니다. 특히 Random Forest와 XGBoost와 같은 트리 기반 앙상블 모델은 복잡한 변수 간 상호작용을 효과적으로 학습하여 선형 모델보다 우수한 성능을 보이는 것을 파악하였습니다. 그 중 특히, XGBoost 모델은 위험 매물 탐지 능력에서 가장 뛰어난 결과를 나타낸다는 점도 파악할 수 있었습니다. 이는 전세사기 예방 목적에서 ‘정확도’보다 ‘위험 사례를 놓치지 않는 탐지율’이 더 중요하다는 점을 시사하며, 결과적으로 트리 기반 앙상블 방식이 본 문제에 가장 적합한 모델임을 알 수 있었습니다.


## 7. 📈 프로젝트 기대 효과
#### 임차인의 합리적 의사결정 지원:
 > 본 프로젝트는 개별 매물의 전세사기 위험을 확률(%) 형태로 정량화하여 제공함으로써, 임차인이 단순 감이나 경험이 아닌 데이터 기반 객관적 지표를 활용해 계약 여부를 판단할 수 있도록 지원합니다.
  
#### 전세사기 사전 예방 효과:
 > 기존 제도(HUG 보증, 사후 구제 정책 등)는 사고 발생 이후 대응에 초점이 맞춰져 있습니다. 반면, 본 프로젝트는 사전 예측 모델을 통해 위험 매물을 계약 전에 탐지함으로써 피해 발생 자체를 줄이는 예방적 접근을 제시합니다.
  
#### 데이터 기반 사회문제 해결 사례 제시:
 > 본 프로젝트는 데이터 분석과 머신러닝 기술을 활용하여 사회적 문제(전세사기)를 예방하고, 데이터 사이언스가 실생활 문제 해결에 어떻게 기여할 수 있는지 보여주는 실증적 사례라는 의의를 가질 수 있습니다.

---


## 8. 💭 한 줄 회고
### - 권민세: 
 전처리 과정에서 필요한 칼럼을 단순히 추출하는 데 그치지 않고, 결측값을 확인하고 처리하며 여러 칼럼 간 연산을 통해 새로운 지표를 생성해 보는 경험을 할 수 있어 뜻깊었습니다. 전세가율 구간별로 주택 유형과 건물 나이를 비교하는 과정에서는 예상처럼 시각화 결과가 바로 나타나지 않아 위험 기준을 설정하는 데 어려움을 겪었지만, 여러 기준을 계속 적용해 보며 이를 해결할 수 있었습니다. 앞으로는 기준 설정 단계에서 데이터 분포를 더 자세히 검토해 봐야겠다고 생각했습니다.
  
### - 김정현:
  지난 EDA 과정을 통해 파악한 데이터 특성을 바탕으로 다양한 머신러닝 모델을 적용해 보았습니다. 특히 하이퍼 파라미터 튜닝과 변수 선택 과정에서 치열하게 고민했던 경험은 모델 성능 향상을 위한 소중한 자산이 되었습니다.
  반면에, 프로젝트 후반까지 X, y 데이터 설정에 대한 확신을 갖지 못해 두 가지 방안을 병행 운영했습니다. 이는 학습 측면에서 다양한 시각을 갖는 계기는 되었으나, 실무 관점에서는 자원 배분의 효율성이 떨어질 수 있겠다고 느꼈습니다. 개선을 위해 고민이 길어질 경우 데드라인을 정해 리소스 낭비를 방지하겠습니다. 또한 실험 초기 단계에서 명확한 가설을 수립하여 '선택과 집중'을 할 수 있도록 하겠습니다.
### - 박영훈:
 구성원 모두가 공감할 수 있는 주제를 선정해 프로젝트를 진행함으로써, 더욱 높은 몰입도와 책임감을 가질 수 있었습니다. 또한, 다양한 머신 러닝 모델을 활용한 결과, 트리 기반의 앙상블 모델에서의 성능이 뛰어나다는 점을 파악할 수 있었습니다. 특히, XGBoost 모델을 활용하는 과정에서 너무 많은 데이터의 학습은 시스템 과부화의 원인으로 작용할 수 있다는 점을 발견할 수 있었으며, 이에 따른 다양한 모델을 활용하거나 데이터의 간소화 전략을 취한다면 보다 좋은 결과물을 얻을 수 있겠다는 판단이 들었습니다. 뿐만 아니라, X 데이터 컬럼이 y 데이터 컬럼과 혼합되어 정확한 학습 결과를 얻지 못한 적이 있는데, 보다 세밀히 구분하여 데이터를 분리하고 학습을 진행하도록 신경써야할 필요가 있다는 교훈을 받았습니다.
  
### - 황인규:
본 프로젝트를 통해 전세 위험을 단순 수치가 아닌 지역·주택유형별 상대적 지표로도 해석할 수 있다는 점을 알 수 있었습니다. 부동산 데이터의 이상치는 제거 대상이 아니라, 오히려 위험 신호로서 의미를 가질 수 있음을 분석 과정에서 확인하였습니다. 또한 흩어진 공공 데이터를 정제·통합하고 기준을 정의하는 과정이 모델 성능만큼 중요한 분석 단계임을 체감했습니다. 데이터 분석이 청년 주거 문제와 같은 현실적인 사회 문제 해결에 기여할 수 있음을 느낀 프로젝트였습니다.


