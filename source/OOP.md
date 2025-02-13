# 객체 지향 프로그래밍 (OOP, Object-Oriented Programming)
> 프로그램을 **객체** 단위로 설계하고 구현하는 방식

## 구성 요소
1. **객체 (Object)**: 속성(값)과 메서드(기능)로 구성된 독립적인 요소
2. **클래스 (Class)**: 객체를 정의하는 설계도
3. **속성(Attributte)**: 객체가 가지는 값
4. **메서드 (Method)**: 객체가 수행하는 기능 혹은 동작

## 핵심 개념
### 캡슐화 (Encapsulation)
* 정의: 객체 외부로부터 객체 내부를 보호하는 방식
* 활용 예시
    * 외부에서 객체 내부에 직접 접근하는 것을 제한하며, 특수 함수(get, set 등)를 이용하여 내부 상태를 변경
    * python에서는 접근 제어 키워드가 없으므로 캡슐화의 개념이 없으며, 함수나 변수 앞에 _를 붙여 접근을 제어

### 다형성 (Polymorphism)
* 정의: 동일한 인터페이스를 여러 형식의 객체가 공유하는 방식
* 활용 예시
    * **메서드 오버라이딩 (Method Overriding)**
        * 자식 클래스에서 부모에게 상속 받은 메소드를 재정의하여, 동일한 이름이지만 객체에 따라 다르게 동작하도록 정의하는 기법
    * **메서드 오버로딩 (Methtod Overloading)**
        * 같은 이름의 메서드에 대하여 입력으로 들어오는 메개변수의 타입이나 개수에 따라 다르게 동작하도록 정의하는 기법
        * 파이썬에서는 직접적으로 지원하지 않지만 args, 데코레이터 등을 이용하여 비슷한 효과를 낼 수 있음
    * 파이썬의 + 연산자는 다형성을 지원하여 정수 덧셈 뿐만 아니라 문자열 합치는 기능도 수행 가능하다.

### 추상화 (Abstraction)
* 정의: 불필요한 부분을 숨기고 사용자가 필요한 부분만 노출하는 방식

### 상속 (Inheritance)
* 

### 컴포지션 (Composition)
* 


## 기본 원칙
### 개방-폐쇄 원칙 (The Open/Close Principle)

### 제어 반전 원칙 (The Inversion of Control Principle)

### 인터페이스 분리 원칙 (The Interface Segregation Principle)

### 단일 책임 원칙 (The Single Responsibilitty Principle)

### 치환 원칙 (The Substituttion Principle)




