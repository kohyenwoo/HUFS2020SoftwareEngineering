# HUFS2020SoftwareEngineering

### Why is this project created?
This is the class project of Team 5, Software Engineering Class, Information and Communication Engineering, Hankuk University of Foreign Studies.

### What is the purpose of this project?
When junior and rookie developer starts to work in big scale field work, they should know about UML(Unified Modeling Language) to contribute well in the project. We would use class material to improve our main contribute ability in any programming development.

### Contributor (Team Members)
강병규 / 고현우 / 김현석 / 정윤성 / 👑 홍영빈

### Supervisor Professor
Saehwa Kim (http://eselab.hufs.ac.kr/index.php/Main_Page)

- - -

### 과제 1 : Team Building

* 각 팀은 비대면 소통 진행

   - 카톡 단톡방 개설

      - 가능한 소통은 여기에서 진행
      
      - 별도의 회의록이 필요 없어지는 장점
        
      - 마지막 wrap-up이 필요
      
      - 비대면 미팅 시간 잡기: 카톡 투표 기능을 이용: https://blog.naver.com/PostView.nhn?blogId=worms1603&logNo=221671288671
      
   - Google hangout으로 비대면 미팅

      - 카톡 단톡방에서 google meet 주소 공유
      
      - 채팅 시 가능한 google meet이 아닌 카톡에서 나누는 것이 좋음
      
      - google meet은 특별히 설정을 하지 않는 한 채팅했던 내용이 사라짐
      
   - Github에 프로젝트 팀 페이지 개설
   
* Github 링크 제출 (못 만들었으면, 그냥 문서(ppt)로 제출)

   - 프로젝트 주제

   - 팀 구성원(participants), 각 멤버 역할(role), 각 멤버 역량(skills)
   
   교과서 예시)
   
   |Participant|Roles|Skills|Training needs|
   |:----------|:----|:-----|:-------------|
   |Alice|Team leader|Management: team leader<br>Programming: C<br>Configuration management|UML<br>Communication skills|
   |John|Architecture liasion<br>Implementor|Programming: C++<br>Modeling: UML|Java|
   |Mary|Configuration manager<br>Implementor|Programming: C++,Java<br>Modeling: Entity relationship<br>Databases: relational<br>Configuration management|Object-oriented databases<br>UML modeling|
   |Chris|Implementor|Programming: C++, Java<br>Modeling: Entity relationship<br>Databases: object-oriented|UML modeling|
   |Sam|Facilities management liasion<br>Tester|Programming: C++<br>Testing: whitebox,blackbox|Inspections<br>Java|
      
- - -

