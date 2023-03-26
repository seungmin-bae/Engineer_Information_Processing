# Engineer_Information_Processing
정보처리기사 情報處理技士 Engineer Information Processing 소프트웨어공학 기출문제 학습정리입니다.

## 정보처리기사 개요
[정보처리기사 CBT 기출문제](https://www.comcbt.com/xe/iz)
```
1과목 : 소프트웨어 설계 (20문항)
2과목 : 소프트웨어 개발 (20문항)
3과목 : 데이터베이스 구축 (20문항)
4과목 : 프로그래밍 언어 활용 (20문항)
5과목 : 정보시스템 구축관리 (20문항)

기출: 2020년 6월 개편(2020년 1,2회차 통합) 이후로 나온 기출만 본다.
시간: 하루에 6시간씩 3일 이상 공부
방법: 남이 만든 요약설명집을 받아서 수차례 읽고, 기출 무한회독
교재: 필기용 교재를 사지 말고, 차라리 실기 교재를 사서 적당히 보는게 낫다.
필기용 교재는 유튜브 같은 곳에 올라온 필기 영상들로 대체할 수도 있다.

1년에 3회로 시험이 실시되고 있다. 2020년도 이후 기출문제 위주로 공부
```

## 정보처리기사 합격 커트라인
```
필기 100점 만점 중 과목 당 40점 이상, 전과목 평균 60점 이상
대충 반타작이상 -한달 공부
실기 100점 만점에 60점 이상
```

## 2020년 6월 6일 기출문제 (1회 2회 통합)
2023-03-25 ~ 
#### 1. 검토회의 전에 요구사항 명세서를 미리 배포하여 사전 검토한 후 짧은 검토 회의를 통해 오류를 조기에 검출하는데 목적을 두는 요구 사항 검토 방법은?
```
워크스루 
```
##### 2. 코드 설계에서 일정한 일련번호를 부여하는 방식의 코드는?
```
순차코드
```
##### 5. 소프트웨어 설계시 구축된 플랫폼의 성능특성 분석에 사용되는 측정 항목이 아닌 것은?
```
어플리케이션 성능측정 항목은 응답시간, 처리량, 자원 사용률, 경과 시간이다.

따라서 답은 서버 튜닝
```
##### 11. XP(eXtreme Programming)의 5가지 가치로 거리가 먼 것은?
```
XP(eXtreme Programming)의 5가지 가치 
1. 용기(Courage) : 고객의 요구사항 변화에 능동적인 대처
2. 단순성(Simplicity) : 부가적 기능, 사용되지 않는 구조와 알고리즘 배제
3. 커뮤니케이션(Communication) : 개발자,관리자,고객 간의 원활한 의사소통
4. 피드백(FeedBack) : 지속적인 테스트와 반복적인 결함 수정, 빠른 피드백
5. 존중(Respect) : 모든 프로젝트 관리자는 팀원의 기여를 존중
```
##### 13. 소프트웨어 개발 방법 중 요구 사항 분석(requirements annalysis)과 거리가 먼 것은?
```
설계 명세서 작성은 요구 사항 분석 다음 단계인 명세에서 합니다.

요구사항 분석에서 하는 것 : 비용과 일정에 대한 제약설정, 타당성 조사, 요구사항 정의 문서화
```
##### 15. 공통 모듈에 대한 명세 기법 중 해당 기능에 대해 일관되게 이해하고 한 가지로 해석될 수 있도록 작성하는 원칙은?
```
명확성
```
##### 23. 소프트웨어 품질 측정을 위해 개발자 관점에서 고려해야 할 항목으로 거리가 먼 것은?
```
개발자 관점에서 고려해야할 사항 : 정확성, 신뢰성, 효율성, 무결성, 유연성, 이식성, 재사용성, 상호운용성
```

##### 33. 소프트웨어 테스트에서 오류의 80%는 전체 모듈의 20% 내에서 발견된다는 법칙은?
```
Pareto의 법칙 파레토의 법칙
```
##### 34. 소프트웨어 형상 관리의 의미로 적절한 것은?
```
개발 과정의 변경 사항을 관리하는 것 git, svn
```
##### 40. 외계인코드(Alien Code)에 대한 설명으로 옳은 것은?
```
아주 오래되거나 참고문서 또는 개발자가 없어 유지보수 작업이 어려운 프로그램을 의미한다.
```
##### 81. 프로토타입을 지속적으로 발전시켜 최종 소프트웨어 개발까지 이르는 개발방법으로 위험관리가 중심인 소프트웨어 생명주기 모형은?
```
Bohem이 고안한 나선형 모델(위험관리)
```

##### 98. 폭포수 모형의 특징으로 거리가 먼 것은?
```
개발 중 발생한 요구사항을 쉽게 반영할 수 있다< 없습니다. 선형 순차적이라 앞단계 다 끝냈는데 갑자기
뭐 들고오면 빡쳐서 안한다고 생각하면 됩니다.

폭포수 모형의 특징 : 선형 순차적, 단계가 끝나야 다음 단계로 넘어가기에 단계적 정의와 산출물이 명확합니다.
오래된 모형으로서 적용 경험 및 성공 사례가 많습니다.

폭포수 - 위에서 아래로 떨어진다라는 뜻에서 선형 순차적이며 다시 거슬러 올라갈 수 없기 때문에 요구 사항 변경이나
전 단계 수정이 어렵습니다.
```
## 2020년 8월 22일 기출문제 (3회)
2023-03-25 ~

#### 1. 요구 사항 분석 시에 필요한 기술로 가장 거리가 먼 것은?
```
분석 시에 필요한 기술 : 요구사항 분류, 개념 모델링, 요구사항 할당, 협상, 정형 분석
```
##### 4. 애자일 기법에 대한 설명으로 맞지 않는 것은?
```
애자일 개발 4가지 핵심 가치

1. 프로세스와 도구보다는 개인과의 상호작용에 더 가치
2. 방대한 문서보다는 실행되는 SW에 더 가치
3. 계약 협상보다는 고객과의 협업에 더 가치
4. 계획을 따르기보다는 변화에 반응하는 것에 더 가치
```

#### 22. 소프트웨어 공학의 기본 원칙이라고 볼 수 없는 것은?
```
기본 원칙 
1. 품질 높은 소프트웨어 상품 개발
2. 지속적인 검증 시행
3. 결과에 대한 명확한 기록 유지
```
