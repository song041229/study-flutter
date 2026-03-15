## 1. 데이터 타입


- 정적 type
    - int
    - double
    - bool
    - String
    -
          int a = 10;
          String a1 = " ";
          bool a2 = true;
          double pi = 3.14;


- 동적 타입
    - var
    - dynamic
    -
            // b1타입 모름 -> 10이 할당됨 -> 앞으로 계속 int
            var b1 = 10;
        
            // b2 타입 모름 -> 맨 처음과 나중 type가 달라도 됨
            dynamic b2  = a1;
            b2=pi;


- 자료구조
    - List< >
    - Map< , >


      // List
      List<String> users = ["철수", "민지", "지원"];
      String user = users[0];

      // Map
      Map<String, dynamic> map = {}

- null safety
    - 초기화 안해도 됨
    - `?`로 지정
    - `String? type`
  
- late
    - 나중에 값 지정할테니 error 만들지 말라