### 과제 1 답안
      
   - 비대면 미팅 시간 

   ![kakaotalk1](https://github.com/archer0307/HUFS2020SoftwareEngineering/blob/master/images/kakaotalk1.png)
   
   - Google Hangout으로 비대면 미팅 진행
   
   ![hangout1](https://github.com/archer0307/HUFS2020SoftwareEngineering/blob/master/images/hangout1.png)
   
   - Github Team Project URL
   
   URL) https://github.com/archer0307/HUFS2020SoftwareEngineering
   
   - 프로젝트 주제
   
   Web Publishing & Web Application Server Programming with Spring Framework & Bootstrap. : HUFS ICE homepage renewal.
   
   - 팀 구성원들의 역할과 멤버 역량, 그리고 요구 사항
   
   |Participant|Roles|Skills|Training needs|
   |:----------|:----|:-----|:-------------|
   |강병규|View Publisher|Programming: C, Java|Bootstrap, HTML, CSS, JS|
   |고현우|Service & Mapper Implementor|Programming: Java|UML|
   |김현석|Database Management<br>Tester|Programming: Python, C, SQL<br>Framework: Django|JAVA, UML, mybatis|
   |정윤성|Controller Implementor<br>Master liasion|Programming: C, Java|UML|
   |홍영빈|Team Leader<br>View Publisher<br>Controller Implementor|Programming: C, Java, Python, mybatis, Freemarker<br>Framework: Django, Spring, Bootstrap|UML|
      
- - -

### 과제 2 : Problem Statement

지난 번에 제출한 Project GitHub에 Project 제목과 Project Problem Statement를 추가

Project Problem Statement: 고객(client, customer)과 사용자(end user) 관점에서 기술, 개발자 관점이 아니라. 

 --> 요구사항 (Requirement) 기술

 --> 풀고자 하는 문제 자체를 기술 (Anlaysis 영역):

   * 최소한 개조식 항목 3개~5개

   * 제공하는 기능 (functional) 관점에서 (가능하면 nonfunctional requirement도 기술 가능)

   * 여러분이 만드는 시스템이 제공하는 기능을 사용하는 주체(어떤 사람인지.. 학생, 교강사, 임산부, 노인 등)가 기술되어야 함

   * 이 시스템의 기능을 제공하기 위해서 활용해야 되는 외부 시스템 (기상청 날씨 제공 서버, 식당 CC TV 등)이 있으면 기술해야 함

   * 활용해야 되는 I/O 디바이스(LCD 패널, 브레이크, 엑셀, 특수 버튼, 비콘)가 기술되어야 함
   
 --> 구체적인 기술로 어떻게 하는지는 얘기를 안 해도 됨 (Design 영역) 

1, 2, 4팀은 발표

- - -

### 과제 2 답안

 - 요구사항 (Requirement 영역)
   
   * 게시판에 학생들의 의견 반영을 위한 기능 추가.
   
   * 학기 초 학생들의 서적 구매 편의성을 위하여 한정기간 책 공동구매 탭이 필요함.
   
   * 영업시간 내에 학교 생활에서의 애로 및 건의사항 해결을 위하여 학과 조교님과 학부생의 실시간 채팅 상담 기능 추가.

 - 풀고자 하는 문제 (Anlaysis 영역)
   
   * "학과 홈페이지"의 "교과과정 탭" 에서, 학부생들에게 다음과 같은 상세한 학과 과목의 정보를 제공.

      1. 학과 교육이수에 필요한 전공 서적.
      2. 원활한 수업 이해를 위한 전공관련 배경지식. (이수요구사항)
      3. 학기 초에 담당 교수님 배정 이후 교과목 교수님의 정보 자동 제공.
      4. 한국외국어대학교 종합정보시스템과의 연계로 선택 교과목의 강의계획서를 볼 수 있는 링크 제공.
      
      현재 교육과정 탭)
      
      ![curriculum](https://github.com/archer0307/HUFS2020SoftwareEngineering/blob/master/images/curriculum.png)
      
   * 학과에서 운영하는 스터디룸 예약 시스템 제공.

   * 한국외국어대학교 정보통신공학과에 관심이 있는 대학 진학 예정자, 정보통신공학과 학부생, 학부 편입생 등이 사용하는 주체가 될 예정.

   * 전공 서적 가격 비교를 위해 각 서적 사이트의 전공 책 가격 비교 시스템 구축.
   
   * 보안을 위한 도구
      
      1. 공유기를 활용한 포트포워딩.
      2. 공유기를 통한 중국발 외부 IP 및 포트 원천 차단.
      3. 소스코드 내부의 HashMap을 extends한 CamelMap을 활용하여 메소드에 접근 할 수 없게 제한.
   
   * 활용되는 Input/Output 디바이스.
      
      1. 보안에 상대적으로 Linux 보다 안전한 Windows 서버 컴퓨터 사용.
      2. 서버 컴퓨터 내부의 대용량 하드 디스크 필요.

 - 대략적인 디자인 (Design 영역)
   
   * 현대적인 홈페이지에 어울리는 세련된 디자인 감각.
   
   * 홈페이지의 약간 부족한 직관성을 보완하여 디자인적 요소를 Bootstrap Framework를 활용하여 개선.
   
   * 교과과정에 자유롭게 과목을 추가하고 제거할 수 있는 UI 구성, 전면적인 구성 개편 필요.
   
- - -

### 과제 3 : 	Use Case Diagram

* Use Case Diagram

  - 모두 영어로: 왜냐하면, 결국 영어로 작성되는 SW로 구현될 것이어서

  - Visual Paradigm으로 작성

  - Actors: user, I/O device, external system that our system exploits

  - Use Cases: Verb (동사) + Objective (목적어) 

  - System Boundary (직사각형): 분산 시스템이면 여러 개 있을 수 있음

* Scenario Description (최소한 하나 이상)

* Use Case Description (모든 use case에 대해 다 할 필요는 없으나, 최소한 하나의 use case에 대해서는 작성)

==> Github 링크로 제출

* 3, 5, 6팀은 반드시 발표.

- - -

### 과제 3 : 답안

* Use Case Diagram

![UseCaseDiagram3](https://github.com/archer0307/HUFS2020SoftwareEngineering/blob/master/images/UseCaseDiagram3.jpg)

* Scenario Description

Actors: 대학생 현석, 학과 사무실 조교

Scenario:
   1. 대학 신입생인 현석은 학기가 시작하기 전 자신이 공부할 과목을 알아보기 위해 학과 홈페이지에 방문했다.
   2. 공부할 과목을 알아본 현석은 교재 구매를 위해 학과홈페이지의 온라인 서점 가격 비교 서비스 메뉴를 클릭.
   3. 서점별 가격이 나열되어있어 현석은 그중 가장 싼 곳에서 구매할수 있었다.
   4. 교재 구입 후 전공과목에서 의문이 생긴 현석은 학과 홈페이지의 실시간 대화창으로 질문을 했다.
   5. 조교는 실시간 대화창에서 현석이 날린 메시지를 보고 확인 후 답변해주었다.

* Use Case Description

   *1.searchBookInfo
   
   ![searchBookInfo](https://github.com/archer0307/HUFS2020SoftwareEngineering/blob/master/images/searchBookInfo.JPG)
      
      1. 학생, 학과 조교 및 교수진은 한 학기에 대한 링크를 클릭한다.

      2. 학과 홈페이지는 SemeseterInfo page로 넘어간다. 그 페이지에는 그 학기에 수강할 수 있는 강의, 그 강의에서 쓰는 교재, 연계 과목 등이 쓰여있다. 교재 제목은 서점의 검색  페이지로 링크되어있다.

      3. 학생, 학과 조교 및 교수진은 교재 제목을 클릭한다

      4. 링크는 서점의 검색창으로 연결된다. 그 페이지에는 교재의 가격이 적혀있다.
              
   

   *2. setRTChattingService

   ![setRTChattingService](https://github.com/archer0307/HUFS2020SoftwareEngineering/blob/master/images/setRTChattingService.JPG)
   
      1. 학생은 화면 오른쪽 밑에 있는 작은 창에서 두 개 중 하나의 버튼을 선택한다:"조교와 채팅" / "교수님과 채팅". 이 후 창은 채팅창으로 바뀐다. 창 위쪽에는 수신자의 이름이 명시
         되어 있다. 학생은 메시지를 작성한다. 그리고 서버는 그 메시지를 과 홈페이지로 전달한다.

      2. 과 홈페이지는 메시지를 수신자에게 보낸다.

      3. 수신자(과 조교나 교수진)는 채팅창을 통해 답한다. 창 위쪽에는, 송신자의 이름이 명시되어 있다. 이 후 이 메시지를 과 홈페이지로 전달한다.

      4. 과 홈페이지는 메시지를 수신자(이 경우엔 송신자(학생))에게 보낸다.
            
            
    *3. showBookList
    
    ![showBookList](https://github.com/archer0307/HUFS2020SoftwareEngineering/blob/master/images/showBookList.JPG)
    
      1.각 학과별로 사용하는 전공책들의 리스트

      2.(1)책을 검색하거나,(2)전공이름 > 전공책 클릭시 그책의 관한 가격및 구입창 출력

      3.이 책을 구매할수있는 사이트중 가장 적은 가격의 사이트순으로 가격을 보여줌

      4.이책을 구입하는데 사용할수있는 할인정보를 보여줌
      
- - -

### 과제 4 : Sequence Diagram and Class Diagram

Sequence Diagram and Class Diagram 

* 수정된 use case diagram, use case/scenario description 

    - 담당자 이름 표시

* Use case diagram의 각 use case 별로 하나씩 sequence diagram이 그려져야 함.

    - 여러분 숙제에서는 중요한 use case 2~3개를 골라서 각각 2~3개의 sequence diagram을 그림

    - 작성자 이름 표시 

* Class diagram은 한 개

    - Sequence diagrams를 모두 아우르는 다이어그램

    - Role name, attributes, operations, multiplicity 가능한 다 표시

    - 작성자 이름 표시

* Object diagram은 한 개

   - Scenario description 하나에 대해

   - 객체 이름에 클래스 이름도 반드시 표시

   - 작성자 이름 표시
   
- - -

### 과제 4 : 답안

   **Class Diagram
   
   ![ClassDiagram](https://github.com/archer0307/HUFS2020SoftwareEngineering/blob/master/ClassDiagram.JPG)

   *작성자:정윤성*
   
   
   **Object Diagram
   
   Senario:   
   
   1. 대학 신입생인 현석은 학기가 시작하기 전 자신이 공부할 과목을 알아보기 위해 학과 홈페이지에 방문했다.
   2. 공부할 과목을 알아본 현석은 교재 구매를 위해 학과홈페이지의 온라인 서점 가격 비교 서비스 메뉴를 클릭.
   3. 서점별 가격이 나열되어있어 현석은 그중 가장 싼 곳에서 구매할수 있었다.
   
   ![Object1](https://user-images.githubusercontent.com/49778514/95831348-dfad2a80-0d73-11eb-8c3d-d5bf216bc862.png)
   
   *작성자:김현석*


   **Sequece Diagram
   
   *1. Use Case: reserveStudyRoom**
   
   ![ReserveStudyRoom](https://user-images.githubusercontent.com/67492707/95797652-fd09d680-0d2a-11eb-98f9-257981780445.png)

   *작성자:강병규*



   *2. Use Case: Web, Group purchase*
   
   ![sequence](https://user-images.githubusercontent.com/70632490/95938347-ad073e80-0e14-11eb-8dda-32a378f491bc.PNG)
    
   *작성자: 고현우*



### 과제 5 : Component Diagram
* Design Goal Description (최소한 2개 이상: 우선순위 순서로)

 

* Component Diagram

   - 출발점은 Analysis Class Diagram (이미 했던 거)

   - Architectural style 적용을 통해 새로운 클래스가 추가될 수 있음: Anlaysis 단계에 없던 것은 별도로 표시 <<design>>

   - 우리 팀이 만드는 게 아니라 가져다 쓰는 COS(Commertial Off the Shelf)도 표현 <<imported>> 또는 <<COS>>

   - Component 간의 의존성(dependency) 표현(--->) + Component 내 포함된 클래스(structured class: 내부 클래스와 외부로 연결되는 Uses(()와 Provides(o) 인터페이스 연결도 표시)

  

 

(다음 시간에 Deployment Diagram) 



### 과제 5 : 답안

   **Design Goal Description
     
     -Textbook Group Purchase
      1. 우리 학교 웹사이트가 외부 프로그램인 북스토어에게 얼마나 잘 지원받을 수 있는가(Utility)  
   
      2. 매 학기마다 과목 정보가 잘 업데이트되는가(Extensibility, Modifiability)
   
   
   **Component Diagram
   ![diagram](https://user-images.githubusercontent.com/70632490/100821432-b2d3e480-3493-11eb-8bfb-758f917dce00.PNG)
   
   *작성자: 고현우*
   
   
   **Deployment Diagram
   ![deployment2](https://user-images.githubusercontent.com/70632490/100822885-8b324b80-3496-11eb-8167-aefeb64b60a1.PNG)
   
   *작성자: 고현우*
