<img src="https://github.com/ChaeDoll/Presentation/assets/108540812/564ade14-586b-40f8-bf6c-f1733be35394" width="30%" align="center">  

### XML (Extensible Markup Language - W2C에서 개발 / 확장가능한 마크업 언어)

- HTML의 한계를 극복하고자 등장
- HTML과 유사하게 생긴 형태
- **구조적인 데이터**를 위한 것이다

### XML의 형태

- XML은 태그라는 마크업 언어를 통해 데이터를 정의하고 관리한다

형태 예시 … 

> <family>
      <human>
            <mother age>Alice</mother>
            <father>John</father>
            <brother>Paul</brother>
            <me>Chaeyun</me>
      </human>
      <animal>
            <dog>Choco</dog>
      </animal>
</family>
> 
- 위 형태에서 엿볼 수 있듯이,  데이터를 정리하는 데에 용이한 언어
- 다른 사용자와 정보를 교환할 때  긴 설명 필요 없이 태그를 통해 원하는 데이터를 취득 가능

### HTML과 다른 점?

- HTML은 데이터 표시가 주 목적, XML은 데이터 저장과 전송이 주 목적
- HTML은 미리 정의된 이름의 태그를 사용, XML은 고유의 태그를 만들고 정의 가능
- HTML은 대소문자를 구분하지 않지만 XML은 대소문자를 구분하여 사용해야

### XML 외의 데이터를 다루는 기술

- XML
    
    장점 : javascript를 통해 원하는 데이터를 쉽게 뽑아낼 수 있음
    
    단점 : 작성하기 어렵고 오래걸리고 용량이 큼
    
- CSV
    
    **콤마와 엔터키를 사용하여 표 형식으로 데이터를 저장함 (comma - separated values)**
    
    > ID, Country, Name, Age
    1153, Korea, Suhyeon, 22
    1263, Japan, Urika, 25
    1662, China, Lin, 21
    > 
    
    장점 : 데이터베이스에 있는 내용을 담기가 편함 (엑셀 표와 같은 형식)
    
    단점 : 표 안에 표가 있는 고차원 데이터를 담는 데에 한계가 있음
    
- JSON
    
    **키-값 쌍으로 이루어진 데이터 오브젝트를 전달하기 위한 표준 포맷 (javascript object notation)**
    
    > { “users” : [ { “first name” : “Lim”, “last name” : “Chaeyun”, “joined” : { “month” : “June”, “day” : 16, “year” : 2022 } }, { “first name” : “Lee”, “last name” : “Hoyeon”, “joined” : { “month” : “October”, “day” : 22, “year” : 2021 } } ] }
    
    .json 파일을 생성하여 데이터를 담을 수 있음
    
    장점 : 자료 종류에 제약이 없고 컴퓨터 프로그래밍에 있어서 변수 값 표현에 용이함 (많이 사용),  
              사람과 기계 둘 다 이해하기 쉽게 되어있음
    
              언어와 플랫폼에 제약이 없기 때문에 다른 시스템 간 객체 교환에 좋음
