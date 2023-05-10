# android-shopping-cart

## Step1
- [ ] 사용자는 상품 목록의 상품을 장바구니에 추가할 수 있다.
  - [x] 상품 목록은 RecyclerView에 GridLayoutManager를 설정하여 구현한다.
  - [x] 상품을 클릭하면 상품 상세로 이동한다.
  - [x] 상품 상세에서 장바구니에 상품을 담을 수 있다.
  - [x] 장바구니에서 원하는 상품을 삭제할 수 있다.
  - [ ] 최근 본 상품이 있는 경우 상품 목록 상단에서 10개까지 확인할 수 있다.
- [x] 툴바를 추가한다.
  - [x] 상품 목록 화면에서 장바구니 버튼을 누르면 장바구니 화면으로 이동한다.
  - [x] 장바구니 화면에서 뒤로가기 버튼을 누르면 상품 목록 화면으로 이동한다.
  - [x] 제품 상세 화면에서 닫기 버튼을 누르면 상품 목록 화면으로 이동한다.
- [ ] 앱이 종료돼도 최근 본 상품 목록과 장바구니 데이터는 유지돼야 한다.

## Step2
- [ ] 목록 뷰에 데이터 로딩 전략을 적용한다.
  - [ ] 상품 목록에서 더보기 버튼을 눌러 추가 로드할 수 있다. (20개 기준)
  - [ ] 장바구니 목록은 페이지네이션이 되어야 한다. (5개 기준)
