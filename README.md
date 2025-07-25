# 👠 패션 쇼핑몰 상품 목록 페이지 (모바일)

## 🧰 사용 기술
- React (프론트엔드 UI 구현)
- CSS 또는 styled-components, Tailwind CSS (스타일링)
- 상태 관리: Redux 또는 Context API
- (선택적으로 Firebase, React Query 등 추가 가능)

## 👩‍💻 문서 작성자
- 박한비

## 📝 고객 요구사항 요약
- **타겟 고객**: 2030 패션 소비자
- **주력 상품**: 신발
- **이용 환경**: 모바일 중심, 웹 브라우저 대응 필요
- **요구 사항**:
  - 상품 이미지가 눈에 잘 띄도록 배치
  - 모바일 화면에 최적화된 반응형 UI
  - 상품을 장바구니에 추가 시 개수가 실시간 표시되어야 함
  - 프로젝트 완료 후 2주 이내 테스트용 공개 URL 제공

## 📋 구현 기능 목록

### 🔹 상품 리스트
- `<ProductList />` 컴포넌트 사용
- 2열(2컬럼) 레이아웃으로 상품 정렬
- 상품 이미지 비율 유지
- 각 상품에 이름과 가격 표시

### 🔹 장바구니 기능
- 상품 추가 시 장바구니 아이콘 옆에 개수 표시
- 개수는 실시간으로 반영됨
- Redux 또는 Context API를 활용한 상태 관리

### 🔹 반응형 UI
- 모바일 환경에 최적화된 디자인
- 웹 브라우저 환경에서도 문제없이 동작

### 🔹 테스트용 배포 URL
- 개발 완료 후 2주 내 테스트용 URL 제공 (예: Netlify, Vercel 등)
- QA 테스트 및 고객 피드백 수집 목적
