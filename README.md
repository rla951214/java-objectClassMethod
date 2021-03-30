# java-objectClassMethod

### 공부한 내용
- toString메서드
1. 객체의 정보를 String으로 바꾸어서 사용할 때 많이 쓰인다
2. String 이나 Integer 클래스에는 이미 재정의 되어 있다
3. String = 문자열 반환 / Integer = 정수 값 반환

- equals메서드
1. 두 인스턴스의 주소 값을 비교하여 true/false를 반환한다
2. 재정의 하여 두 인스턴스가 논리적으로 동일함의 여부를 반환한다
3. 같은 경우 여러 인스턴스의 주소 값은 다르지만, 같은 처리방식을 해야 할 경우 equals메서드를 재정의한다

- hashcode메서드
1. 정보를 저장, 검색하기 위해 사용하는 자료구조
2. 자료의 특정 값에 대해 저장 위치를 반환해주는 해시 함수를 사용한다
3. 해시 함수는 어떤 정보인가에 따라 다르게 구현된다
4. hashcode메서드는 인스턴스의 저장 주소를 반환한다
5. 힙 메모리에 인스턴스가 저장되는 방식이 hash이다

- clone메서드
1. 객체의 원본 복제하는데 사용하는 메서드
2. 객체 clone 메서드 사용을 허용한다는 의미로 cloneable 인터페이스를 명시해 준다 (중요!!)
