# TRN08 산출물 디렉토리 구조 및 저장 안내 가이드

## 1. 작업 디렉토리 구조
`TRN08_student.ipynb`의 **공통 환경 설정(Cell 1)**을 실행하면 현재 작업 경로 아래에 다음 8개 산출물 디렉토리가 자동으로 생성됩니다.

```text
작업폴더/
├── docs/        # 미션 1(기초 평가·훈련 프로파일), 미션 5(교차검증 매트릭스)
├── sop/         # 미션 2(현장 관측 체크리스트·7단계 SOP·요약 카드)
├── scenarios/   # 미션 3(거리별 미디어셋·MSEL 상황 주입 시나리오)
├── logs/        # 미션 4(1차 Dry-run 실행 로그), 미션 7(스트레스 훈련 결과)
├── reports/     # 미션 6(SALUTE·SBAR 인계 프로토콜·브리핑 기록지)
├── aar/         # 미션 8(AAR 회의록·오류 분석 매트릭스)
├── eval/        # 미션 9(재평가 전후 성과 비교표·보수 교육 계획)
└── package/     # 미션 10(최종 표준 훈련 패키지·교관 지침서)
```

> **참고:** 노트북을 사용하지 않고 수동으로 작성하는 경우, 터미널(PowerShell / bash)에서 아래 명령어로 디렉토리를 먼저 생성한 뒤 파일을 저장하세요.
> ```bash
> mkdir -p docs sop scenarios logs reports aar eval package
> ```

---

## 2. 미션별 필수 산출물 및 저장 경로 매핑

| 미션 | 필수 산출물 | 저장 경로 예시 | 비고 |
| --- | --- | --- | --- |
| 미션 1 | `docs/trn08_baseline_assessment.md`, 훈련 프로파일 | `docs/trn08_baseline_assessment.md` | 훈련 프로파일은 동일 문서 내 섹션 또는 `docs/` 하위 저장 |
| 미션 2 | `sop/trn08_field_checklist.md`, SOP 흐름도 | `sop/trn08_field_checklist.md` | 요약 카드(Pocket Guide)·흐름도 함께 보관 |
| 미션 3 | `scenarios/trn08_msel_scenario.json(md)` | `scenarios/trn08_msel_scenario.md` | JSON 또는 Markdown 형식 중 지정 서식 사용 |
| 미션 4 | `logs/trn08_dryrun_execution_log.md`, 작성된 체크리스트 | `logs/trn08_dryrun_execution_log.md` | 초 단위 타임라인·지연시간 기록 포함 |
| 미션 5 | `docs/trn08_cross_verification_sheet.md` | `docs/trn08_cross_verification_sheet.md` | `E1~E12` 판정·정답 대조 결과 포함 |
| 미션 6 | `reports/trn08_handover_protocol.md`, 브리핑 녹취/기록지 | `reports/trn08_handover_protocol.md` | `SALUTE`·`SBAR` 10항목·퀴즈 5문항 기록 |
| 미션 7 | `logs/trn08_stress_drill_results.md` | `logs/trn08_stress_drill_results.md` | `D1~D10` 성공률 및 1·2회차 전환시간 비교 |
| 미션 8 | `aar/trn08_aar_session_minutes.md`, 오류 분석 매트릭스 | `aar/trn08_aar_session_minutes.md` | 팩트체크 기반 4요인 분류 및 SOP 1차 수정안 |
| 미션 9 | `eval/trn08_rerun_performance_comparison.md` | `eval/trn08_rerun_performance_comparison.md` | 미션 4 대비 단축률·감소율 검산 포함 |
| 미션 10 | `package/trn08_standard_training_package.md`, 교관 지침서 | `package/trn08_standard_training_package.md` | 미션 1~9 검증 산출물 통합본 |

---

## 3. 저장 및 제출 전 체크리스트
1. **경로 일치**: 파일명과 상위 디렉토리(`docs/`, `sop/` 등)가 오타 없이 일치하는가?
2. **인코딩**: Markdown(`.md`) 및 JSON(`.json`) 파일은 `UTF-8`로 저장했는가?
3. **보안·HITL 준수**: 실제 부대명·진지 위치·호출부호·실제 드론 제원/주파수가 포함되지 않았는가?
