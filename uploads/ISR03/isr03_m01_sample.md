# [ISR03 - 미션 01] 상용 및 군용 드론 비행로그(GPS, 속도, 고도, RC제어) 데이터 스키마 및 수집 환경 분석

> **보안 및 활용 주의**: 본 자료는 교육용 가상 데이터(`isr03_m01_dataset.json`)만을 다룹니다. 실제 부대명, 좌표, 장비 제원 등 군사 비밀은 절대 입력하지 마세요.

## 1. 실습 준비물
- 실습 노트북: `isr03_m01_student.ipynb` (정답 참고: `isr03_m01_solution.ipynb`)
- 가상 데이터셋: `isr03_m01_dataset.json`

## 2. 필수 산출물
- `data/schema/isr03_input_schema.json (필수)`
- `docs/isr03_data_spec.md (필수)`

## 3. 단계별 수행 및 검증 가이드
### Step 1. M1 코드를 실행해 정상 샘플 20건의 검증 결과를 확인한다.
- 점검 포인트: `isr03_m01_student.ipynb` 미션 01 셀을 실행해 출력 로그와 `isr03_m01_dataset.json` 기준값을 대조하세요.

### Step 2. 오류 주입 결과 5종과 추가로 잡힌 해시 불일치가 어떤 규칙에 걸렸는지 표로 정리한다.
- 점검 포인트: `isr03_m01_student.ipynb` 미션 01 셀을 실행해 출력 로그와 `isr03_m01_dataset.json` 기준값을 대조하세요.

### Step 3. attribution.status가 'unassessed'만 허용되는 이유(수집 단계 단정...
- 점검 포인트: `isr03_m01_student.ipynb` 미션 01 셀을 실행해 출력 로그와 `isr03_m01_dataset.json` 기준값을 대조하세요.

### Step 4. 도전 과제 및 파라미터 튜닝 최적화
- 점검 포인트: `isr03_m01_student.ipynb` 미션 01 셀을 실행해 출력 로그와 `isr03_m01_dataset.json` 기준값을 대조하세요.
