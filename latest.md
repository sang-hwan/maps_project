# 📌 현실적이고 구체적인 단계별 실행 계획 (최신본)

> **마지막 업데이트:** 2025-05-23
> **현재 진행 단계:** 🔲 2단계 (예정)

| 단계 | 핵심 작업                              | 상태     |
| ---- | -------------------------------------- | -------- |
| 1    | API 키 설정 및 환경 구성               | ✅ 완료 |
| 2    | 플랫폼별 장소 데이터 수집 및 JSON 저장 | 🔲 미완료 |
| 3    | 데이터 통합 및 운영 상태 확인          | 🔲 미완료 |
| 4    | PostgreSQL DB 구축 및 데이터 저장      | 🔲 미완료 |
| 5    | 지도 구축 및 인터랙티브 UI 개발        | 🔲 미완료 |
| 6    | 장소 방문 및 콘텐츠 제작               | 🔲 미완료 |
| 7    | 콘텐츠 관리 및 포트폴리오 구축         | 🔲 미완료 |
| 8    | 포트폴리오 수익화 및 확장              | 🔲 미완료 |

---

## ✅ **단계별 세부 작업 내용**

### ✅ 1단계: API 키 설정 및 환경 구성 (완료)

* Google Maps, 네이버 지도, 카카오맵 API 키 발급 완료
* `.env` 파일 설정 완료

### ✅ 2단계: 플랫폼별 장소 데이터 수집 및 JSON 저장(예정)

* 카카오, 네이버, 구글 맵 API를 활용한 대전 내 카페, 바, 동전 노래방의 상호명, 주소, 위도, 경도 데이터 수집
* 플랫폼별로 구분하여 각각 JSON 파일로 저장

### ✅ 3단계: 데이터 통합 및 운영 상태 확인

* 플랫폼별 JSON 데이터를 하나의 JSON 파일로 통합
* 중복 데이터 제거
* 각 장소의 운영 여부(운영 중/폐업) 판단 로직 도입 및 적용
* 운영 중인 장소만을 최종 JSON 파일로 저장

### ✅ 4단계: PostgreSQL DB 구축 및 데이터 저장

* PostgreSQL 데이터베이스 환경 구축
* 최종 JSON 데이터를 데이터베이스에 저장 및 관리

### ✅ 5단계: 지도 구축 및 인터랙티브 UI 개발

* 대전 전체 지도, 구별 지도, 동별 지도 확보 및 병합
* 지도에 구별 경계선 표시, 사용자가 구를 클릭 시 동별 경계선 표시
* 지도 위 구와 동의 이름 명확히 표시
* 각 동 지도 위에 장소의 마커 표시(위도, 경도 기반)
* 사용자가 동을 클릭 시 화면 좌우측에 가게 목록 표시

  * 페이징 처리 및 카테고리(카페, 바, 동전 노래방) 필터링 기능
  * 리스트 항목 또는 마커 클릭 시 해당 가게의 상호명과 상세 주소 표시

### ✅ 6단계: 장소 방문 및 콘텐츠 제작 (지속적, 주 1\~3회)

* 카페, 바, 동전 노래방 방문을 통한 콘텐츠 제작
* 리뷰, 사진, 짧은 영상 제작

### ✅ 7단계: 콘텐츠 관리 및 포트폴리오 구축 (지속적, 주 단위 업데이트)

* 블로그, 유튜브, 인스타그램 등 SNS 콘텐츠 업로드
* 콘텐츠 분석 및 최적화

### ✅ 8단계: 포트폴리오 수익화 및 확장 (장기적 목표)

* 광고 제휴 및 협찬 기회 확보
* 개인 브랜드 구축 및 확장

---

## 🥅 **최종 목표**

> 장소 데이터 기반의 지속 가능한 콘텐츠 제작 및 개인 브랜드 성장

---

## 🔖 **상태값 설명**

* 🔲 **미완료** : 아직 시작하지 않은 작업
* 🔶 **진행중** : 현재 진행 중인 작업
* ✅ **완료** : 작업이 완료됨
* 🔵 **수정중** : 작업 내용 수정 중
