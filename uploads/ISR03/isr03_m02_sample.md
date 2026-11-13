# [ISR03 - 미션 02] 비행로그 내 GPS 스푸핑 왜곡값 보정 및 시계열 텔레메트리 전처리 모듈 구현

> **보안 및 활용 주의**: 본 자료는 교육용 가상 데이터(`isr03_m02_dataset.json`)만을 다룹니다. 실제 부대명, 좌표, 장비 제원 등 군사 비밀은 절대 입력하지 마세요.

## 1. 실습 준비물
- 실습 노트북: `isr03_m02_student.ipynb` (정답 참고: `isr03_m02_solution.ipynb`)
- 가상 데이터셋: `isr03_m02_dataset.json`

## 2. 필수 산출물
- `src/preprocess/isr03_preprocessor.py (필수)`
- `전처리 전후 데이터셋 (필수)`

## 3. 단계별 수행 및 검증 가이드
### Step 1. M2 코드를 실행해 처리 속도, 전처리 오류율, 보정 전후 위치 오차를 확인한다.
- 점검 포인트: `isr03_m02_student.ipynb` 미션 02 셀을 실행해 출력 로그와 `isr03_m02_dataset.json` 기준값을 대조하세요.

### Step 2. 스푸핑 구간을 추측항법으로 대체하는 원리를 그림(빨간 점 대 파란 선)으로 설명한다.
- 점검 포인트: `isr03_m02_student.ipynb` 미션 02 셀을 실행해 출력 로그와 `isr03_m02_dataset.json` 기준값을 대조하세요.

### Step 3. 기상별 임계값 표에서 강우·강풍 조건의 오표시율이 줄어든 이유를 정리한다.
- 점검 포인트: `isr03_m02_student.ipynb` 미션 02 셀을 실행해 출력 로그와 `isr03_m02_dataset.json` 기준값을 대조하세요.

### Step 4. 단위 테스트 5종의 통과 여부를 기록한다.
- 점검 포인트: `isr03_m02_student.ipynb` 미션 02 셀을 실행해 출력 로그와 `isr03_m02_dataset.json` 기준값을 대조하세요.

### Step 5. 도전 과제 및 파라미터 튜닝 최적화
- 점검 포인트: `isr03_m02_student.ipynb` 미션 02 셀을 실행해 출력 로그와 `isr03_m02_dataset.json` 기준값을 대조하세요.
