# [ISR03 - 미션 08] 장거리 전술 비행 대량 로그 주입 시뮬레이션 및 이상 탐지 처리 성능 테스트

> **보안 및 활용 주의**: 본 자료는 교육용 가상 데이터(`isr03_m08_dataset.json`)만을 다룹니다. 실제 부대명, 좌표, 장비 제원 등 군사 비밀은 절대 입력하지 마세요.

## 1. 실습 준비물
- 실습 노트북: `isr03_m08_student.ipynb` (정답 참고: `isr03_m08_solution.ipynb`)
- 가상 데이터셋: `isr03_m08_dataset.json`

## 2. 필수 산출물
- `tests/isr03_stress_test.py (필수)`
- `스트레스 테스트 분석 보고서 (필수)`

## 3. 단계별 수행 및 검증 가이드
### Step 1. M8 코드를 실행해 상황별 수신·처리·격리·유실·다운을 확인한다.
- 점검 포인트: `isr03_m08_student.ipynb` 미션 08 셀을 실행해 출력 로그와 `isr03_m08_dataset.json` 기준값을 대조하세요.

### Step 2. 메모리 반복 측정 결과로 누수 여부를 판단한다.
- 점검 포인트: `isr03_m08_student.ipynb` 미션 08 셀을 실행해 출력 로그와 `isr03_m08_dataset.json` 기준값을 대조하세요.

### Step 3. 병목 구간 비율을 보고 우선 최적화할 단계를 정한다.
- 점검 포인트: `isr03_m08_student.ipynb` 미션 08 셀을 실행해 출력 로그와 `isr03_m08_dataset.json` 기준값을 대조하세요.

### Step 4. 처리 예산 부족 시 성능저하 모드(ML 지연처리)가 표시되는지 확인한다.
- 점검 포인트: `isr03_m08_student.ipynb` 미션 08 셀을 실행해 출력 로그와 `isr03_m08_dataset.json` 기준값을 대조하세요.

### Step 5. 도전 과제 및 파라미터 튜닝 최적화
- 점검 포인트: `isr03_m08_student.ipynb` 미션 08 셀을 실행해 출력 로그와 `isr03_m08_dataset.json` 기준값을 대조하세요.
