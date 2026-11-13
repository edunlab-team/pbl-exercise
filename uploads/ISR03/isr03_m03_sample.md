# [ISR03 - 미션 03] 드론 통상 비행 패턴 정의 및 규칙 기반 이상 비행(급선회·호버링) 탐지 Baseline 구현

> **보안 및 활용 주의**: 본 자료는 교육용 가상 데이터(`isr03_m03_dataset.json`)만을 다룹니다. 실제 부대명, 좌표, 장비 제원 등 군사 비밀은 절대 입력하지 마세요.

## 1. 실습 준비물
- 실습 노트북: `isr03_m03_student.ipynb` (정답 참고: `isr03_m03_solution.ipynb`)
- 가상 데이터셋: `isr03_m03_dataset.json`

## 2. 필수 산출물
- `src/models/isr03_baseline_model.py (필수)`
- `기본 추론 결과 보고서 (필수)`

## 3. 단계별 수행 및 검증 가이드
### Step 1. M3 코드를 실행해 통상 비행 기준과 기본 데이터셋 정확도를 확인한다.
- 점검 포인트: `isr03_m03_student.ipynb` 미션 03 셀을 실행해 출력 로그와 `isr03_m03_dataset.json` 기준값을 대조하세요.

### Step 2. 유형별 탐지율 표에서 측량(survey) 비행이 오탐되는 이유를 적는다.
- 점검 포인트: `isr03_m03_student.ipynb` 미션 03 셀을 실행해 출력 로그와 `isr03_m03_dataset.json` 기준값을 대조하세요.

### Step 3. 선회율 임계값 표에서 정확도와 오탐이 바뀌는 구간을 찾는다.
- 점검 포인트: `isr03_m03_student.ipynb` 미션 03 셀을 실행해 출력 로그와 `isr03_m03_dataset.json` 기준값을 대조하세요.

### Step 4. 복합 이상 5종 탐지율이 낮은 이유를 규칙의 한계로 설명한다.
- 점검 포인트: `isr03_m03_student.ipynb` 미션 03 셀을 실행해 출력 로그와 `isr03_m03_dataset.json` 기준값을 대조하세요.

### Step 5. 도전 과제 및 파라미터 튜닝 최적화
- 점검 포인트: `isr03_m03_student.ipynb` 미션 03 셀을 실행해 출력 로그와 `isr03_m03_dataset.json` 기준값을 대조하세요.
