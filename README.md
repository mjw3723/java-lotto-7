# java-lotto-precourse

## 📌 구현할 기능 목록
### 1. 구입금액 입력 
- [x] 구입금액 입력 문구 출력한다.
- [x] 구입금액 입력 받는다.
### 2. 구입금액 검증 
- [ ] 빈 문자열이 입력 되는 경우
- [ ] 숫자 이외의 값을 받는 경우
- [ ] 음수의 값을 받는 경우
- [ ] 1000원으로 나누어 떨어지지 않는 경우
- [ ] 공백이 들어간 경우
### 3. 구입한 로또 출력
- [ ] 몇 장 구입 했는지 출력한다.
- [ ] 구입한 만큼 중복 되지않은 6자리 숫자 배열을 출력한다.
### 4. 당첨 번호 입력
- [ ] 당첨 번호 입력 문구 출력한다.
- [ ] 당첨 번호를 입력 받는다.
### 5. 당첨 번호 검증
- [ ] , 로 추출 하였을 때 숫자 6개가 안되는 경우
- [ ] 빈 문자열이 입력 되는 경우
- [ ] 추출한 값이 숫자가 아닌 경우
- [ ] 추출한 값이 음수인 경우
- [ ] 번호가 1부터 45가 아닌 경우
### 6. 보너스 번호 입력
- [ ] 보너스 번호 입력 문구 출력한다.
- [ ] 보너스 번호를 입력 받는다.
### 7. 보너스 번호 검증
- [ ] 빈 문자열이 입력 되는 경우
- [ ] 숫자 이외의 값을 받는 경우
- [ ] 음수의 값을 받는 경우
- [ ] 번호가 1부터 45가 아닌 경우
### 8. 당첨 통계 출력
- [ ] 당첨된 통계 출력
- [ ] 수익률 출력

## 체크 리스트
-[ ] JDK 21 버전에서 실행 가능해야 한다.
-[ ] Java Enum을 적용한다.
-[ ] Random 값 추출은 camp.nextstep.edu.missionutils.Randoms의 pickUniqueNumbersInRange()를 활용한다.
-[ ] 사용자가 입력하는 값은 camp.nextstep.edu.missionutils.Console의 readLine()을 활용한다.