
##📍 Problem1

### 💡 Issues
- 예외처리해야하는 대상들
- 기능별 메서드 분리
  - 페이지의 자릿수의 합과 곱을 구할때 `String` 으로 변환시 `String.valueOf()` 를 사용할지  `toString()` 를 사용할지? 
    -  `String.valueOf()` : `null` 값들어올시 문자열 'null' 으로 처리
    - `toString()` : `null` 값들어올시 `Null PointerException(NPE)` 발생
- 주어진 배열이 유효한지 검증하는 메서드의 설계

### 🛠 Todo
- 공통된 부분의 리팩토링
- 각 메서드의 가독성 체크

<br>

##📍 Problem2

### 💡 Issues
- 기능별 메서드 분리
    - 주어진 문자열이 복호화가 필요한지 체크하는 기능의 분리가 적절한지?
    - SOLID 의 SRP 를 지키는것에 해당하는지?
- 문자열을 복호화할때 까지 체크하는 `while` 문에서 무한 루프에 빠지지는 않는지?    

### 🛠 Todo
- `while` 문 예외 발생하는지 체크

<br>

##📍 Problem3

### 💡 Issues
- 기능별 메서드 분리
  - 박수 쳐야하는지 여부를 체크하는 기능과 박수 횟수를 계산하는 기능을 분리해야할지?

### 🛠 Todo
- 리팩토링 고민


##📍 Problem4

### 💡 Issues
- 기능별 메서드 분리
  - 문자열들을 매번 계산하는것보다 전역변수로 HashMap을 만드는 메서드와 상응하는 문자열을 가져오는 부분을 분리
  - 상수로 선언한 a,z,A,Z 의 아스키 코드를 `static final` 로 선언한것이 적절한지?
  - 전역변수들을 선언하지 않으면서 효율적인 기능 구현이 가능한지?

### 🛠 Todo
- 리팩토링 고민


##📍 Problem5


##📍 Problem6


##📍 Problem7