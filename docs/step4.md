# 🚀 4단계 - 로또(수동)

## 기능 요구사항

- 현재 로또 생성기는 자동 생성 기능만 제공한다. 사용자가 수동으로 추첨 번호를 입력할 수 있도록 해야 한다.
- 입력한 금액, 자동 생성 숫자, 수동 생성 번호를 입력하도록 해야 한다.

### 기능 리스트

- [ ] 사용자가 수동으로 로또번호를 입력할 수 있어야 한다.
- [ ] 로또번호는 콤마(`,`)로 구분된 6자리 숫자이며, 각 로또는 줄바꿈(`\n`)을 기준으로 분리한다.
- [ ] 잘못된 형식인 경우 논리오류로 판단하고 exception throw
- [ ] 수동으로 구매하는 로또 개수보다 구입금액이 적은 경우 구입금액에 만큼 로또를 구매한다.
- [ ] 수동으로 구매하는 로또 개수보다 구입금액이 큰 경우 차액만큼 자동구매한다.
- [ ] 원시타입을 포장한다 (amount)