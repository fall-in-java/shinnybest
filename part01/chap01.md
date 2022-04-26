## 자바 8, 9, 10, 11 : 무슨 일이 일어나고 있는가?
### 자바 8 설계의 밑바탕을 이루는 세 가지 프로그래밍 개념
#### 1. 스트림 처리
스트림: 한번에 한개씩 만들어지는 연속적인 데이터 항목들의 모임
스레드라는 복잡한 작업을 사용하지 않으면서도 공짜로 병렬성을 얻을 수 있다.
#### 2. 동작 파라미터화로 메서드에 코드 전달하기
동작 파라미터화: 메서드를 다른 메서드의 인수로 넘겨주는 기능 제공
#### 3. 병렬성과 공유가변 데이터
### 자바 함수
프로그래밍 언어에서 함수라는 용어는 메서드 특히 정적 메서드와 같은 의미로 사용된다.
#### 1. 메서드와 람다를 일급시민으로
메서드를 값으로 취급할 수 있게 만든 것이 자바 8 설계의 핵심
자바 8에서는 메서드가 일급값이기 때문에 객체 참조처럼 메서드 참조를 만들어 전달할 수 있게 되었다. 
#### 2. 코드 넘겨주기
* 프리디케이트
### 스트림
스트림 API를 사용하게 되면 컬렉션 API와는 상당히 다른 방식으로 데이터를 처리할 수 있다.
컬렉션 API : 외부 반복
스트림 API : 내부반복(라이브러리 내부에서 모든 데이터가 처리됨)
#### 멀티스레딩은 어렵다
자바 8은 스트림 API로 컬렉션을 처리하면서 발생하는 모호함과 반복적인 코드 문제, 멀티코어 활용 어려움이라는 두 가지 문제를 모두 해결했다. 
### 디폴트 메서드와 자바 모듈
### 함수형 프로그래밍에서 가져온 다른 유용한 아이디어