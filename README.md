# 수술 전후 처치 대시보드 (Perioperative Care Console)

복벽탈장 및 외과 수술환자의 주술기(perioperative) 위험 평가 · 조기 인지 · 처치 결정을 병상 옆에서 바로 쓰기 위한 임상 의사결정 지원 도구 모음입니다.

**🔗 https://missurgeon.github.io/**

## 구성

| 대시보드 | 파일 | 내용 |
|---|---|---|
| 복벽탈장(LOD) 수술 주술기 대시보드 | [`lod-perioperative.html`](lod-perioperative.html) | 적용 대상 판정, 동반질환별 맞춤 권고, 수술 전 체크리스트, 인수인계, POD 0–3 모니터링, 에스컬레이션 트리거, NEWS2 계산기, IAP 해석기, 감별진단 |
| 병동 수술전후 처치 대시보드 | [`ward-perioperative.html`](ward-perioperative.html) | 환자 위험도 입력, 본원 보정 합병증 위험도, STOP-BANG, Caprini VTE, 수술군별 baseline 재보정, 합병증별 대처 실무지침 |
| Foley Catheter Decision Support | [`foley-decision-support.html`](foley-decision-support.html) | 환자·해부·술기·주술기 4축 기반 도뇨관 삽입/제거 판단, 선택적 삽입(in-and-out) 대안 |

## 기술 사항

- 각 파일은 **단일 HTML 자체완결형(self-contained)** 문서입니다. 빌드 과정이 없습니다.
- 모든 계산과 입력은 **사용자 브라우저 안에서만** 실행됩니다. 서버로 전송되는 환자 데이터는 없습니다.
- 모바일 · 태블릿 반응형. 휴대폰에서 "홈 화면에 추가"하면 앱처럼 사용할 수 있습니다.

## 수정 방법

각 HTML 파일을 직접 편집한 뒤 `main` 브랜치에 커밋하면 1–2분 내에 사이트에 반영됩니다.

## ⚠ 면책

본 도구는 임상 의사결정을 **보조**하기 위한 참고 자료이며, 담당 의료진의 판단을 대체하지 않습니다. 기관별 프로토콜·약제 정책이 다를 수 있으므로 본원 지침에 맞추어 확인 후 사용하십시오. 환자 식별 정보는 입력하지 마십시오.

---

Ha Tae-kyung, MD · Department of Surgery, Hanyang University Hospital
Robotic Abdominal Wall Hernia Surgery
