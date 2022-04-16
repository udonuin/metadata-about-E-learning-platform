# 온라인 이러닝 플랫폼에 대한 (학습) 메타데이터

## EduCOR : An Educational and Career-Oriented Recommendation Ontology **[논문 링크](https://arxiv.org/abs/2107.05522)**

## - 개요
> **온라인 학습 플랫폼의 의존도가 증가**함에 따라,   
> **디지털 학습 자원의 통합된 표현**은 동적 및 다중 소스 학습 경험을 지원하기 위해 **필수적**이다.   
> 따라서 **개인화된 학습 시스템을 위한** 온라인 학습 자원을 표현하기 위해,   
> 기초를 제공하는 교육적이고 경력 지향적인 온톨로지인 **"EduCOR ontology"** 를 소개한다.
>   
> 이러한 온톨로지는 **학습 자료 저장소**가 사용자의 학습에 해당하는 **학습경로 권장사항을 제공**할 수 있도록 **설계**된다.

## - [Resource](https://tibonto.github.io/educor/)
## - 키워드
: **온톨로지** / **교육 자원** / 교육 / **노동시장** / 스킬 / **학습 경로** / 사용자 프로필 / **개인화된 권장사항**

## 1. 소개
최근 디지털 교육은 ERs(교육 자원, Educational Resources)와 OER(개방형 교육 자원, Open Educational Resources)에 의존하고 있다.   
이때, ERs(교육 자원)은 비디오, 디지털 교과서, 강의의 오디오 녹음, 간단한 웹 페이지, 슬라이드 덱 등과 같이 다양한 형태로 이용 가능하다.   

ERs와 OER은 대게 저품질 메타데이터와 함께 제공되고, 다른 혹은 비슷한 내용상의 ER(교육 자원)들로부터 떨어져 있다.   

즉, 이는 OERS(개방형 교육 자원)에 기반한 고품질 서비스 (Ex. 추천 및 검색 서비스)가 부족한 이유 중 하나로 대두된다.   

공개적으로 사용 가능한 ER과 OER에 메타데이터를 향상시키는 것과 ERS를 분류하고 구성하는 것에 SW(the Semantic Web) 커뮤니티의 관심이 높아진 것은 놀랍지 않은 결과이다.   

많은 어휘들과 스키마가 제안되었지만, 그들 중 일부만 온라인에서 이용 가능함과 동시에 OERS의 특수성 및 개인화된 추천 시스템의 특징을 수용할 수 있다.   

교육 지식 그래프에 대한 관심이 증가했지만, 근본적인 온톨로지 or 스키마가 부족하다.   
또한, 상용 제품들은 그들의 기본 지식 스키마를 사용하지않거나 게시하지 않으므로 비슷한 방향을 따르는 것처럼 보인다. 

e-learning에 대한 설문조사에 따르면, 개인화된 추천 시스템을 달성하는 데 온톨로지가 도움이 되고
스마트 교육을 달성하기 위해 인공지능으로 현재의 도구를 풍부하게 하기 위한 교육 측면의 관심이 증가하고 있는 추세다.   
이러한 측면에서 온톨로지는 스마트 튜터링 시스템에 매우 다양한 이점을 제공한다.   

the SW(the Semantic Web)은 질문 답변 및 (학습) 추천 시스템에 상당한 초점을 맞추고 있다.  
(학습) 추천 시스템은 개인화된 학습 권장사항을 제공하면서, 상호운용성, 설명성 및 사용자 개인정보를 제공하도록 빠르게 발전하고 있다.   

사회는 교육의 디지털 전환에 엄청난 노력을 쏟고 있는데 (Ex. 유럽 연합의 디지털 교육 계획)   
일과 관련된 기술을 일치 시키고, 온라인 학습 플랫폼에서 기술을 개발하고 있다.   

COVID-19 범유행 기간 동안 온라인 학습 플랫폼은 수백만명의 학습자에 의해 매일 사용되고 있다.   
결과적으로 직업변화, (재)기술 또는 실업기간 후 노동시장에 (재)진출하는 사람들을 도울 수 있는 평생학습 도구의 필요성이 대두되고 있다.   

복잡한 학습 환경에서 학습 프로세스를 모델링하는 새로운 방법이 필요하므로 교육의 개인화 어젠다가 필요하다.  
하지만, 이는 특히 학습 과정의 구성요소(Ex. 교육(학습 콘텐츠 및 교육), 노동시장(학습 컨텍스트), 학습자의 개별 요구(학습 목표))가 유래되었을 때 어렵다.   
e-learning 및 직업 온톨로지로서 사용할 수 있는 직업은 많으나, 현재 이 두 도메인을 연결할 수 있는 모델은 없다.   
따라서 SW와 더 광범위한 지역사회의 관심에 따라 교육 및 경력 지향 추천 온톨로지인 "EduCOR ontology"를 개발하게 되었다.   
이는 풍부한 메타데이터를 ER, 기술 및 사용자의 프로필을 설명한다.   

EduCOR의 역할
1) 개인화된 OER 추천 시스템을 위한 잠재적 프레임 워크
2) 교육 지식 그래프의 기초를 모두 제공
- 학습자의 학습 경로와 사용자의 프로필을 기반으로, 개인화된 추천 시스템을 위한 ER 모델링에서 새로운 장을 열고 있다.
- 개인화된 학습 추천 시스템과 교육 데이터 및 기술을 노동시장과 연결하는데 있어 필수적인 격차를 메우고 있으므로 향후 응용에 필수적인 스키마가 되고 있다.   

## 2. EduCOR Ontology
EduCOR ontology 제안 목적
1) 공통 온톨로지 하에 서로 다른 ER 및 OER를 구성
2) 노동시장에 연결
3) e-learning 도메인에서 개인화된 추천 시스템을 제공

결론적으로, 온톨로지를 구성하는 주요 구성 요소를 식별한다.

>**2-1. 온톨로지 구성**   
> 이 온톨로지는 개인화된 권장 사항을 지원하는 e-learning 환경을 구성하는데 필요한 클래스 및 속성을 소개한다.
> 한편, IEEE LOM Standard7과 LRMI Standard8를 채택 & CSSO 및 Schema.org의 부품을 재사용 한다.
> 온톨로지 표현을 위해 OWL을 사용하고, FARE 원칙을 따라 이에 대한 참조를 포함하는 어휘를 재사용 한다.
> 다른 온톨로지를 매핑하여 보다 구체적인 활용도를 얻을 수 있는 플러크인 포인트로 클래스를 제공한다.
   
>**2-2. 패턴**   
> EduCOR은 온톨로지의 완전한 스키마를 만들기 위해 결합될 수 있는 독립적인 모듈로 구성된다.
> 이때, 모듈을 패턴이라고도 한다.
> 요구사항 분석을 기반으로 개인화된 학습 추천 시스템의 주요 구성 요소를 식별했다.

**EduCOR가 식별하는 패턴**
- 교육 자원
- 지식 주제
- 기술
- 학습 경로
- 테스트
- 권장사항
- 사용자 프로필

**패턴 특성**
- 각 패턴은 단독으로 존재한다.   
- 응용 프로그램이 해당 패턴을 필요로 하거나 필요로 하지 않을 경우 EduCOR 온톨로지로부터 분리된 단일 패턴으로 사용되는 다른 온톨로지에 추가할 수 있다.   


## 3. 사용 사례 시나리오   
## 4. 평가   
>**4-1. Gold standard-based 평가**   
>**4-2. Task-based 평가**
## 5. 관련 작업      
## 6. 토론 및 향후 단계      
## 7. 결론
