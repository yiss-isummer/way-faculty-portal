# WAY Faculty Portal

2026-2027 Winter Abroad at Yonsei (WAY) 교원 포털 프론트엔드.

- 하계(YISS) 포털 `index.html` 에서 파생. 화면 구조는 동일하고 **API 엔드포인트와 프로그램 표기만** 다르다.
- 백엔드는 별도 Apps Script 프로젝트(`1iU3kOOoI1bUVBTAB_TyvPn78fqJ6yjJLONKC__htu3OIBnIswhgtljW6`).
  교원 명단·급여·재임용 시트가 하계와 완전히 분리돼 있다. 계약 시트만 공용(Q열 PROGRAM 으로 구분).

## 배포
GitHub Pages (main 브랜치 루트).

## 백엔드 변경 시
Apps Script 를 재배포하면 `index.html` 의 `API_URL`(25행)도 새 배포 URL 로 바꿔야 한다.
현재: `AKfycbz6UPrdXAZlEbUCUHXlE-8BDFNufruftlrx_MAuvfI7wezGjW4-AtPf_k1FuEgHv1wX` (@4)

## 하계와 다른 점
| | 하계 | 동계 |
|---|---|---|
| 제목·머리말 | YISS Faculty Portal / Yonsei International Summer School | WAY Faculty Portal / Winter Abroad at Yonsei |
| 기본 라벨 | 2026 YISS | 2026-2027 WAY |
| 숙소·항공료 | 있음 | **없음** (백엔드에서 꺼짐) |
| 재임용 | 외부 웹앱 링크 | 포털 내 업로드 |
