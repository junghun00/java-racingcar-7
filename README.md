# java-racingcar-precourse


## ⚒️️️ 역할에 맞게 클래스 분류 하기

- 입/출력 관리
- 자동차 이름 input 값 파싱 및 이동 횟수 전달
- 자동차 인스턴스 생성 및 이동 명령
- 무작위 값 출력 실행
- 에러 메세지 enum 목록 구현

--------------------------------------------------------

## 💬 입/출력 관리

#### 1. 입력 구현

- 자동차 이름 입력 받기
  - 입력값이 올바르지 않다면 에러
- 행동 지시 횟수 입력 받기

#### 2. 출력 구현

- 자동차 인스턴스를 받아 실행 결과 출력
  - 자동차 이름
  - 자동차 전진 횟수
- 최종 우승자 이름 출력


## 🔍 입력값 파싱 하기

#### 1. 자동차 이름 파싱

- (,) 기준으로 구분
- (,) 연속적으로 나올 경우 에러
- 문자, 숫자 외 입력 시 에러
- 이름 입력 전과 후 공백 허용(글자수 포함 x)
- 이름 사이에 공백 없는가
- 5자 이하 인가

#### 2. 시도할 횟수 파싱

- 숫자 인가

## 🚕 자동차 객체 및 행동 구현

#### 1. 자동차 객체 만들기
 
- 필드 작성
  - 자동차 이름
  - 전진 횟수 카운트
- 자동차 인스턴스 생성

#### 2. 자동차 이름 받는 생성자 생성

- move() 메서드 생성
  - 4 이싱 인가?
  - 전진 카운트++

## 🎲 무작위 값 생성

- 입력 횟수 만큼 무작위 값 생성하기

## ☠️ 에러 메세지 Enum Type 정리
