# Engineer_Information_Processing
정보처리기사 情報處理技士 Engineer Information Processing 소프트웨어공학 기출문제 학습정리입니다.
## 제1회 정보처리실기 가채점 04.27
![image](https://github.com/chihyeonwon/Engineer_Information_Processing/assets/58906858/54c4d28a-c29b-409b-84a6-570db49abda8)
```
정답. 기출로 봤던 문제이고 싱글톤 문제임을 알고 있었다. 처음에 4를 적었다가 함정이 있나하고 다시봐도 4
다른 객체로 하나의 인터페이스에서 처리해도 카운트는 4
```
![image](https://github.com/chihyeonwon/Engineer_Information_Processing/assets/58906858/5a1ab9a2-637b-4240-9301-6ffce3934578)
```
정답. 삼항연산자랑 if -else 문제. if안의 조건이 만족하지 않아서 맨 뒤에꺼 0이 if안에 들어가고 0은 거짓이니까 else문을 실행
else하면 v2는 35 v3는 쉬프트 왼쪽으로 2니까 4배해서 116

35 + 116 은 151
```
![image](https://github.com/chihyeonwon/Engineer_Information_Processing/assets/58906858/993f544f-8b9d-49a7-95cb-adcecf9e8501)
```
정답. 모듈 응집도 강한 것부터 쓰는 문제. 평소에 기순통절시논우로 노래를 만들어서 외웠음
```
![image](https://github.com/chihyeonwon/Engineer_Information_Processing/assets/58906858/d6281afe-0a96-4f61-b97c-17e2eb439212)
```
정답. 문자 ABCDEFGH가 있고 이 문자를 가리키는 포인터를 선언했음. 함수 호출했는데 함수 안에서 swap 하고 있고 앞의 포인터는 ++ 증가 뒤의 포인터는 문자 맨뒤를 가리키는 데 --감소하고 있으니까 얘들이 ABCDEFGH를 뒤집고 있구나라고 생각했음 그리고 마지막에 for문 돌리면서 print하는데 C언어에서 print는파이썬과 다르게 개행문자 안 넣으면 이어서 출력해야되는 것을 알 고 있었고 for문으로 len=글자수8 까지였으니까 HGFEDCBA의 1, 3, 5, 7 번째 문자를 출력하면 GECA
```
![image](https://github.com/chihyeonwon/Engineer_Information_Processing/assets/58906858/d4b16edf-a7cf-4feb-bcce-8e1a0346802d)
```
틀림. ip 주소 3개주고 그 ip랑 같은 네트워크에 있는 거 각각 3개 구하는 문제였음 0이랑 249있었는데
이 두개를 네트워크랑 브로드주소인줄 알고 제외하고 시작했음 -> 결론 틀림 
```
![image](https://github.com/chihyeonwon/Engineer_Information_Processing/assets/58906858/ce7bf50c-7ed9-43e4-98fd-8f0babd7c17d)
```
정답. 제3정규형, 기본키 2개인 표 하나 주고 최대 몇 정규형인지 쓰는 문제였음 부분 함수 종속성이 있나
확인해봤는데 없음 왜냐면 결정자를 나열해봤는데 부분종속없었음 그래서 3정규형을 만족하는지 봤는데 이행종속성이 없었음 3정규형 만족, BCNF를 만족하나 봤는데 기본키2개를 제외한 한 속성이 결정자 역할을 하면서 후보키도 아니였음 그래서 BCNF는 만족하지못하는구나 해서 3정규형했음
```
![image](https://github.com/chihyeonwon/Engineer_Information_Processing/assets/58906858/92864d84-564b-47db-8e25-1f1bad072b58)
```
정답. OSPF 이거는 시험 전에 내부,외부 라우팅 프로토콜 IGP,EGP, IGP에서 RIP, OSPF로 외웠음
다익스트라 알고리즘과 링크상태프로토콜이라는 말보고 바로 OSPF 적음
```
![image](https://github.com/chihyeonwon/Engineer_Information_Processing/assets/58906858/5ee629cf-34bf-48b0-82f9-23b91e98a03d)
```
틀림. 조인 종류 물어보는 문제였는데 동등 조인의 의미는 =로 조인한다고 알고 있어서 가운데는 정답
자연조인하고 세타조인 두개 고민했었는데 세타가 조인 조건에 만족하는 것, 자연이 중복 제외하고 였음
두 개를 바꿔서 적어서 틀림 - 부분점수 1점 획득
```
![image](https://github.com/chihyeonwon/Engineer_Information_Processing/assets/58906858/709244f8-6a66-401c-ba8c-2d3b74c572d3)
```
정답. 페이지 교체 알고리즘인 LRU Least Recently Used랑 LFU Least Frquent used 두 개가 나왔음
운영체제 전공 수업에서 페이지 교체 연습을 쭉 해왔어서 무난하게 풀었는데 다만 답이 똑같아서 실수했나
검토를 5번 이상 진행해버렸음. 어떻게 해도 6, 6이 나와서 그대로 둠
```
![image](https://github.com/chihyeonwon/Engineer_Information_Processing/assets/58906858/98333c5d-60d5-40be-9444-3bc3d1b40878)
```
틀림. 상속 실행 순서로 자식 클래스에서 부모클래스 호출하는거 까지 잘햇는데 print할 때 return 한 값을
출력한다고 해서 마지막 두개를 바꿔서 씀 다시 생각해보니까 애초에 print가 실행되지 않으면 getArea도
호출안되는 거였음 ...
```
![image](https://github.com/chihyeonwon/Engineer_Information_Processing/assets/58906858/b78ab336-ff70-41f7-9c46-2c21b1259dbb)
```
정답. 구조체 나오고 포인터 나왔음 포인터로 구조체를 가리키고 구조체 안에 있는 값들을 함수 3개에 넣어서 값을 이리저리 바꿈. sim_pow였나 이 함수에서 맨 앞에 double 이 있길레 나는 당연히 return이 있겠거니 했는데 return 문이 없어서 당황함 그러면 sim_pow 결과값이 뭘까하다가 이거는 문제 실수거나 예외처리안한 경고문장이뜨고 프로그램은 돌아갈거다라고 생각해서 return 했다 치고 문제 풀었음 근데 1.1을 3번 곱하더니 1331 (숫자가 너무커서 정확히 기억남)하고 2100을 곱하라는 거임 순간 4자리수 곱셈하는 방법을 까먹었는데 정신차려서 곱했음. 출력할때 %.2f 로 출력하라고 되어있었는데 이건 시나공 10장 프로그래밍 문제 중 출력형태를 공부해서 둘째짜리까지 출력해야겠다 하고  2795.10 까지 적음
```
![image](https://github.com/chihyeonwon/Engineer_Information_Processing/assets/58906858/e746cd50-12c0-40fe-9095-0d1ae366966f)
```
틀림. 파이썬 기출문제에서 본 문제인데 처음에는 Seynaau 문자 두 번째꺼로 잘 적었다가 기출문제에서는 맨 앞 대문자만 썼던 게 기억나서 무슨 이유인지는 모르겠는데 답을 앞글자 대문자로 바꿔서 적음- 멍청했음
```
![image](https://github.com/chihyeonwon/Engineer_Information_Processing/assets/58906858/4462f732-2589-4ad1-9678-a4157514dc67)
```
정답. 조건에 맞는 릴레이션을 칸도 그려서 넣으라는 문제였음. 집에 와서 가답안 주어진 표를 보니까 오름차순 되어있었음 그래서 아마 맞을 거임
```
![image](https://github.com/chihyeonwon/Engineer_Information_Processing/assets/58906858/44510653-e6da-4dc6-8971-fc22ab47cc37)
```
정답. 테스트 커버리지 4개하고 경계값 분석, 원인효과 그래프가 보기로 나왔음. 근데 문제에서 말하고 있는 내용은 분명히 커버리지에 관한 문제였음 그래서 경계값 분석, 원인효과 그래프는 보기에서 걸렀음
테스트 커버리지 3개는 문장, 결정, 분기로 정확히 알고 있었는데 MC/DC 이건 뭐지 뒤에는 결정같은데 하고
처음에는 결정 커버리지로 생각하고 있다가 그러면 문제에서 말하고 있는 장점인 자기가 결정해서 테스트 출력의 수를 줄이는 장점?이 말이 맞지가 않음 그래서 MC/DC 커버리지 적었음

시험 끝나고 MC/DC를 인터넷에 검색했는 데 문제에 나왔던 지문이 그대로 나왔음 그래서 이런 커버리지도 있구나라고 생각함
```
![image](https://github.com/chihyeonwon/Engineer_Information_Processing/assets/58906858/5af20d71-6d22-46a9-936d-004907681a02)
```
정답. 무슨 트로이목마하고 해킹 공격자의 공격 루트가 된다에서 보안 용어구나싶었음. 그래서 처음에 Trace route가 보여서 경로를 뚫어서 공격하겠구나 했는데 제일 첫 문제 지문에 프로그램들의 집합이라고 적혀있는 거임. 그래서 내가 아는 집합은 응급구조 키트 키트라는 단어가 생각났음. 보기에 RootKit라고 눈에 띄었음. 그래서 RootKit함
```
![image](https://github.com/chihyeonwon/Engineer_Information_Processing/assets/58906858/d8851af9-d24d-4f97-959c-694ad4e5af23)
```
정답. 이거는 하루전에 무슨 부모생성자로 만들고 자식클래스 생성자로 호출하는 것을 정리했었음
자식 클래스 생성자로 호출하고 super로 실컷 부모클래스 변수들을 초기화한다음 다시 메인함수 왔더니
매개변수 없는 함수 호출하고 있었음. 그래서 그 함수봤는데 부모에도 매개변수 없고 자식에도 매개변수 없음 그러면 어떤 함수를 호출할까? 자식클래스가 부모클래스의 함수를 오버라이딩 재정의(형태가 똑같음)했구나 해서 자식클래스의 함수안의 po*po를 실행하고 리턴값으로 넘겨줬음 po 두개 곱하면 값이 9임
그래서 9함 
```
![image](https://github.com/chihyeonwon/Engineer_Information_Processing/assets/58906858/2d14343e-628e-4cc2-998c-8034a2d5e83a)
```
정답. 또 보안용어 문제 나왔음. 근데 딱 문제 지문보니까 지속적이고 1~4번의 과정을 거칠만큼 공격자가 되게 치밀하고 계획적으로 과정을 밟아가면서 공격하는 게 눈에 보임. 그래서 정보보안 수업에서 들었던 APT 지능적 지속적 공격 이 생각났음 그래서 APT 적음
```
![image](https://github.com/chihyeonwon/Engineer_Information_Processing/assets/58906858/b9ef6dfb-2674-4326-b975-55909803a674)
```
정답. 표 두개인가 주고 조건에 맞는 행의 수를 구하는 문제였음 앞에 두 개 조건을 둘다 만족하는 게 애초에 하나 밖에 없어서 1바로 적음
```
![image](https://github.com/chihyeonwon/Engineer_Information_Processing/assets/58906858/e0a5ab71-fe40-4e67-b4cd-887ac6a4ccd0)
```
정답. 시저암호?라는 알고리즘이였다고 하는데 이거 푸는데 30분이상 쓰고 시험장에서 제일 늦게 나옴. 첨에 It is 8 적어두고 I는 대문자니까 uppear함수에서 나머지 t is 는 lower함수에서 8은 isnum 함수에서 처리해야겠다 생각하고 A가 아스키 문자로 65이라고 어디서 들은게 기억났음 그래서 ABCDEFGHIJKLMNOPQRSTUVWXYZ 까지 연습란에 적고 65 부터 알파벳 끝까지 번호를 쭉 나열했음
I의 위치에서 A의 위치, 즉 문자열 사이의 거리를 뜻하는 거구나 해서 이때부터 아스키 코드가 몇 번인지는 크게 중요하지않겠다라고 느낌. % 26으로 나눈 나머지와 A위치 56을 더해서 나오는 위치들을 적어줬음

마지막에 숫자는 솔직히 잘 몰라서 '0'을 0으로보고 8-0+3 -> 11이고 10으로 나눈 나머지 1에다가 0더하니까 1 나와서 그냥 1적음
```
![image](https://github.com/chihyeonwon/Engineer_Information_Processing/assets/58906858/f9cce987-d591-40cc-abf6-a3775761f921)
```
정답. 디자인 패턴은 시험 전에 생성, 구조, 행위로 나눠진 부분에 있는 디자인 패턴을 거의 다 외움
문제 지문에는 추상화란 단어가 눈에 많이 보였고 그러면 생성에서 abstract factory 랑 factory method밖에 없다해서 abstract factory 적고 나옴 추상팩토리에 관한 문제였음
```
```
예상은 75점인데 실수하거나 정확히 모르는 문제 1문제빼고는 다 맞출 수 있었던 것 같음.
솔직히 시험지 상태 확인하라고 해서 처음 시험지 받아서 넘길 때 프로그래밍 문제가 너무 많은 것 같아서 지레 겁부터 먹었었다.
포기할까 생각했는데 그래도 멘탈 다시잡고 끝까지 남아서 검토했다.
100점 맞았다고 금테둘러서 나오는 것 아니니까 다음 시험 준비해야겠다.
```
## 성취
```
나는 하루도 이 생각을 안 해본 적이 없다
```
## 24.02.15 12:40 필기 합
![image](https://github.com/chihyeonwon/Engineer_Information_Processing/assets/58906858/4d2aa216-b3d1-483d-b26f-360f1a038eb1)

## 24.4.27 실기
실기는 프로그래밍, 데이터베이스 잘하면 합격하는듯
[20년 1회](https://www.youtube.com/watch?v=S7l1qX0WhqE&list=PLniy99c_7ZfpDRzBXv1ryJbW-KnHGp1Az)

## 76점 합예상 실기 시험 문제 & 후기
```
얇고 넓게 공부한게 도움이 되었다
```
## 24년 정처기 학습동아리 "정보처리흑기사"
[1과목 소프트웨어 설계](https://www.youtube.com/watch?v=JhKOsZuMDWs)   
[2과목 소프트웨어 개발](https://www.youtube.com/watch?v=cnjvTZh3_bg)   
[3과목 데이터베이스 구축](https://www.youtube.com/watch?v=KLj1U03HCNI)   
[4과목 프로그래밍 언어 활용](https://www.youtube.com/watch?v=Oxjmb9rAsn8)   
[5과목 정보시스템 구축 관리](https://www.youtube.com/watch?v=LC3TWc_j6n4)   
```
24년 1월 학습동아리 활동하면서 기록 제개
```

[이기적 CBT](https://cbt.youngjin.com/exam/index.php?no=71)

## 2024 정보처리기사 필기, 실기 일정
![image](https://github.com/mr-won/Engineer_Information_Processing/assets/58906858/cb7c9482-ac74-4847-89b5-5e380b141821)       
![image](https://github.com/mr-won/Engineer_Information_Processing/assets/58906858/d05cde24-ace3-401f-889c-0c1a440bab89)     

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

##### 1. 요구 사항 분석 시에 필요한 기술로 가장 거리가 먼 것은?
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

##### 22. 소프트웨어 공학의 기본 원칙이라고 볼 수 없는 것은?
```
기본 원칙 
1. 품질 높은 소프트웨어 상품 개발
2. 지속적인 검증 시행
3. 결과에 대한 명확한 기록 유지
```

## 2020년 09월 26일 (4회)

##### 1. XP(eXtreme Programming)의 기본원리로 볼 수 없는 것은?
```
XP의 기본 원리 

개발자 공동 2명 작업 Pair Programming (PP)
공동 소유 Collective Ownership (CO)
지속적통합 Continuous Integration (CI)
계발계획수립PG, 짧은배포주기 SR, 문장형시스템아키텍쳐 meta, 단순설계 SD
중복제거 Refactoring 등등
```
##### 15. 요구 사항 명세기법에 대한 설명으로 틀린 것은?
```
요구 사항 명세 기법 : 정형 명세기법, 비정형 명세기법

정형 명세기법 : Z, VDM, Petri-Net 모형기반, CSP, CCS, LOTOS(대수적방법) 명세가 간결하고 구현이 일치 하지만 이해도가 낮으며 이해관계자의 작성 부담이 가중

비정형 명세기법 : 상태, 기능, 객체 기능 명세법, FSM, ER모델링, SADT, UseCase: 사용자기반 모델링 명세 작성이 간편하고 의사전달 방법이 다양하지만 모호하고 불충분할 수 있다.
```
##### 16. 소프트웨어 개발 단계에서 요구 분석 과정에 대한 설명으로 거리가 먼 것은?
```
개발 비용이 가장 많이 드는 단계는 유지보수 단계입니다.
```
##### 17. 애자일 방법론에 해당하지 않는 것은?
```
애자일 방법론에 해당하는 것들 : XP, 스크럼(scrum), 크리스털패밀리, 기능 중심 개발(FDD, Feature-Driven Development)
```
![image](https://github.com/chihyeonWON/Engineer_Information_Processing/assets/58906858/bae3296f-778d-455d-a11c-6eea4a402b1a)
![image](https://github.com/chihyeonWON/Engineer_Information_Processing/assets/58906858/f09bab42-9f57-46a0-a06c-62ef66f56fbe)
![image](https://github.com/chihyeonWON/Engineer_Information_Processing/assets/58906858/709f3c9b-2ec5-46d0-9db8-c5688de63a19)

## 2과목 소프트웨어 개발 오답노트
![image](https://github.com/mr-won/Engineer_Information_Processing/assets/58906858/47dc1162-9c71-4dd7-b6a1-ae60e9cddfbc)
![image](https://github.com/mr-won/Engineer_Information_Processing/assets/58906858/103f5e3f-1c4f-416f-a207-7c836cfaa6ff)
![image](https://github.com/mr-won/Engineer_Information_Processing/assets/58906858/ff5fcf4d-dd85-4bcd-90b1-e92cacff547d)

![image](https://github.com/mr-won/Engineer_Information_Processing/assets/58906858/b8b14dfe-cb6c-4423-8330-2d2c023aea5d)
![image](https://github.com/mr-won/Engineer_Information_Processing/assets/58906858/bb778420-4e09-4426-a864-9b9cc276d495)
![image](https://github.com/mr-won/Engineer_Information_Processing/assets/58906858/7af998d6-a6d0-4fad-8238-5cd937f66a87)

![image](https://github.com/mr-won/Engineer_Information_Processing/assets/58906858/aeda468d-baea-4d0a-9c8e-b636cb356077)
![image](https://github.com/mr-won/Engineer_Information_Processing/assets/58906858/065e0099-d310-4f2d-a6eb-0aef630493fd)

![image](https://github.com/mr-won/Engineer_Information_Processing/assets/58906858/3d65206a-6412-4ef3-bdf9-025fcfa2adb4)
![image](https://github.com/mr-won/Engineer_Information_Processing/assets/58906858/68dce5a4-c84d-42fa-94e2-9a24e878d48b)
![image](https://github.com/mr-won/Engineer_Information_Processing/assets/58906858/204bf680-63df-4827-88f8-6dd545d5bc83)
![image](https://github.com/mr-won/Engineer_Information_Processing/assets/58906858/4bf4af70-9013-4093-b51c-9bd08c032c38)

![image](https://github.com/mr-won/Engineer_Information_Processing/assets/58906858/cdb87b61-1463-4a6b-8e58-be92bf0cc7ab)
![image](https://github.com/mr-won/Engineer_Information_Processing/assets/58906858/d52fcb83-e5a0-46e2-8fd3-043c84faaf14)

![image](https://github.com/mr-won/Engineer_Information_Processing/assets/58906858/8725dd2b-cde8-4d50-92a3-c58cc64effcd)
![image](https://github.com/mr-won/Engineer_Information_Processing/assets/58906858/d40ab0a0-d69f-4eba-ab58-82868f47d8b7)
![image](https://github.com/mr-won/Engineer_Information_Processing/assets/58906858/6be75ac1-6302-4d65-b723-cde18cf6149f)
![image](https://github.com/mr-won/Engineer_Information_Processing/assets/58906858/732e8a64-2185-441f-88fe-351f2931fa0f)
![image](https://github.com/mr-won/Engineer_Information_Processing/assets/58906858/22491fb5-640f-4481-a36a-e6be8679ad6b)
![image](https://github.com/mr-won/Engineer_Information_Processing/assets/58906858/6b3e9bf9-0f1a-4a19-a1a9-8c4adbd4c0f0)
![image](https://github.com/mr-won/Engineer_Information_Processing/assets/58906858/0e269d67-d36f-4f15-8925-6ccca854e268)

![image](https://github.com/mr-won/Engineer_Information_Processing/assets/58906858/b50be756-f6ff-4c2c-9d59-b85634386fe7)
![image](https://github.com/mr-won/Engineer_Information_Processing/assets/58906858/93404b67-dd6c-482a-8a2c-154bec4838c6)
![image](https://github.com/mr-won/Engineer_Information_Processing/assets/58906858/f2af832b-0098-468d-871c-9bcd596322a7)

## 3과목
![image](https://github.com/mr-won/Engineer_Information_Processing/assets/58906858/ec465886-4073-4a34-81ef-87c8dd6c56cb)
![image](https://github.com/mr-won/Engineer_Information_Processing/assets/58906858/50ddf3c7-c61f-439a-b17e-4589deb8cf11)
![image](https://github.com/mr-won/Engineer_Information_Processing/assets/58906858/8d2eb103-e84c-4824-939a-5b19577b182d)
![image](https://github.com/mr-won/Engineer_Information_Processing/assets/58906858/27566765-546c-4ed1-8602-4267cc1ae9c9)
![image](https://github.com/mr-won/Engineer_Information_Processing/assets/58906858/6ba56c45-9038-43d0-ab9e-e80c2c0bd112)
![image](https://github.com/mr-won/Engineer_Information_Processing/assets/58906858/04d0caa7-ad48-42cf-944e-653ea4d984e0)
![image](https://github.com/mr-won/Engineer_Information_Processing/assets/58906858/fff626db-45b6-4a27-a971-d2c54a775d68)
![image](https://github.com/mr-won/Engineer_Information_Processing/assets/58906858/49bd5592-c402-40c7-9bbc-0c08a3d62e2f)
![image](https://github.com/mr-won/Engineer_Information_Processing/assets/58906858/8452ff4b-bbff-4545-bbd0-c47554e34840)
![image](https://github.com/mr-won/Engineer_Information_Processing/assets/58906858/b193adad-395d-41c4-9bb6-39334a87f0c7)
![image](https://github.com/mr-won/Engineer_Information_Processing/assets/58906858/9363d613-3501-451a-aba7-aa29c43f1a51)
![image](https://github.com/mr-won/Engineer_Information_Processing/assets/58906858/8343326c-3746-4f5e-94a9-7eb512ec1ac4)
![image](https://github.com/mr-won/Engineer_Information_Processing/assets/58906858/94865ce2-0ed7-422c-b129-d16fc75eb494)
![image](https://github.com/mr-won/Engineer_Information_Processing/assets/58906858/51746449-b45b-4620-9a47-22cc10d00da4)
![image](https://github.com/mr-won/Engineer_Information_Processing/assets/58906858/611afcc7-028e-4bd6-929f-3de2f451654c)
![image](https://github.com/mr-won/Engineer_Information_Processing/assets/58906858/07549694-2318-4ed5-81d1-b2d98093790a)

## 4과목
![image](https://github.com/mr-won/Engineer_Information_Processing/assets/58906858/fc10826e-b3aa-4927-96d8-eadf2ac753a8)
![image](https://github.com/mr-won/Engineer_Information_Processing/assets/58906858/0c426469-8604-4dfd-8690-f1f79342e4d8)
![image](https://github.com/mr-won/Engineer_Information_Processing/assets/58906858/3dabe7fa-d583-4422-badb-8c4f4e6e1b3e)
![image](https://github.com/mr-won/Engineer_Information_Processing/assets/58906858/d0e7b20e-bb0a-43ef-8602-2d8daae98d71)
![image](https://github.com/mr-won/Engineer_Information_Processing/assets/58906858/cc82d76c-3a8e-4a3a-9fa2-bd92f5dc767d)
![image](https://github.com/mr-won/Engineer_Information_Processing/assets/58906858/53b59750-81f2-4c0a-a181-50b8e17cf4c6)
![image](https://github.com/mr-won/Engineer_Information_Processing/assets/58906858/878f6969-ec4d-4cc6-a34f-e1b54c6faa15)
![image](https://github.com/mr-won/Engineer_Information_Processing/assets/58906858/39ee9a39-5ac1-45aa-8b43-1a28f5bc1073)
![image](https://github.com/mr-won/Engineer_Information_Processing/assets/58906858/71c363da-7d42-4140-9b09-fb2bfd661cc9)
![image](https://github.com/mr-won/Engineer_Information_Processing/assets/58906858/afdb8fda-54cb-4a5c-8d65-cde224786315)
![image](https://github.com/mr-won/Engineer_Information_Processing/assets/58906858/69172ba7-de92-48a5-854a-c0bb466b22d4)
![image](https://github.com/mr-won/Engineer_Information_Processing/assets/58906858/355e4551-54e1-4155-ba55-d3e3940053df)
![image](https://github.com/mr-won/Engineer_Information_Processing/assets/58906858/2ee787ac-cd93-41f9-9549-8c06eca99f37)

![image](https://github.com/mr-won/Engineer_Information_Processing/assets/58906858/cecc6a5a-d201-4892-9fbc-015cbd3743cc)
![image](https://github.com/mr-won/Engineer_Information_Processing/assets/58906858/bc51394e-a7ab-403f-ba45-6963b92126fb)
![image](https://github.com/mr-won/Engineer_Information_Processing/assets/58906858/c878ea9c-4e17-41ee-b5f5-3230f2ed9b3a)
![image](https://github.com/mr-won/Engineer_Information_Processing/assets/58906858/346d75da-aaa3-4cb2-895d-4cf8b80537e8)

![image](https://github.com/mr-won/Engineer_Information_Processing/assets/58906858/bf28f766-bc92-4934-a06c-632bb09a2607)
![image](https://github.com/mr-won/Engineer_Information_Processing/assets/58906858/da174712-6595-4a47-a163-fe9f3b649cda)
![image](https://github.com/mr-won/Engineer_Information_Processing/assets/58906858/386b86a3-eb20-4f3c-bdd1-45e4a206cd8d)

![image](https://github.com/mr-won/Engineer_Information_Processing/assets/58906858/7f5106bb-3326-43b3-92f4-2e761ed20891)
![image](https://github.com/mr-won/Engineer_Information_Processing/assets/58906858/68324d75-5afe-4e88-bd8d-1d85ca0695c6)
![image](https://github.com/mr-won/Engineer_Information_Processing/assets/58906858/6919c991-f8ce-4e1e-b48f-f112222350c7)
![image](https://github.com/mr-won/Engineer_Information_Processing/assets/58906858/3e6b2008-b337-407c-81ae-f35ce6a330cf)
![image](https://github.com/mr-won/Engineer_Information_Processing/assets/58906858/59d48454-e352-4b4b-b4c9-2189ddf5aba9)
![image](https://github.com/mr-won/Engineer_Information_Processing/assets/58906858/8e3518dc-fe06-4dd0-905f-0ab4118d4059)

![image](https://github.com/mr-won/Engineer_Information_Processing/assets/58906858/9838ddf5-2be1-4f0d-9613-70e9a1c56afc)
![image](https://github.com/mr-won/Engineer_Information_Processing/assets/58906858/f53b7904-c0d7-494d-8de2-1422a01e2322)
![image](https://github.com/mr-won/Engineer_Information_Processing/assets/58906858/cd092466-a486-465b-8107-9ea05c5b9a03)
![image](https://github.com/mr-won/Engineer_Information_Processing/assets/58906858/859bbd49-3be0-4d24-8e30-c844da5d4487)
![image](https://github.com/mr-won/Engineer_Information_Processing/assets/58906858/629ea6da-bb33-4f00-88a9-e55545041a07)

## 5과목

![image](https://github.com/wonchihyeon/Engineer_Information_Processing/assets/58906858/cf7ae6c5-8e89-41aa-8fa6-72b49a97e4ad)
![image](https://github.com/wonchihyeon/Engineer_Information_Processing/assets/58906858/28a03688-85bb-49d6-be3c-60e92054cccc)
![image](https://github.com/wonchihyeon/Engineer_Information_Processing/assets/58906858/92013f9b-4972-4730-832b-3ca401ed337e)
![image](https://github.com/wonchihyeon/Engineer_Information_Processing/assets/58906858/f9ccf63b-62d3-42e0-8724-a1a929ec16db)
![image](https://github.com/wonchihyeon/Engineer_Information_Processing/assets/58906858/d8ae6ea4-1301-4e3f-8c3f-ca4d85bc5588)
![image](https://github.com/wonchihyeon/Engineer_Information_Processing/assets/58906858/a53fdf65-49f6-440f-8260-1cc8fc9a2123)
![image](https://github.com/wonchihyeon/Engineer_Information_Processing/assets/58906858/572a6156-7a28-4510-bc51-b5dac4abb2ca)
![image](https://github.com/wonchihyeon/Engineer_Information_Processing/assets/58906858/ddcd960f-d12a-484d-a7e5-85fe1ebb9884)
![image](https://github.com/wonchihyeon/Engineer_Information_Processing/assets/58906858/c932e032-5e45-49ba-938e-7e3f9fc11f67)
![image](https://github.com/wonchihyeon/Engineer_Information_Processing/assets/58906858/4e36baab-e578-41f7-b94e-733bd4e01cba)
![image](https://github.com/wonchihyeon/Engineer_Information_Processing/assets/58906858/1bccaa39-f431-4ce9-9f06-1c5ca10cf196)
![image](https://github.com/wonchihyeon/Engineer_Information_Processing/assets/58906858/1e06ceba-aa4e-4bea-9342-e697d37fc243)
![image](https://github.com/wonchihyeon/Engineer_Information_Processing/assets/58906858/bc318073-d796-405b-81a7-bb009e2e40a7)
![image](https://github.com/wonchihyeon/Engineer_Information_Processing/assets/58906858/139d91e1-7293-4a74-a0c1-b4bb50f6e83b)
![image](https://github.com/wonchihyeon/Engineer_Information_Processing/assets/58906858/07b141a3-868e-4c88-89e2-6d1bd43170c3)
![image](https://github.com/wonchihyeon/Engineer_Information_Processing/assets/58906858/68e85cee-6b37-4622-a4ea-338369a384a5)
![image](https://github.com/wonchihyeon/Engineer_Information_Processing/assets/58906858/fd5c2b9a-a98b-4d41-9fa0-b0d4626b0ced)
![image](https://github.com/wonchihyeon/Engineer_Information_Processing/assets/58906858/c08df15c-1e12-41c0-a2cd-6ceb3ad866b5)
![image](https://github.com/wonchihyeon/Engineer_Information_Processing/assets/58906858/d207ae6a-563f-4a15-9865-88377065e249)
![image](https://github.com/wonchihyeon/Engineer_Information_Processing/assets/58906858/ba6cc990-039c-415d-95b4-0061b5e81f29)
![image](https://github.com/wonchihyeon/Engineer_Information_Processing/assets/58906858/2203aa4b-9b2b-49d7-b333-f9420f0cd816)
![image](https://github.com/wonchihyeon/Engineer_Information_Processing/assets/58906858/203276b1-09ca-4df2-80ab-19025fce3df0)
![image](https://github.com/wonchihyeon/Engineer_Information_Processing/assets/58906858/ea4de7b0-650f-4a14-9e8b-01b6d701e1aa)
![image](https://github.com/wonchihyeon/Engineer_Information_Processing/assets/58906858/e10a5887-c64e-4a8e-8d41-2bb7d3073fd9)
![image](https://github.com/wonchihyeon/Engineer_Information_Processing/assets/58906858/ce55ea3c-f7f7-498e-8a1e-38774102b5ed)
![image](https://github.com/wonchihyeon/Engineer_Information_Processing/assets/58906858/8f169690-9768-4e10-a319-cff73f2efb5c)
![image](https://github.com/wonchihyeon/Engineer_Information_Processing/assets/58906858/6cc441d3-3bf3-4079-9d22-29adffcee099)
![image](https://github.com/wonchihyeon/Engineer_Information_Processing/assets/58906858/d932864e-de7c-499e-b64b-5af9e33d9b66)
![image](https://github.com/wonchihyeon/Engineer_Information_Processing/assets/58906858/254db186-1cc3-45d0-afc3-fce80688cd0e)
![image](https://github.com/wonchihyeon/Engineer_Information_Processing/assets/58906858/9870ae30-fce9-441e-bb00-172fe6b1cfcd)
## 실기 기출 정리 

## 2023년 1회 기출 60점 (3.1)
```
Java에서 println : 출력 결과를 다음 행에 출력한다.
C에서 %s 는 문자열을 %c는 한 문자를 출력한다.
가상 회선 방식 : 연결형 통신에서 주로 사용되는 방식으로, 출발지와 목적지의 경로를 미리 연결하여 논리적으로 고정한 후 통신하는 방식
데이터 그램 : 비연결형 통신에서 주로 사용되는 방식으로, 사전에 접속 절차를 수행하지 않고 헤더에 출발지에서 목적지까지의 경로 지정을
위한 충분한 정보를 붙여서 개별적으로 전달하는 방식
L2TP : 데이터링크 계층의 프로토콜 중 하나로, 터널링 프로토콜인 PPTP와 VPN의 구현에 사용하는 L2F의 기술적 장점들을 결합하여 만든
프로토콜이다. 자체적으로 암호화 및 인증 기능을 제공하지 않아 다른 보안 프로토콜과 함께 사용한다.
SSH (22번 포트) : 데이터 암호화와 강력한 인증 방법으로 보안성이 낮은 네트워크에서도 안전하게 통신할 수 있다.
Proxy : 복잡한 시스템을 개발하기 쉽도록 클래스나 객체들을 조합하는 패턴에 속하며, 대리자라는 이름으로도 불린다. 내부에서는 객체 간의
복잡한 관계를 단순하게 정리해 주고, 외부에서는 객체의 세부적인 내용을 숨기는 역할을 한다.
Java에서 부모를 상속한 자식 클래스에서 생성자를 호출하면 Super()를 암묵적으로 호출하여 부모의 생성자를 호출하게 된다.
```
## 2022년 3회 기출 60점 (3.2)
[1번 ~ 12번](https://www.youtube.com/watch?v=obYRnoYAouk)
[13번 ~ 20번](https://www.youtube.com/watch?v=1CW6fdw8OwI)
```
배열 분석 해설 
관계대수 기호, 합집합, 차집합, 교차곱, 프로젝트, 조인
디자인 패턴, 브릿지 패턴은 구현부에서 추상부를 분리하여, 서로가 독립적으로 확장할 수 있도록 구성한 패턴으로, 기능과 구현을 두 개의 별도
클래스로 구현한다는 특징이 있다.
옵저버 패턴은 한 객체의 상태가 변화하면 객체에 상속된 다른 객체들에게 변화된 상태를 전달하는 패턴으로, 일대다의 의존성을 정의한다.
주로 분산된 시스템 간에 이벤트를 생성, 발행하고 이를 수신해야 할 때 이용한다.
4번 자바 문제 해설
브로드캐스트 IP 주소는 마지막 주소, 네트워크 주소는 앞의 주소
Boundary Value Analysis : 경계값 분석
사회 공학 Social Engineering은 컴퓨터 보안에 있어서, 인간 상호 작용의 깊은 신뢰를 바탕으로 사람들을 속여 정상 보안 절차를 깨뜨리기 위한
비기술적 시스템 칩입 수단을 의미한다.
다크 데이터는 특정 목적을 가지고 데이터를 수집하였으나, 이후 활용되지 않고 저장만 되어있는 대량의 데이터를 의미한다.
미래에 사용될 가능성을 고려하여 저장 공간에서 삭제되지 않고 보관되어 있으나, 이는 저장 공간의 낭비 뿐만 아니라 보안 위험을 초래할 수 있다.
SIEM (Security Information & Event Management) : 다양한 장비에서 발생하는 로그 및 보안 이벤트를 통합하여 관리하는 보안 솔루션으로, 방화멱, IDS,
IPS, 웹 방화벽, VPN 등에서 발생한 로그 및 보안 이벤트를 통합하여 관리함으로써 비용 및 자원을 절약할 수 있는 특징이 있다. 또한 보안 솔루션 간의
상호 연동을 통해 종합적인 보안 관리 체계를 수립할 수 있다.
형상 관리 도구 3가지 : CVS, GIT, SVN
Trustznone은 칩 설계회사인 ARM에서 개발한 기술로, 하나의 프로세서 내에 일반 구역과 보안이 필요한 애플리케이션을 처리하는 보안 구역으로 분할하여 관리하는
하드웨어 기반의 보안 기술이다.
Typosquatting 타이포 스쿼팅은 네티즌들이 사이테으 접근할 때 주소를 잘못 입력하거나 철자를 빠뜨리는 실수를 이용하기 위해 이와 유사한 유명 도메인을
미리 등록하는 것으로 URL 하이재킹이라고도 한다. 유명 사이트들의 도메인을 입력할 때 발생할 수 있는 온갖 도메인이름을 미리 선점해 놓고 이용자가 모르는 사이에
광고 사이트로 이동하게 만든다.
SJF, Shortest Job First는 준비상태 큐에서 기다리고 있는 프로세스들 중에서 실행 시간이 가장 짧은 프로세스에게 먼저 CPU를 할당하는 기법이다.
가장 적은 평균 대기 시간을 제공하는 최적 알고리즘이지만, 실행 시간이 긴 프로세스는 실행 시간이 짧은 프로세스에게 할당 순위가 밀려 무한 연기 상태가 발생될 수 있다.
RR, Round Robin은 시분할 시스템을 위해 고안된 방식으로, 준비상태 큐에 먼저 들어온 프로세스가 먼저 CPU를 할당받지만 각 프로세스는 시간 할당량 동안만 실행한 후
실행이 완료되지 않으면 다음 프로세스에게 cpu를 넘겨주고 준비상태 큐의 가장 뒤로 배치된다. 할당되는 시간이 작을 경우 문맥 교환 및 오버헤드가 자주 발생되어 요청된
작업을 신속히 처리할 수 없다.
SRT, Shortest Remaining Time은 현재 실행중인 프로세스의 남은 시간과 준비상태 큐에 새로 도착한 프로세스의 실행 시간을 비교하여 가장 짧은 실행 시간을 요구하는 프로세스에게
cpu를 할당하는 기법으로, 시분할 시스템에 유용하다. 준비 상태 큐에 있는 각 프로세스의 실행 시간을 추적하여 보유하고 있어야 하므로 오버헤드가 증가한다.

클래스는 UML에 표현되는 사물의 하나로, 객체가 갖는 속성과 동작을 표현한다. 일반적으로 직사각형으로 표현하며, 직사각형 안에는 이름, 속성, 동작을 표기한다.
인터페이스는 클래스와 같은 UML에 표현되는 사물의 하나로 클래스나 컴포넌트의 동작을 모아놓은 것이며, 외부적으로 가시화되는 행동을 표현한다.
```
## 2022년 2회 기출 70점 (3.3)
[1번 ~ 10번](https://www.youtube.com/watch?v=obYRnoYAouk&t=15s)
[10번 ~ 20번](https://www.youtube.com/watch?v=jeCbqu1XfcA)
```
스위스의 라이와 메시는 1990년 PES를 발표하고, 이후 이를 개선한 IPES를 발표하였다. IPES는 128비트의 KEY를 이용하여 64비트 블록을 암호화는 알고리즘이며
현재는 IDEA라고 불린다. IPES->IDEA (S가 A) International Data Encryption Algorithm
SkipJack은 국가 안전 보장국에서 개발한 암호화 알고리즘으로 클리퍼 칩이라는 IC 칩에 내장되어 있다. 80비트의 KEY를 이용하여 64비트 블록을 암호화 주로 전화기와 같은
음성 통신 장비에 삽입되어 음성 데이터를 암호화한다.

128 비트 KEY -> 64비트 블로 암호화 -> IDEA
80 비트 KEY -> 64비트 블록 암호화 -> SkipJack

SOLID 5가지 -> SRP(Single Responsibility Principal), OCP(Open-closed Principal), LSP(리스코프 치환), ISP(인터페이스 분리), DIP(의존관계 역전)

호스트의 수 -> 256 / 새롭게 추가된 비트수 2개 -> 네트워크 개수 ->4개 256을 네트워크 개수인 4개로 나눈다. 64개 192.168.1.0부터 64개씩 들어감 네트워크의 수 4개

Regression 회귀 테스트 : 통합 테스트로 인해 변경된 모듈이나 컴포넌트에 새로운 오류가 있는지 확인하는 테스트, 이미 테스팅된 프로그램의 테스팅을 반복한다.

경로 제어 프로토콜은 크게 자율 시스템 내부의 라우팅에 사용되는 IGP와 자율 시스템 간의 라우팅에 사용되는 EGP로 구분할 수 있다.

ISP는 소규모 동종 자율 시스템에서 효율적인 RIP와 대규모 자유 시스템에서 많이 사용되는 OSPF로 나눌 수 있다. OSPF 는 링크 상태를 실시간으로 반영하여
최단 경로로 라우팅을 지원하는 특징이 있다.

BGP는 EGP의 단점을 보완하여 만들어진 라우팅 프로토콜로, 처음 연결될 때는 전체 라우팅 테이블을 교환하고, 이후에는 변화된 정보만을 교환한다.

내부 IGP는 두 개로 나뉨 소규모 RIP, 대규모 OSPF, 자율 시스템 간의 큰 범위에서는 EGP로 EGP에서 향후에 BGP로 변화함

팬인과 팬아웃은 개수를 세는 것에 유의한다. 위에서 아래

```
## 2022년 1회 기출 60점 (3.3)
```
TKIP, 무선랜 보안에 사용된 웹 방식을 보완한 데이터 보안 프로토콜로 임시 키 무결성 프로토콜이라고도 한다. WEP의 취약성을 보완하기 위해 암호 알고리즘의
입력 키 길이를 128비트로 늘리고 패킷당 키 할당, 키 값 재설정 등 키 관리 방식을 개선하였다.

블랙박스 테스트 기법에 해당하는 것 : 경계값 분석 Boundary Value Analysis, 동등분할 Equivalence Partitioning, 원인 효과 그래프 Cause-Effect Graph

ISMS, 정보 자산을 안전하게 보호하기 위한 보호 절차와 대책으로, 정보보호 관리 체계라고 한다. 조직에 맞는 정보보호 정책을 수립하고, 위험에 상시 대응하는
여러 보안 대책을 통합 관리한다. 공공 부문과 민간 기업 부분에서 이것을 평가하고 인증하는 사업을 한국인터넷진흥원에서 운영중이다.

Watering Hall, 목표 조직이 자주 방문하는 웹 사이트를 사전에 감염시켜 목표 조직의 일원이 웹사이트에 방문했을 때 악성 코드에 감염되게 한다.
이후에는 감염된 pc를 기반으로 조직의 중요 시스템에 접근하거나 불능으로 만드는 등의 영향력을 행사하는 웹 기반 공격이다.
Watering Hall -> 특정인 대상, Drive-by Download -> 불특정 대상

V 모델 -> 요구사항 -> 분석 -> 설계 -> 구현 -> 단위 테스트 -> 통합 테스트 -> 시스템 테스트 -> 인수 테스트
```
## 2021년 3회 기출 75점 (3.3)
```
Python -> True ,False 대문자에 유의
파일의 구조는 파일을 구성하는 레코드들이 보조기억장치에 편성되는 방식을 의미하는 것으로, 크게 순차, 색인, 해싱으로 구분한다.
색인 파일 구조는 <값, 구조> 쌍으로 구성되는 데이터 구조를 활용하여 데이터에 접근하는 방식으로, 자기 디스크에서 주로 활용된다.

테스트 조건, 테스트 데이터, 예상 결과

OSI 7 계층 - 데이터링크 계층 : 물리적으로 연결된 두 개의 인접한 개방 시스템들 간에 신뢰성 있고 효율적인 정보 전송을 할 수 있도록 연결 설정, 데이터 전송,
오류 제어 등의 기능을 수행한다.
네트워크 계층 : 개방 시스템들 간의 네트워크 연결을 관리하며, 경로 제어, 패킷 교환, 트래픽 제어 등의 기능을 수행한다.
표현 계층 : 서로 다른 데이터 표현 형태를 갖는 시스템 간의 상호 접속을 위해 필요한 계층으로, 코드 변환, 데이터 암호화, 데이터 압축, 구문 검색 등의 기능을 수행한다.

Cause-Effect Graph : 그래프를 활용하여 입력 데이터 간의 관계와 출력에 영향을 미치는 상황을 체계적으로 분석한 다음 효용성이 높은 테스트 케이스를 선정하여 검사하는 기법

Aggregation(집합) : 하나의 사물이 다른 사물에 포함되어 있는 관계로, 전체와 부분으로 구분되어지며 서로 독립적이다.
Aggregation과 Composition은 둘 다 포함관계이나 Aggregation은 독립적이고 Compostion은 독립적이지 않다.
```
## 2021년 2회 기출 75점 (3.5)
```
Ad Hoc Network 애드 혹 네트워크 : 재난 및 군사 현상과 같이 별도의 고정된 유선망을 구축할 수 없는 장소에서 모바일 호스트만을 이용하여 구성한 네트워크이다.
망을 구성한 후 단기간 사용되는 경우나 유선망을 구성하기 어려운 경우에 적합하다. 멀티 홉 라우팅 기능을 제공한다.

LEFT JOIN ~ ON

python에서 for i in range(1, 3) -> i는 1부터 2까지임 (3-1)

구문(문장) 검증 기준 : 최소 한번은 모든 문장이 수행되도록 구성하는 검증 기준
결정(분기) 검증 기준 : 조건식이 참, 거짓일때 수행되도록 구성하는 검증 기준
조건 검증 기준 : 조건식에 상관없이 개별 조건이 참, 거짓일 때 수행되도록 구성하는 검증 기준

절차적 응집도 : 내부의 요소들이 기능적으로 연관이 없으나, 순차적으로 실행될 때의 응집도
교환적 응집도 : 서로 다른 기능을 수행하지만 동일한 입력과 출력을 사용할 때의 응집도
기능적 응집도 : 하나의 기능에 밀접하게 관련되어 있거나 연관되어 있을 때의 응집도

순차적 응집도 : 모듈의 한 결과값을 다른 모듈이 사용할 때의 응집도

행위 패턴은 클래스나 객체들이 서로 상호작용하는 방법이나 책임 분배 방법을 정의하는 패턴으로 인터프리터, 옵저버, 커맨드 등이 그 예에 해당한다.

럼바우 데이터 모델링
기능 Function : 다수의 프로세스들 간의 자료 흐름을 중심으로 처리 과정을 표현한 모델링
동적 Dynamic : 시간의 흐름에 따른 객체들 간의 제어 흐름, 상호 작용, 동작 순서 등의 동적인 행위를 표현하는 모델링
객체(정보) Information : 시스템에서 요구되는 객체를 찾아내어 속성과 연산 식별 및 객체들 간의 관계를 규정하여 표현하는 모델링

static 을 사용하면 객체 변수 없이 클래스이름.메소드이름 으로 접근하는 것이 가능해진다.

상위 모듈 대체할 수 있는 테스트 드라이버
하위 모듈을 대체할 수 있는 테스트 스텁
```
## 2021년 1회 기출 61.5점 (3.21)
```
RARP : 인터넷 환경에서의 호스트 상호 간 통신에서 연결된 네트워크 접속 장치의 물리적 주소인 MAC 주소를 이용하여 IP 주소를 찾는 인터넷 계층 프로토콜로
역순 주소 결정 프로토콜이라 불린다.

WSDL(Web Service Description Language) : 웹 서비스와 관련된 서식이나 프로토콜 등을 표준적인 방법으로 기술하고 게시하기 위한 언어로, XML로 작성되며 UDDI의
기초가 된다. SOAP, XML 스키마와 결합하여 인터넷에서 웹 서비스를 제공하기 위해 사용되며, 클라이언트는 이것을 통해 서버에서 어떠한 조작이 가능한지를 파악할 수 있다.

Python 코드 출력 서식 : for i in myVar.a: str01 = str01 + i[0] <- 인덱스의 첫글자만 모두 합한다. SKIDDP

경계값 검사 기법은 입력 조건의 중간값보다 경계값에서 오류가 발생될 확률이 높다는 점을 이용한 검사 기법이고, 동치 분할 검사는 입력 조건이 유효한 경우와 그렇지 않은
경우의 입력 자료의 개수를 균등하게 정하는 검사 기법이다. 예를 들어 0 <= x <= 10과 같은 조건이 있을 때, 경계값 분석은 -1, 0 , 10, 11을 입력값으로
동치 분할 검사는 0이상 10이하의 수 n개와 0미만 10초과의 수 n개를 입력값으로 정한다.

단위 테스트 : 코딩 직후 소프트웨어 설계의 최소 단위인 모듈이나 컴포넌트에 초점을 맞춰 수행하는 테스트로, 모듈 테스트라고도 불린다. 사용자의 요구사항을 기반으로 한
기능성 테스트를 최우선으로 인터페이스, 외부적 I.O 자료구조, 독립적 기초 경로, 오류 처리 경로, 경계 조건 등을 검사한다.

통합 테스트 : 모듈들을 결합하여 하나의 시스템으로 완성시키는 과정에서의 테스트를 의미하며, 모듈 간 또는 컴포넌트 간의 인터페이스가 정상적으로 실행되는지 검사한다.

EAI : 기업 내 각종 애플리캐이션 및 플래폼 간의 정보 전달, 연계, 통합 등 상호 연동이 가능하게 해주는 솔루션으로, Point to Point, Hub & Spoke, Message Bus, Hybrid 등의
다양한 방식으로 구축이 가능한 모듈 연계 방법이다.

데이터 모델의 구성요소: 연산, 구조, 제약조건

연산 Operation은 데이터베이스에 저장된 실제 데이터를 처리하는 작업에 대한 명세로서 데이터베이스를 조작하는 기본 도구에 해당한다.
구조 Structure는 논리적으로 표현된 객체 타입들 간의 관계로서 데이터의 구성 및 정적 성질을 표현한다.
제약조건은 데이터베이스에 저장될 수 있는 실제 데이터의 논리적인 제약 조건을 의미한다.

접근 통제 기법 3가지, MAC 강제적 접근 통제 : 등급, DAC 임의적 접근 통제 (신원), RBAC 역할기반 접근통제 (역할, 업무)

임의 접근 통제는 데이터에 접근하는 사용자의 신원에 따라 접근 권한을 부여하여 제어하는 방식으로, 데이터의 소유자가 접근통제 권한을 지정하고 제어한다.
객체를 사용한 사용자가 생성된 객체에 대한 모든 권한을 부여받고, 부여된 권한을 다른 사용자에게 허가할 수도 있다.

내용 결합도는 데이터, 지역 변수등을 직접 참조하거나 수정할 때의 결합도이다.
스탬프 결합도는 배열이나 레코드 등의 자료 구조가 전달될 때의 결합도이다.
공통 결합도 : 파라미터가 아닌 모듈 밖에 선언된 전역 변수를 사용하여 전역 변수를 갱신하는 방식으로 상호작용하는 때의 결합도이다.

세션 하이재킹은 세션을 가로채다라는 의미로 정상적인 여결을 RST 패킷을 통해 종료시킨 후 재연결 시 희생자가 아닌 공격자에게 연결하는 공격 기법이다.
TCP 세션 하이재킹은 TCP 3-Way HandShaking 과정에 끼어듦으로써 서버와 상호 간의 동기화된 시퀀스 번호를 갖고 인가되지 않는 시스템의 기능을 이용하거나
중요한 정보에 접근할 수 있게 된다.
```
## 2020년 4,5회 기출 56.6점 (3.17)
```
UML 다이어그램 종류 : <<import>>가 있고 외부에서 다른 시스템을 import한다.-> 패키지 다이어그램

데이터베이스 회복 기법(즉각갱신기법, 지연갱신기법 둘 중에 하나)
즉각 갱신 기법 Immediate Update는 트랜잭션이 데이터를 변경하면 트랜잭션이 부분 완료되기 전이라도 즉시 실제 DB에 그 내용을 반영하는
기법으로, 장애가 발생하여 회복 작업할 경우를 대비하여 갱신된 내용들을 로그 (Log)에 보관시킨다. 즉각 갱신 기법에서 회복 작업을 수행할 경우
Redo와 Undo 모두 수행이 가능하다.

Python 이중 배열 코드 출력 문제

스니핑에 대한 개념을 간략히 한 문장으로 쓰시오 : 스니핑은 네트워크의 중간에서 남의 패킷 정보를 도청하는 해킹 유형 중 하나로 수동적 공격이다.

변수 n에 저장된 10진수를 2진수로 변환하여 출력하는 자바 코드

Java 2차원 배열 문제 new int[행][열] 첫번째 for(i<3) 0,1,2 행 3개 두번째 for(j<5) 0,1,2,3,4,5 행 5개

C언어 포인터 char* p = "KOREA" 일때 %s,p -> KOREA, %s,p+3 -> EA, %c,*p -> K, %c,*(p+3) -> E, %c,*p +2 -> K에서 2번째 뒷 문자 M 출력

NAT : 우리말로 번역하면 네트워크 주소 변환이라는 의미의 영문 3글자 약자이다.
1개의 정식 IP 주소에 다량의 가상 사설 IP 주소를 할당 및 연결하는 방식이다.
1개의 IP주소를 사용해서 외부에 접속할 수 있는 노드는 어느 시점에서 1개만으로 제한되는 문제가 있으나, 이 때에는 IP 마스커레이드를 이용하면 된다.

샘플링 오라클 Sampling Oracle : 특정한 몇몇 테스트 케이스의 입력 값들에 대해서만 기대하는 결과를 제공하는 오라클로, 전수 테스트가 가능한 경우 사용하고,
경계값 및 구간별 예상값 결과 작성시 사용하는 오라클이다.

동치 분할 검사 : 테스트 기법 중 평가 점수표를 미리 정해 놓은 후 각 영역에 해당하는 입력값들을 넣고, 예상되는 출력값이 나오는지 실제 값과 비교하는
명세 기반 테스트 기법

프로세스 상태 전이도
Ready -> Run -> Wait -> Ready

가용성 : 인가받은 사용자는 데이터베이스 시스템 내의 정보와 자원을 언제라도 사용할 수 있다는 보안 요건이다.
```
## 2020년 3회 기출 62.5점 (3.15)
```
데이터베이스 스키마란 데이터베이스의 구조와 제약 조건에 대한 전반적인 명세를 기술한 것이다.

프로토콜, 심리학자 톰 마릴은 컴퓨터가 메시지를 전달하고, 메시지가 제대로 도착했는지 확인하며, 도착하지 않았을 경우 메시지를 재전송하는
일련의 방법을 기술적 은어를 뜻하는 프로토콜이라는 용어로 정의하였다.

% (Division) : 릴레이션 A, B가 있을 때 릴레이션 B의 조건에 맞는 것들만 릴레이션 A에서 분리하여 프로젝션을 하는 연산이다.

형상 통제란 식별된 형상 항목에 대한 변경 요구를 검토하여 현재의 기준선이 잘 반영될 수 있도록 조정하는 작업을 뜻한다.

헝가리안 표기법 : 변수명 작성 시 변수의 자료형을 알 수 있도록 자료형을 의미하는 문자를 포함하여 작성하는 방법이다.

while(a < 10) { a++ } -> a가 10일 경우도 포함됨 a++, 후치 연산

Point to Point : 가장 기본적인 애플리케이션 통합 방식으로, 애플리케이션을 1:1로 연결한다.
Hub & Spoke : 단일 접점인 허브 시스템을 통해 데이터를 전송하는 중앙 집중형 방식이다. 확장 및 유지 보수가 용이하다. 허브 장애 발생시 전체
시스템에 영향을 미친다.

C++에서 생성자에 대해 간략하게 서술하시오 : 생성자는 객체 변수 생성에 사용되는 메서드로, 객체 변수를 생성하면서 초기화를 수행한다.
```
## 2020년 2회 기출 50점 (3.17)
```
목표 복구 시간 Recovery Time Objective RTO는 비상 상황이 발생한 경우 "비상사태 또는 업무중단 시점부터 업무가 복구되어 다시 정상 가동 될 때까지의
시간을 의미한다.

IPsec, Internet Protocol Security : 네트워크 트래픽에 대해 IP 계층에서 IP 패킷 단위의 데이터 변조 방지 및 은닉 기능을 제공하는 네트워크 계층에서의
보안 통신 규약

정적 테스트, 정적 분석 : 애플리케이션을 실행하지 않고, 소스 코드에 대한 코딩 표준, 코딩 스타일, 코드 복잡도 및 남은 결함을 발견하기 위하여 사용하는
테스트

Observer : 한 객체의 상태가 바뀌면 그 객체에 의존하는 다른 객체들에게 연락이 가서 자동으로 내용이 갱신되는 방식으로, 일대다의 의존성을 정의하는 패턴이다.
상호 작용을 하는 객체 사이에서는 가능하면 느슨하게 결합하는 패턴

student 테이블을 참고하여 name 속성으로 idx_name이라는 인덱스를 생성하는 sql 문을 쓰시오.
create index 인덱스이름 on 테이블이름(속성이름)
create index idx_name on student(name);

SOAP는 HTTP, HTTPS, SMTP 등을 이용하여 xml 기반의 메시지를 네트워크 상에서 교환하는 프로토콜로, SOAP envelope, 헤더, 바디 등이 추가된 xml 문서이다.
SOAP는 복잡하고 무거운 구조로 구성되어 있어 SOAP 보다는 Restful 프로토콜을 이용하기도 한다.

SOAP : 복잡하고 무거운, Restful : 쉽고 가벼운

SQL injection : 웹 응용 프로그램에 SQL 구문을 주입하여 내부 데이터베이스 서버의 데이터를 유출 및 변조하고 관리자 권한을 우회하는 공격 기법이다.

사용자 인터페이스의 4 원칙 UI 설계 원칙 : 직유학유

직관성:누구나 쉽게 이해하고 사용할 수 있어야 한다.
유효성:사용자의 목적을 정확하고 완벽하게 달성해야 한다.
학습성:누구나 쉽게 배우고 익힐 수 있어야 한다.
유연성:사용자의 요구사항을 최대한 수용하고 실수를 최소화해야 한다.

리눅스 또는 유닉스에서 a.txt 파일에 대한 권한
사용자 rwx 권한, 그룹 r,x 권한, 기타 사용자 x 권한

rwx - user, group, other

chmod 751 a.txt 파일이름을 맨 뒤에 쓰는 것을 잊지 말것.

개방형 링크드 데이터 : LOD, Linked Open Data : 웹 상에 존재하는 데이터를 url로 식별하고 각 url에 링크 정보를 부여함으로써 상호 연결된 웹을 지향하는 모델
Linked Data와 Open Data를 결합한 용어 -> Linked Open data

데이터베이스 구축까지의 과정 : 요구 분석 -> 개념적 설계 -> 논리적 설계 -> 물리적 설계 -> 구현

데이터베이스 나오고 과정나오면 개념적, 논리적, 물리적 설계를 기억한다.

소프트웨어 형상 도구 Software Configuration Management 는 소프트웨어 개발 단계의 각 과정에서 만들어지는 프로그램, 프로그램을 설명하는 문서, 데이터 등을 관리하는
것을 말한다. 소프트웨어의 개발 과정에서 만들어지는 여러 버전들의 변경 사항을 관리하는 일련의 활동이며 이를 지원하는 도구로 Git, SVN 등이 있다.
```
## 20년 1회 기출
```
비정규화,반정규화란 ? 성능향상을 위해서 정규화에 위배되는 방법을 채택하는 것

살충제 패러독스 : 똑같은 유형의 테스트만 반복하면 다른 유형의 결함이 왔을 때 결함을 발견할 수 없다.

오류 - 부재의 궤변 : 오류가 없는 프로그램이라 할지라도 사용자의 요구사항과 맞지 않으면 소용없다.

응집도 높히고 결합도는 낮춘다. 결합도 : 모듈과 모듈간의 상호작용 응집도: 모듈 내부의 기능적인 집중 정도

처리량 응답시간, 반환 시간, 자원 사용률

DDOS -> 가용성을 해치는 공격 기법, LAND ATTACK

통신 프로토콜의 3요소 : 구문, 의미, 타이밍 : 구타를 왜하니 의구
SYNTAX, SEMANTIC, TIMING

HRN 공식 -> 대기시간 + 실행시간(서비스시간) / 실행시간(서비스시간)

선점 : SRT, RR, MLQ, MFQ (Shortest Remaining Time, Round Robin)

릴리즈 노트 작성 항목 중 문이름, 제품이름, 버전번호, 참고 날짜 등을 기술-> 헤더 header

데이터 마이닝 : 대규모로 저장된 데이터에서 자동적으로 통계적 규칙이나 패턴을 찾아내는 것

MD5 : MD4를 일방향 해시 함로 개선한 알고리즘, 128 길이의 해시값을 출력하는 알고리즘

비밀키(대칭키) 알고리즘 : DES, AES, ARIA, SEED, IDEA
비대칭키 알고리즘 : RSA, ELGama
해시알고리즘 SHA, MD5, HAS-16

버블 정렬알고리즘 : TEMP써서 앞값하고 비교해서 바꾸는 것

break가 있을 때까지 한다.
```
## 시나공 실기 기출문제 풀이 - 코드 위주
```
c, Java, Python 16진 표기법 숫자 앞에 0 또는 0x
Python 8진 0o(octagon) C, Java 8진 숫자 앞에 0
35(8)인경우 3*8의 1승 + 3*8의 0승 이렇게 계산하여 10진수로 출력한다

~ : not 비트 연산 11001111 인경우 2의보수 = 1의보수 + 1이므로
맨 앞 부호 비트를 제외한 비트를 한 번 더 뒤집고 1을더한다.
10110000 + 1 -> 10110001

^ : xor 비트연산 두개가 같을 경우 0 다를 경우 1
```
## 외우는거 
```
XP: 5가지 의사존중, 피드백, 존중, 용기, 단순성 의사 피존용기에 단아서
스크럼 : 스프린트

SOAP - XML
REST - JSON

WSDL(문서) -> UDDI(도서관)

ui 설계, 유효성, 유연성, 학습성, 직관성

실행여부 -> 동적, 정적
테스트 기법 -> 블랙박스, 화이트박스

create index index이름 테이블이름(속성명 asc or desc)

IPSec 안에는 AH, ESP
AH : 인증 무결성
ESP : 인증 무결성 기밀성

RTO : 목표 복구 시간 
RPO : 9시부터 9시30분까지 손실되었을 때 손실량 Recovery Point Objective

시맨틱 웹 : 시맨틱 태그를 써서 의미있는 태그를 써서 검색이 잘되도록 함
```
[진법, 비트연산](https://www.youtube.com/watch?v=avot35M_ETM)
```
not 연산 -> ~16 양수이면 +1하고 음수기호붙여준다. -17
~-16 음수이면 -1하고 음수기호 때준. 15

11 -> 00001011
~11 -> 11110100 으로 하고 맨앞부호는 부호비트 1 -> 음수 놔두고 나머지를 반대로
2의보수 = 10001011 에서 (1의보수) + 1 = 10001100 -> -12
```
[22](https://www.youtube.com/watch?v=YQ5kIuoHam8)
```
디자인 패턴

구조

생성

행위

선택 정렬 (첫번째꺼랑 전체랑 비교해서 바꾼다)

삽입 정렬 (두번째 첫번째, 세번째에 첫,두번재 이런식)

버블 정렬(바로앞에거랑 바꿈)

로그기반 복구
즉시 갱신 : redo, undo

지연 갱신 : redo

acid 중 a 원자성과 관련 있는 것 : rollback, commit

단위테스트 : 정적, 동적 테스트
통합테스트 : 
시스템테스트 : 기능, 비기능
인수테스트 : 알파(개,사), 베(사용자)


리팩토링 (동료검토, 워크스루, 인스펙션)

스모크 테스트 : 테스트 환경을 테스트

블랙 박스

동등 분할 : 입력값 대상
경계값 분석
원인-효과 그래프

ISMS : 정보보호관리체계 
PIMS : 개인정보에 관련한것  핌스

ISMS-P : 두 개를 합친것 개인정보, 정보보호관리체계

tkip : 임시 키 무결성 프로토콜 temporary key integrity protocol

슈퍼키 : 유일성
후보키 : 유일성 + 최소성 
기본키 : 유일성 + 최소성
대체키 : 유일성 + 최소성

개체 무결성 제약조건 : null이오면안되고 중복 x
참조 무결성 제약조건 : 참조하는 테이블의 데이터값이 있어야 한다.
-> 옵션을 줄수 있음 (restrict <> cascade)
도메인 무결성 제약조건
```
```
insert into 테이블명 (속성1, 속성2) values (1, 'A') 문자는 '' 안에
update 테이블명 set 속성 = 1 where 조건
delete from 테이블명 where 조건
select * from 테이블명  where ~ group by ~ 집계함수 having 조건 order by 속성 asc or desc

c코드 나오면 main() 부터본다.
재귀함수-> 박스로이어서 계산 , 상수값이 나오면 끝
아래서 위까지 써놓고 맨 위가 상수면 그 상수를 밑으로 내리면서 계산

괄호에는 <, > 이게 많이나오고 답이 %, / 을 넣어보고 계산

값을 변수에 넣고 *, /, % 세 개를해서 원하는 출력값이 출력될 것 같은지를 판단해서 푼다.

소수 prime, 나눴는데 ==0 떨어진다 약수 -> 소수 && 약수 -> 소인수분해
-> 답 29
```
```
IPS = IDS(탐지) + 방화벽
샌드박스 응용프로그램이 가상환경에서 독립적으로 운영되는 형태

igp안은 rip, ospf
rip 최대 15홉 거리벡터라우팅
ospf 상태기반

egp 는 bgp

변경 또는 수정된 것에 대해 새로운 결함을 테스트 하는 것 -> 회귀

웹 : http(프로토콜), 하이퍼텍스트(링크), html 마크업언어

solid
한 클래스는 하나의 책임을 진다. srp
개방폐쇄 ocp :확장에는 열려있고 수정에는 닫혀있다.
리스코프 lsp: 자식클래스는 부모클래스를 대신할 수 있어야 한다. 상속
isp 인터페이스 분리 자신이 사용하는 것 외에는 생성 x
의존성 역전의 법칙 : 변화가 많은 것 보다 의존관계에 있는 것은 변화가 없는 것에 의존해야한다.

사용가능한 네트워크의 주소

맨앞은 네트워크 주소, 맨뒤는 브로드캐스트주소로 사용되기 때문에
서브넷마스크 192라면 11000000에서 6비트 2의 6승 -2가 답
```
```
동료검토 : 작성자들끼리 회의하는 것
워크스루 : 회의전에 이해관계자들에게 간략하게 설명하는 것
인스펙션 : 작성자 제외하고 전문가들끼리 오류
```
```
형상식별 - 형상통제 - 형상감사 - 형상기록

식통감기

Memento 디자인패턴중 되돌리기할때 메멘토

브릿지 : 구현부에서 추상층을 분리
옵저버 : 상태를 전달, 감시

UML : 사물 , 관계, 다이어그램

연관, 의존(짧은 연관), 일반화, 실체화, 집합(독립), 포함(독립X 긴말한 관계)
실체화 : 인터페이스에서 추상 메서드를 구현한 것

유스케이스 다이어그램 : 포함관계 include 반드시 실행되어야 하는 관계, 확장관계 extend 선택적인것

블랙박스 : 경계값분석, 동등 분할, 원인효과 그래프, 오류예측, 비교검사
```
```
선점형 : SRT, RoundRobin, MFQ 다단계큐, 다단계 피드백 큐 -> 기아현상 -> 에이징 -> MFQ
비선점형 : SJF, FCFS, HRN(대기+실행/실행) -> 기아현상 -> 에이징 -> HRN

DLP 데이터 유출 방지 : 컴퓨터에서 USB로 데이터유출을 막는다.

SOAR : 자동화나오면 SOAR

SIEM : 빅데이터, 인덱싱 기반
 
FDS : Fraud Detection System 전자 금융 이상 거래 탐지
```
```
Trust Zone : 독립적인 보안 구역을 두어 중요한 정보를 보호하는 하드웨어 보안 기술

일반집합 : 카티전프로젝트, 합집합, 차집합

sql 마지막에는 세미콜론

속성명은 ,로 구문 where에는 and와 or로 구분

printf("%d", 배열) 이라고하면 배열 안의 요소를 콤마없이 이어서 출력한다.

완전수 문제 -> 30까지는 2개있다. 뭔가 값을 2로나누고 for 돌린다.-> 답이 2

for하는데 숫자가 크다? 뒤에서부터 돌린다

출력결과에 집중
```
```
서브쿼리 쿼리가 두개나왔으면 서브쿼리부터 읽고 부등호가 있다.
서브쿼리 다중행 연산자를 떠올린다.
any, all 이 있다. any는 or와 같고 all은 and와 같다. 두 쿼리의 조건이 둘다 all 하나만 any

집계함수(속성) 속성값 중 null 포함x
```
```
4+1 뷰 = 논리, 구현, 배치, 프로세스, 유스케이스뷰

uml 특징 : 가시화, 명세화, 문서화, 구축 언어

UI 유형 : UI 앞에 뭐가 붙냐가 다르다. CLI
VUI, NUI, OUI,

UI 설계 도구
와이어프레임 : 개발자와 디자이너와 함께 그림 그리는거
스토리보드 : 화면에 대해 기획자가 개발자 등들에게 주는거
프로토타입
목업 : 정적인 모형
유스케이스

유연성, 유효성, 직관성, 학습성 ui

식통감시

CCB 형상 통제 위원회 Configuration control committee
위원회 하나 알아두자
형상 통제 : 변경사항에 대해서 검토하고 베이스라인에 반영

버전관리 : add, commit, update, merge, diff

페르소나. 잠재적 사용자의 목적와 패턴을 응집시킨 가상의 사용자

ant 자바, maven, jekins자바, gradle, make(유닉스)

프레임워크 : 개발에 필요한 구성요소와 아키텍처를 제공하는 반제품 소프트웨어
스프링, 전자정부 : 모듈화, 재사용성, 확장성, 제어의 역흐름

라이브러리 : 개발에 필요한 리소스(함수, 템플릿)등을 모아둔 것

API : 다른 소프트웨어와 상호작용하는데 사용되는 인터페이스

내공외제스자 소스코드로 나올 수 있음 결합도
내용 : 다른 모듈 기능
공통 : 전역변수
외부 : 다른 모듈 변수 extern
제어 :제어요소
스탬프 : 구조
자료 : 변수 

기능적
순차적 -> 출력값을 입력값으로 사용하는것
절차적 -> 순차적으로 처리
통신적(교환적) 동일한 입력 동일한 출력
시간적
논리적
우연적

팬인 팬아웃 -> 숫자
차수 -> 나가는것에서 제일 많은거

MVC 모델 뷰 컨트롤러 패턴 : 데이터, 화면, 이벤트같은 처리를 나눠서 개발
퍼시스턴스 계층 : 데이터 관리
도메인 모델 계층 : 데이터를 담아서 전달

OWASP : 오픈소스 웹 애플리케이션 보안 프로젝트 오왑스프
opensource web application secure project

시큐어 코딩 Secure coding
보안관련 가이드를 준다.
입력데이터 검증

배치프로그램 : 프로그램을 모아서 일괄로 처리하는 작업이다.
필수 요소 : 대용량데이터, 자동화,견고함,안전성, 성능

인터페이스 : 정보 (데이터)를 서로 주고 받는 프로그램
송신, 수신, 중계 시스템

중계가 있으면 데이터의 안정성,유효성을 보장하기 위해서(로그를 둔다)

공통부 : 어디로 보내고 들어오는지에 대한정보
개별부 : 개별 데이터
종료부 : 언제프로그램이 종료된느가

EAI : 기업 내의 애플리케이션을  통합하는 솔루션
포인트 투 포인트
허브 앤 스포크
메시지 버스 ( ESB 방식)
하이브리드

전송 데이터
XML : 구조화된 데이터
Json : 이름과 값 쌍 
YAML : 데이터 직렬화 언어
csv : 콤마로 구분

AJAX : 비동기 방식으로 페이지의 일부만 변경이 가능한 특징

SOAP : HTTP,SMTP등을 이용한 메시지 교환
SOAP : 메시지 교환 프로토콜
UDDI : 비즈니스 업체 목록
WSDL : 서비스의 기술 사항 등록

REST

자원: URI를 통해 자원의 위치 식별 
행위: get, post, put 수정 delete 삭제 등 동작 표현
표현 : 데이터 표현

restful : rest를 따르는 시스템 

패킷 공격 유형 : 스니핑(지켜보는것), 스푸핑(속이는 공격)

보안 적용

네트워크 : IPSec, SSL, S-HTTP
애플리케이션 영역: Secure coding


메서드와 메시지 차이

메서드 : 작업을 수행하기 위한 명령어의 집합
메시지 : 객체들에게 어떤 행동을 하도록 지시

정보은닉 : 내부 데이터에 직접 접근할 수 없도록 제한
캡슐화 : 속성과 메서드를 한 곳에 묶은 것
추상화 : 실체에 대해 핵심적인 개념만 추출
다형성 : 하나의 메시지에 대해 여러가지로 응답

오버로딩: 메서드 이름은 같은데 인자 매개변수가 다른것
오버라이딩: 상속할 때 덮어쓰는거 자식에서 덮어씀

리스코프 치환 : 자식은 부모를 대체
의존석 역전 :변화에없는거
인터페이스 분리: 안쓰는 거 구현X

디자인 패턴 : 재사용할 수 있는 패턴들의 모음

생성 : 객체 생성
구조 : 객체 조합해서 더 큰거 생성
행위 : 알고리즘 책임분배에 관한것

기신사효유이 : 기능성, 신뢰성,사용성,효율성,유지보수성, 이식성

파이썬 [start : end] start오프셋부터 end-1 오프셋(인덱스)까지
[2:5] 면 2부터 4까지
list a [5,3,2,3,1] 의 [2:4] = [2,3]

print(numbers[::2])    # [1, 3, 5] 2 간격으로 띄워서 출력

테스트 오라클 : 테스트의 결과가 참인지 거짓인지 알아내려고 미리 정의된 참값을
입력해보는 것

참샘휴일
참오라클 
샘플링오라클 : 샘플 빼서 오라클
휴리스틱 : 샘플링하고 나머지 것들을 추정
일관성 검사 오라클 : 다른 곳에서는 어떤 결과가 나오는 지 판단

단통시인 테스트

v 모델 : 요구사항 분석, 아키텍처 설계, 모듈 설계, 구현(분석, 아키,모듈,구현)
단위 - 동적,정적
통합 - 블,화
시스템 - 기능, 비기능
인수 - 알파, 베타

화이트 - 문장, 분기, 경로, 조건 검증

경계값 분석 0~10 이면 -1, 0, 1, 9, 10 ,11 을 입력 테스트

비교검사 - 병행테스트랑 비교 : 기존과 변경시스템을 비교해보는 거 똑같이 나오는지 검사
오류 예측

A/B 테스트 기존테스트 대비해서 테스트
스모크 테스트 : 테스트 환경에 대한 테스트

테스트 커버리지: 테스트가 얼마나 수행했는 지 측정하는 기준

기능기반 : 
라인 : 라인 수 
코드 :

구문
조건 IF(x > 0 && y<0) 이면 x>0 개별 t,f
결정 IF(x > 0 && y<0) 이면 IF 전체가 t,f

테스트 스크립트 : 자동화 테스트에 필요한 스크립트 설명서

상향식 - 위로가면서 테스트하는데 위에께 구현안되있으면 테스트 드라이버(임시모듈)
하향식 - 밑으로가면서 테스트하는데 밑에께 구현안되어있으면 테스트 스텁(임시 모듈)

동료 검토 : 짝프로그래밍 xp
워크스루 : 진행자 개발자인데 발표하는거 듣는 사람이 개선
인스펙션 : 공식검토회의 기능 회의 <> FTR (전반적인 것)

리팩토링 : 기능의 변경없이 내부 코드 개선
```
```
파일 디스크립터 : 유닉스 시스템이 파일에 접근할 때 직접 사용

부팅블록 : 시스템 부팅에 관한 정보
슈퍼블록 : 전체 파일에 대한 정보
i-node 블록 :파일 디렉터리 정보 위치
데이터블록 : 실제 데이터

nur : 참조비트, 변형비트를 이용

단편화 : 내부 단편화:빈 공간의 크기
통합
압축
재배치 : 압축 시 멀리있어서 재배치

가상 기억장치: 보조기억장치의 일부를 주기억처럼 사용하는 것

페이징분할 고정 -> 내부 단편화 발생
세그먼테이션 가변 -> 외부 단편화 발생

코드 영역 : 코드 
데이터 영역 : 전역, 정적변수
힙 : 동적변수
스택 함수의 매개변수, 지역변수

IPC : 프로세스들이 서로 데이터를 주고 받거나 상태를 조정하기 위해 사용하는 인터페이스

ready->run 디스패치
run -> ready 타임 런 아웃

디스패치하고 타임 런 아웃 번갈아가면서 함
run -> wait -> 블록
wait-> ready -> 웨이크업

PCB : 문맥교환이 일어날 수 있도록 프로세스의 상태나 정보등을 저장
문맥교환 : 하나의 프로세스가 CPU 사용을 마치면 다른프로세스가 CPU를 사용할 수 있도록 하는 것

프로세스 스케줄링 : 어느 프로세스를 먼저 처리할지 결정하는 행위

선점형: SRT, ROUND ROBIN, 다단계 큐, 다단계 피드백 큐
비선점형 : SJF, 시한부, 우선순위, HRN, FCFS

선점형 : 프로세스가 강제로 뺏을 수 있는 것
비선점형: 못 뺏는 거

기아현상 : 우선순위가 낮은 프로세스가 할당받지 못하는 현상
에이징 : 기아현상을 해결하기 위한 방법

병행 프로세스 : 두 개 이상의 프로세스가 동시에 실행되는 것
하나의 자원을 두 개 이상의 프로세스가 실행되면 안되는 것
임계구역에 하나만 들어갈 수 있게 하는 것 <- 상호배제 

동기화 기법 -> 세마포, 모니터

교착 상태 : 서로 프로세스가 자원을 점유하면서 다른 프로세스의 자원을 요구하면서
무한정 기다리고 있는 상황

교착상태 발생 조건
상호배제 
환형대기
점유및대기
비선점 

교착상태 해소 방법

예방 발견,회복, 회피 (은행가 알고리즘) avoidance

디스크 스케줄링:하드디스크의 정보에 접근하기 위해 하드디스크 헤드의 움직임을 최소화
FCFS : 먼저들어온 것을 처리
SSTF 정렬해서 푸는것 작은 곳먼저
SCAN 끝까지 처리 엘리베이터
LOOK SCAN을 개선 -> 끝까지 가지않고 틀어버리는것

스토리지 저장소
DAS : Direct Attached storage : usb같은거
NAS : nework Attached storage 네트워크로 연결
SAN : Storage area network 광채널 네트워크 

raid 0 : 스트라이핑 : 2T + 2T => 4T
raid 1 : 미러링 2T = 2T 복사해놓는 것 가용량은 0보다 작을 수 있다. 
raid 2 : 해밍코드
raid 3 : 패리티 코드 
raid 4 : 3번과 유사하나 블록단위 
raid 5 : 각각에 패리티
raid 6 : 두개 디스크에 패리티 

네트워크 토플리지
계층형, 링형(두개의 인접노드순환), 망형(막 엉켜서 연결), 버스형, 성형(중앙과 연결) 

단반향 : 한쪽방향으로만 데이터 전송 TV
전이중 : 전화기 양방향
반이중 : 한번에는 한쪽만 전송 무전기
직렬 : 일렬로만들어서 데이터를 순차적으로 보내는 것

동기식 : 박자를 맞춰서 전송(SYN, STX ETX)
비동기식 : start하고 end 둬서 그때그때 보내는것

LAN : 가까운 거리의 망
프로토콜 : LLC , MAC
응표세전(세그먼테이션)네(패킷)데이터링크(프레임)물리 (데이터링크,물리에잇음)

HDLC : 데이터링크에서 전송되는 프로토콜, 프레임으로 전송
프레임

데이터교환 방식 : 축적후 교환 패킷형태의 교환
가상회선
데이터그램

다중화 : 하나의 통신회선을 여러 가입자가 사용하는 기능
다중화 종류들

주파수 분할
시분할
코드분할
파장분할
공간분할

```
```
ipv4 : 유1:1멀1:다브1:전체
ipv6 : 유1:1멀1:다애1:옆사람이 공지 옆사람이 다시 옆사람한테 공지

A 클 0 시작
B 클 10 시작
C 클 110 시작

IPV4 8비트 4부분 32비트
IPV6 16비트 8부분 128비트

NAT 사설과 공인간의변환

DNS : IP주소에 도메인 주소 할당
DHCP 자동 IP 할당
QOS : 네트워크 품질 보장

통신프로토콜 : 구문, 의미, 타이밍
컴퓨터상 규칙, 약속 규약

슬라이딩 윈도우
스탑 엔 웨이트

피기배깅 : 양방향 통신에서 응답프레임을 같이보내는것

오류 수정 ARQ

전진 수정 : 자기가 스스로 수정하는 것 해밍 코드
후진 오류 수정 : 검출만하고 ARQ로 다시받는 거 : 패리티 코드, CRC

전송 : 검증해서 정확한 정보 전달
네트워크 : 비검증 빠르게 전달만

물리 - 리피터, 허브
데이터링크 - 스위치,브릿지
네트워크 - 라우터

동적 - igp egp
igp - rip(15홉 30초 인접내), ospf(링크 상태)
egp - bgp

정보보안 3요소
기밀성 인가된사용자만 사용
무결성 인가된사용자만 변경
가용성 : 인가된사용자 언제든지 접근

ddos 가용성해치는 공격

정보보안 aaa

authentication 인증
authorization 인가 권한
accounting : 활동들 계정관리

인증제도 isms pims(개인정보) isms-p

한국에서 만든거 seed, aria , lea (경량)

MD5 :빠른거
SHA : 미국에서 NIST에서 개발 해시함수
HAS-160 :우리나라에서 만듬

해시함수의 결정과 해결방법
레인보우 테이블-> 솔팅
무차별 공격 -> 키 스트레칭

커버로스 : 사용자와 서비스간의 인증 프로토콜
아이피 : 주민등록번호 대체 수단

MAC 강제적, 시스템이 결정 신원,
DAC 임의적, 소유자가 결정 
RBAC 역할기반 중앙관리자가 결정

벨라파듈라 - 기밀성을 강조 밑에있는 사람이위에있는사람 no read
위에있는사람이 밑에있는사람 no write

비바 모델 - 무결성 강조

클락 월슨 - 무결성 강조 업무처리

만리장성 모델 - 이해충돌 방지

ESM - 
SIEM - 빅데이터

dmz : 외부지만 내부 데이터에 접근 가능한 공간

ssh : 원격 외부에 접근하기 위한 보안 프로토콜 22
ssl : 웹에서 정보 전달 간 보안 적용 443

IPsec : 네트워크 계층 보안
AH (인증, 무결성) ESP (인증, 무결성 기밀성) IKE (키교환)

스머프 어택 : IP와 ICMP의 특성을 이용
랜드어택 : 출발지 목적지가 같다
티어드롭 : 플래그먼트 넘버를 위조
SYN FLOODING :SYN만 계속 주는거
UDP FLOODING : UDP 만 주는거
ping flooding : icmp echo 넘치게 주는거

ping of Death : 정상 크기보다큰 icmp 패킷을 주는거

dos : 공격주체가 내 자신
ddos : 공격주체를 쫄병들 한테 공격해라고 시키는거
트리누 udp 패킷을 이용해서 대량 데이터 발생

클라우딩 : 타사 호스팅 제품을 빌리는거
iaas 인프라 장비
paas 플랫폼
saas 소프트웨어 빌리는거

소프트웨어 3R

역공학
재공학 : 분석 재구 역공학 이관
재사용 
```
```
테스트 시나리오 : 테스트 케이스들의 집합
테스트 조건, 데이터, 결과값

집합 관계 두가지 집약, 합성

전송 : 신뢰성, udp, tcp 라우터 프로토콜 : igp, egp
네트워크 : 비신뢰, 빠르게 ip

입력,출력에 영향을 미치는 상황 -> 원인효과
입력->동등분할

cross join 카티전 프로덕트하고 where 조건 수행

FROM 테이블명 RIGHT OUTER JOIN 테이블명2
오른쪽거를 카티전하고 오른쪽거를 다표현

a[] -> 1차원배열
a[][] -> 2차원배열 행,열
구조체 배열 나오면 값을 넣는거 계산해서

*arr => arr의 주소
&arr 해야 arr의 주소값을 가져온다

모든프로그래밍언어에서 연산후 참은 1 거짓은 0
출력시에 달라짐

참, 거짓 결과값
C -> 0 과 1
Java -> true, false
Python -> True, False

static은 new로 객체를 생성안해도 쓸 수 있는 것이다.

i in range(1,3) <- [] 슬라이싱과 같다. 1부터 3-1 1부터 2까지

프로그래밍은 변경되는 변수와 for문밖에서 고정되는 값을 계산하는 것인지를 잘 판단

grant 권한 on 테이블명 to 
revoke 권한 on 테이블명 from

객체의 생성 처리를 별도의 클래스로 분리하는것 -> 팩토리 메서드

ftp 20 21 ssh 22 telnet 23 smtp 25 dns 53

a[1, 2, 3, 4, 5, 6, 7, 8, 9]
[-a,-b] 일경우에 -a부터 -b빼
a[-4:-2] = [6, 7] 
a[-1:-5] = [] 파이썬은 오른쪽부터 출력되기때문에 아무것도 출력안됨
-> 방법이없는가 있다 맨 마지막에 -1하면
a[-1:-5:-1] 이렇게 하면 [9,8,7,6] 이 출력된다.

데이터에는 ' ' 쌍따옴표 X
```
```
DDL : 3가지 create, drop, alter
DML : select, delete, update, insert

외래키 참조
속성명 foreign key preferences 테이블명 on delete cascade;
foregin key(속성명) preferences 테이블명 on delete cascade;

뷰 생성
craete view 뷰이름(속성명) as select ~

create view CC(ccid, ccname, instname) as select course.id, corse.name, instructor.name from course, instructor
where course.instructor = instructor.id

인덱스 생성
create index 인덱스이름 on 테이블명(속성 asc|desc);

권한 부여
grant on to

권한 회수
revoke on from

Rollback : 변경되었으나 commite 되지 않은 내용들을 취소하고 데이터베이스를 이전 상태로 되돌리는 명령어

Update

Update 테이블명 set 속성명=값 where 조건

Select
Select distinct 속성명 from 테이블명

distinct <- 중복을 제거하고 하나만 표시함, 속성명 앞에 위치

UNION ALL 중복 제거 X
UNION 중복제거 O

Join 조인

조인은 일반적으로는 from 절에 위치하나 어느 위치에서든 사용가능하다.

from 사원 a left outer join 동아리 on a.코드 = b.코드

inner 조인 한 후에 왼쪽에 있는것을 다표현하되 없는 속성값은 null로 해서 다 표현

트리거 : 데이터베이스 시스템에서의 이벤트가 발생했을 때 관련 작업이 작동으로 수행하게 하는 절차형 SQL

동등조인 EQUAL JOIN 3가지 표현 방식

1. where을 사용해서 동일한 조건을 나열
2. natural join 공통테이블명
3. 테이블명 1 join 테이블명2 using(속성명)

create table 테이블명 (문자 char(15), 숫자 int) primary key(속성), unique(속성), check a>=100(조건식)

a에게 b 테이블에 대한 모든 권한을 부여하고 권한을 남에게 줄 수 잇는 권한 까지 준다.

grant all on b to a with grant option
```
## 시험 전 마지막 프로그래밍 정리
[C](https://youtu.be/jxGsqCpLakA?si=mvG_ifL-5jD-66qM)    
[C 2](https://youtu.be/JepSpbDFqj8?si=CYTK_DrRgQ1-j-A5)     
[자바](https://youtu.be/vEi-qgeIaRs?si=sOEFJTZcoVveQ3fa)    
[파이썬](https://youtu.be/EQ74SvmdU4s?si=qcrVMhHUEH_33iUA)     
```
c언어 입출력 : %o 8진수 %x : 16진수

Java 언어 입력 : Scanner 라이브러리 import, scan 객체 생성 후 nextInt()로 정수형 값을 입력받는다.
객체 사용 후 close로 반환

연산자 우선순위

단산시 관비논 조대순

논리연산자 사이의 연산자 우선순위 & | ^

파이썬 print 는 엔터를 포함한것
엔터안하려면 print(a, b, end="") end를 붙여야 이어서 써짐

a[0,1,2,3,4,5] 슬라이스 a[0:1] = [0] 한개만나오더라도 괄호를 해줘야한다.
슬라이싱 -> 괄호 필수

[] 와 {}의 차이

{} 집합에는 중복요소가 들어갈 수 없기 때문에 add할 때 중복인게 있으면 무시된다.
```
![image](https://github.com/chihyeonwon/Engineer_Information_Processing/assets/58906858/58d7314a-80ab-467f-9619-2b14eba2782b)
```
print는 뒤에서부터 연산되며 ++i는 최종 i의값을 출력한다 중간에 연산이없기때문에
맨 뒤의 ++i 는 1 증가시키고 맨 마지막에 출력되는 i값을 출력한다.
```
![image](https://github.com/chihyeonwon/Engineer_Information_Processing/assets/58906858/2368b956-e5c7-4885-8dce-157149bc8ee0)
```
후위연산 i--는 현재 i값을 참조해서 출력한다.
--i는 i값을 먼저 -1하고 i를 참조하고 있다가 최종 i값을 출력한다.

프린트는 무조건 뒤에서부터 계산해서 출력

아스키코드 'a'-32 -> A

대문자가 소문자보다 작은숫자 항상 32차이가 나도록 설계되어 있음

<<스위치 케이스문>>
break가 없으면 아래끝까지내려감 break를 만날 때까지

<<포인터와배열>>
선언할 때 *은 포인터 즉 주소를 담을 거다
출력할 때 *은 주소에 있는 값을 출력한다

앞에 있는 문자까지 확인하고 쓸것

%s 는 뒤에꺼까지 모두 출력
%c 는 한 문자 출력

<< 구조체 >>
char 변수명[][10] = {"apple", "banana", "orange"} 2차원배열로 선언해야함

구조체 f = {"값", "값"}
*ptr포인터 = &f
출력 형태 ptr->name (*ptr.name과 같음)

포인터 왜쓰냐 ? 포인터는 크기가 작음, 메모리 유리, 자료구조, 알고리즘 구현가능
살아있는 애를 직접 접근하려고하면 구조체 변수가많을때 복사하기어려움

<< 자바 오버라이딩 >>
부모를 선언 -> 부모에 있는 메서드
자식으로 선언 -> 자식에 있는 메서드(상속)

System.out.println 이나 print 에 있는 문자를 출력하는 것을 잊지 말것

부모 형태 = 자식 생성자
메서드가 같을 때 무조건 자식에 있는 메서드를 호출함 재정의했기 때문
super는 부모를 호출

a%2==0 약수 약수의합

<<상속과 this>>
this는 자신과 제일 가까운것

<< 파이썬 set, list>>

set : 집합 {} : 순서 x 중복x
list : 리스트 [] : 순서 o 중복o

set에 데이터 넣는다.-> add
list에 데이터 넣는다 -> append

선언할 때 데이터를 중복하게 선언했다 집합
출력할 때 중복된것을 삭제하고 출력한다.

<<리스트 컨프리헨션>>
[산술식 for 임시변수 in 리스트 if 특정 조건식]
[x**2 for x in range(1, 11) if x % 2 == 0]

x에 1부터 10까지 들어가는데 조건식을 거쳐서 2,4,6,8,10의 제곱(x**2)
[4, 16, 36, 64, 100]

sort() 조건 없으면 오름차순 정렬 (작은것부터나열)

a=b.pop() 맨 뒤에있는 하나를 빼서 a에 리턴 a는 하나만 들어오고
b 배열 자체는 뺀 전체를 유지한다.

a가 만약 [1,3,5,15,9] 라면
b = a.pop()
print(b) <- 9
print(a) <- [1,3,5,15]

ARQ 자동 반복 요청
스고쉘
Stop and wait
go back n
selective repeat

udp : 비신뢰성, 비연결성
tcp: 신뢰성, 연결성, 흐름 제어, 혼잡 제어

상점비환: 상호배제, 점유와대기, 비선점, 환형대기

참샘휴일 : 참,샘플링,휴리스틱, 일관성 검사

solid rcssi lsp리스코프치환 자식->부모 대체
isp 인터페이스 분리 쓸데없는 거 만들 지 마라
dip 의존성 역전 : 자주 바뀌는 거 X

```
#### 디자인패턴 시험 직전
```
<<생성>>
Abstract Factory 추상팩토리 : 구체적인 클래스에 의존x 인터페이스를 통해서 그룹으로 생성해서 추상화하여 표현
Factory Method 팩토리메서드 : 객체 생성을 서브클래스에서 처리하도록 분리
<<구조>>
브릿지 : 기능 구현 연결
데코레이터: 기존 기능에 추가
퍼싸이드(건물의정면): 간단한 인터페이스, 시스템의 구조 파악
플라이웨이트 : 클래스의 경량화 -> 메모리 절약

```
