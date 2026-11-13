# TRN01 산출물 디렉토리 및 제출 안내 가이드

본 프로젝트(`TRN01`: 드론 시뮬레이터 비행로그 기반 숙련도 분석기)는 10개 미션을 수행하며 아래와 같은 표준 프로젝트 폴더 구조에 산출물(`deliverables`)을 저장·관리합니다.

## 1. 권장 디렉토리 구조

```text
TRN01_project/
├── README.md                                  # 미션10: 프로젝트 실행·배포 안내서
├── configs/
│   └── trn01_tuned_params.yaml                # 미션9: AAR 재튜닝 파라미터 설정
├── data/
│   ├── schema/
│   │   └── trn01_input_schema.json            # 미션1: 비행로그 입력 JSON 스키마
│   └── processed/
│       ├── trn01_m02_sample_raw.json          # 미션2: 전처리 전 원시 샘플
│       └── trn01_m02_sample_clean.json        # 미션2: 전처리 후 정제 샘플
├── docs/
│   ├── trn01_data_spec.md                     # 미션1: 데이터 명세서
│   ├── trn01_m03_baseline_report.md           # 미션3: Baseline 추론 결과 보고서
│   ├── trn01_m04_exception_report.md          # 미션4: 예외·위험 조작 탐지 테스트 결과
│   ├── trn01_hitl_guide.md                    # 미션7: HITL 평가 운영 가이드
│   ├── trn01_m08_stress_report.md             # 미션8: 스트레스 테스트 분석 보고서
│   ├── trn01_aar_report.md                    # 미션9: AAR 편차 분석 및 재튜닝 보고서
│   └── trn01_final_report.md                  # 미션10: 교육훈련 브리핑 최종 보고서
├── src/
│   ├── main_trn01.py                          # 미션10: 전체 파이프라인 통합 진입점
│   ├── preprocess/
│   │   └── trn01_preprocessor.py              # 미션2: 시계열 정제·필터링 모듈
│   ├── models/
│   │   ├── trn01_baseline_model.py            # 미션3: Baseline 채점 알고리즘
│   │   └── trn01_advanced_detector.py         # 미션4: 정밀 평가·위험 탐지 엔진
│   ├── verification/
│   │   └── trn01_confidence_engine.py         # 미션5: 조작 습관·신뢰도 등급 모듈
│   ├── ui/
│   │   └── trn01_dashboard.py                 # 미션6: 3D 궤적 재생 대시보드
│   └── hitl/
│       └── trn01_approval_workflow.py         # 미션7: 교관 HITL 승인 워크플로우
└── tests/
    └── trn01_stress_test.py                   # 미션8: 대량 배치 스트레스 테스트
```

## 2. Google Colab / 로컬 환경 폴더 생성 방법

노트북(`TRN01_student.ipynb` / `TRN01_solution.ipynb`)에서 코드를 실행하기 전 또는 저장 시 아래 명령으로 디렉토리를 자동 생성할 수 있습니다.

```python
import os
for d in [
    "configs", "data/schema", "data/processed", "docs",
    "src/preprocess", "src/models", "src/verification", "src/ui", "src/hitl", "tests"
]:
    os.makedirs(d, exist_ok=True)
```

## 3. 산출물 작성 및 제출 유의사항
- **가명화 원칙**: 모든 JSON/MD/코드 산출물에는 가명 조종자 ID(`P001~`)만 사용하며 실제 훈련생 성명·군번·부대명은 포함하지 않습니다.
- **HITL 원칙**: 평가 보고서 및 브리핑 문서에는 AI 점수가 교관 판단 보조 지표임을 명시하고, 최종 등급·재교육 결정은 교관이 근거를 기록해 확정합니다.
