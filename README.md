### 주문취소 환불 계산기 샘플

사용 기술 : html, javascript, jquery, bootstrap

- 주문서의 상품을 자유롭게 취소할 수 있는 환불 계산기입니다.
  
- 할인 쿠폰이 적용된 주문서이며, 정해진 쿠폰 정책에 의해 취소 금액이 계산됩니다.

- [계산기 샘플 링크](https://daye9005kim.github.io/toy/)

- ![image](https://github.com/daye9005kim/toy/assets/78843974/aedee89c-865a-46a9-ae4e-702cf1f518e7)
  
- 장바구니 쿠폰의 경우 최소 사용 금액 조건, 구매자 귀책, 판매자 귀책 여부에 따라 취소 정책이 적용됩니다.
  - 구매자 귀책인 경우 장바구니 쿠폰 금액 조건을 충족하지 않으면 장바구니 쿠폰 전체 할인 금액을 제외하고 환불합니다.
  - 예) 상품 A 1,000원, 상품 B 1,000원, 상품 C 1,000원 3종류의 상품을 구매하며 "2,000원 이상 구매 시 300원 할인" 장바구니 쿠폰을 적용한 주문에서 상품 A, B 취소 시 최소 사용 금액 조건을 불만족하므로 환불액에서 300원을 제외하고 1,700원을 환불
  - 판매자 귀책인 경우 장바구니 쿠폰 금액 조건을 따르지 않고 실결제금액을 환불합니다.

- 체크박스 선택 시 금액 조건에 따른 취소 처리 방식을 토스트로 안내합니다.
  
- 차감 금액에 입력된 금액은 제외하고 환불합니다. 잔액으로 남습니다.
