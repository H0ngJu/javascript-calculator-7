# javascript-calculator-precourse

## 기능 구현 목록

- [x] 문자열 입력받기
- [x] 구분자
  - [x] 커스텀 구분자로 분리
  - [x] , :로 분리
- [x] 입력받은 숫자의 합 출력
- [ ] 예외 처리
  - [x] 빈 문자열인 경우
  - [ ] 숫자가 아닌 문자가 입력된 경우
  - [ ] 양수가 아닌 숫자가 입력된 경우
  - [x] 커스텀 구분자 양식이 잘못된 경우
  - [ ] 연속된 구분자가 잘못된 경우 (구분자가 2개 이상인 경우)

## Flow

1. 문자열 입력 받기

   1. 커스텀 구분자 양식이 잘못된 경우
   2. 커스텀 구분자가 잘못된 경우

2. 구분자로 분할한다
   2-1. 커스텀 구분자가 없는 경우 → : or ,로 split한다.

   2-2. 커스텀 구분자가 있는 경우 → 커스텀 구분자로 spilit한다.

3. error를 확인한다.

   1. 문자가 속한 경우
   2. 양수가 아닌 경우

4. 입력한 수들을 합하여 출력한다.

## 과제 요구 사항

- [ ] 외부 라이브러리는 사용하지 않는다.
- [ ] 프로그램 종료시 process.exti()를 호출하지 않는다.
- [ ] 파일, 패키지 이름을 바꾸거나 이동하지 않는다.
- [ ] JS 코드 컨벤션을 지킨다.
- [ ] @ woowacourse/mission-utils에서 제공하는 Console API를 사용하여 구현
- [ ] 사용자의 값을 입력, 출력하려면 Console.readLinAsync()와 Console.print()를 활용
