# java-racingcar-precourse
# 구현 기능 목록

## 🎯 경주 자동차 이름 입력

- [x] 각 자동차에 이름을 부여할 수 있다.

- [x] 자동차 이름은 쉼표 `,` 를 기준으로 구분한다.


```java
pobi,woni, jun
```

❌ **예외처리**

- [x] 자동차에 이름을 부여하지 않은 경우

- [x] 자동차 이름은 5자 이하만 가능하다.

- [x] 자동차 이름이 중복된 경우

## 🎯 시도 횟수 입력

- [x] 몇 번의 이동을 할 것인지 정수 입력

```java
5
```

❌ **예외처리**

- [x] 정수가 아닌 다른 문자가 입력 되었을 경우

## 🎯 경기 실행 기능

- [x] 전진 하기 (0~9 사이에서 무작위 값을 구한 후 무작위 값이 4 이상일 경우)

- [x] 차수 별 진행상황 출력하기

```java
pobi : --
woni : ----
jun : ---
```

❌ **예외처리**

## 🎯 우승자 안내 문구 출력

- [x] 가장 많이 전진한 자동차를 구한다.

- [x] 우승 자동차의 이름을 출력한다.

- - [x] 단독 우승자 안내 문구

```java
최종 우승자 : pobi
```

- - [x] 공동 우승자 안내 문구

```java
최종 우승자 : pobi, jun
```

❌ **예외처리**