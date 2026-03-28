# travelreview

## 1. 프로젝트 개요
- 서비스 명: travelreview(가칭)
- 한 줄 정의: 여행 계획 수립과 실제 방문 리뷰를 하나로 연결하는 사용자 중심 기록 앱
- 타겟 사용자: 꼼꼼한 일정 관리를 선호하며, 광고 없는 실질적인 장소 리뷰를 기록하고 공유하고 싶은 여행자

## 2. 핵심 기능 (MVP)
- 장소 검색 (Search): 네이버 API를 연동하여 장소명, 주소, 카테고리, 사진 정보를 리스트로 확인
- 여행 계획 (Plan): 날짜 및 시간별 일정 생성, 검색한 장소를 내 계획표에 즉시 추가
- 방문 리뷰 (Review): 내 계획표를 기반으로 별점, 사진, 텍스트가 포함된 '내돈내산' 리뷰 작성

## 3. 사용자 시나리오 (User Flow)
- 탐색: 사용자가 검색창에 목적지(예: 부산 해운대)를 입력하고 카테고리별로 장소를 탐색합니다.
- 계획: 마음에 드는 장소를 발견하면 '+' 버튼을 눌러 특정 날짜와 시간(Day 1, 13:00-14:00)의 일정으로 추가합니다.
- 기록: 여행 중 또는 여행 후에 계획표에서 '리뷰 쓰기'를 눌러 사진과 소감을 남깁니다.

## 4. 기술 스택 및 데이터 구조
- 플랫폼: Android & iOS (Cross-platform)
- 개발 환경: Flutter, Dart, Android Studio (Mac M1)
- IDE/도구: Android Studio (with Claude MCP), Figma, GitHub
- 데이터베이스: SQFlite (Local DB)
- 외부 API: Naver Search API, Naver Image API
