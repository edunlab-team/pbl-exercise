# [ISR03 - 미션 04] 비행 패턴 클러스터링 및 머신러닝 기반 은밀 침투 드론 이상 궤적 탐지 모델 고도화

> **보안 및 활용 주의**: 본 자료는 교육용 가상 데이터(`isr03_m04_dataset.json`)만을 다룹니다. 실제 부대명, 좌표, 장비 제원 등 군사 비밀은 절대 입력하지 마세요.

## 1. 실습 준비물
- 실습 노트북: `isr03_m04_student.ipynb` (정답 참고: `isr03_m04_solution.ipynb`)
- 가상 데이터셋: `isr03_m04_dataset.json`

## 2. 필수 산출물
- `src/models/isr03_advanced_detector.py (필수)`
- `예외 탐지 테스트 결과 (필수)`

## 3. 단계별 수행 및 검증 가이드
### Step 1. M4 코드를 실행해 규칙·ML·규칙+ML의 재현율과 오경보율을 비교한다.
- 점검 포인트: `isr03_m04_student.ipynb` 미션 04 셀을 실행해 출력 로그와 `isr03_m04_dataset.json` 기준값을 대조하세요.

### Step 2. 시나리오 10종별 재현율 표에서 규칙이 놓친 유형을 ML이 잡았는지 확인한다.
- 점검 포인트: `isr03_m04_student.ipynb` 미션 04 셀을 실행해 출력 로그와 `isr03_m04_dataset.json` 기준값을 대조하세요.

### Step 3. 정상 비행 오경보의 원인 특징(z값)을 보고 오경보 유발 패턴을 정리한다.
- 점검 포인트: `isr03_m04_student.ipynb` 미션 04 셀을 실행해 출력 로그와 `isr03_m04_dataset.json` 기준값을 대조하세요.

### Step 4. 도전 과제 및 파라미터 튜닝 최적화
- 점검 포인트: `isr03_m04_student.ipynb` 미션 04 셀을 실행해 출력 로그와 `isr03_m04_dataset.json` 기준값을 대조하세요.
