## 🔗 배포 링크

https://rolling-tau.vercel.app/


## 🛠 사용 기술

<div align=center> 
  <img src="https://img.shields.io/badge/react-61DAFB?style=for-the-badge&logo=react&logoColor=black">
  <img src="https://img.shields.io/badge/vite-9135FF?style=for-the-badge&logo=vite&logoColor=white">
  <img src="https://img.shields.io/badge/styledcomponents-DB7093?style=for-the-badge&logo=styledcomponents&logoColor=white">
  <img src="https://img.shields.io/badge/axios-5A29E4?style=for-the-badge&logo=axios&logoColor=white">
  <img src="https://img.shields.io/badge/eslint-4B32C3?style=for-the-badge&logo=eslint&logoColor=white">
  <img src="https://img.shields.io/badge/prettier-F7B93E?style=for-the-badge&logo=prettier&logoColor=black">
</div>


## 📄 개발 내용

1.  리스트 정렬 로직 구현 (Client-side Sorting)
  상황: 백엔드 API에서 인기순/최신순 정렬 필터를 제공하지 않음.
  해결: 전체 데이터를 Fetch한 후, 상위 Wrapper 컴포넌트에서 정렬 로직을 처리하여 카드 리스트 컴포넌트로 전달하는 방식으로 구현.

2. 이미지 로딩 및 렌더링 최적화
  상황: 외부 이미지 API 서버의 응답 속도 저하로 인해 초기 렌더링 시 사용자 경험 저하.
  해결: 메모이제이션(Memoization): 불필요한 재렌더링을 방지하여 연산 비용 최적화.
        캐싱 전략: 동일한 이미지 URL 요청 시 브라우저 캐시를 활용하도록 유도하여 재방문 및 탭 전환 시 로딩 속도 개선.

3. Styled-Components를 활용한 유지보수성 향상
  컴포넌트 단위로 스타일을 관리하여 스타일 충돌을 방지하고 코드 추적성 확보.
  CSS-in-JS 방식을 통해 컴포넌트 구조와 스타일 간의 연관성을 명확히 하여 코드 가독성 증대.

4. 반응형 웹 디자인 구현
  Media Query를 활용하여 데스크탑, 태블릿, 모바일 전 기기에 최적화된 레이아웃 제공.

5. 사용자 이탈 방지를 위한 커스텀 404 페이지 구현
