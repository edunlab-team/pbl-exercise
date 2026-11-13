# [ISR03 - 미션 09] AAR 기반 비행 이상 오탐·미탐 사례 분석 및 이상 탐지 임계치 최적화

> **보안 및 활용 주의**: 본 자료는 교육용 가상 데이터(`isr03_m09_dataset.json`)만을 다룹니다. 실제 부대명, 좌표, 장비 제원 등 군사 비밀은 절대 입력하지 마세요.

## 1. 실습 준비물
- 실습 노트북: `isr03_m09_student.ipynb` (정답 참고: `isr03_m09_solution.ipynb`)
- 가상 데이터셋: `isr03_m09_dataset.json`

## 2. 필수 산출물
- `docs/isr03_aar_report.md (필수)`
- `configs/isr03_tuned_params.yaml (필수)`

## 3. 단계별 수행 및 검증 가이드
### Step 1. M9 코드를 실행해 초기 설정의 AAR 일지(오탐 원인별 건수)를 확인한다.
- 점검 포인트: `isr03_m09_student.ipynb` 미션 09 셀을 실행해 출력 로그와 `isr03_m09_dataset.json` 기준값을 대조하세요.

### Step 2. 평시 학습 자료 보강(측량·강풍 로그) 후 격자 탐색 상위 조합과 재보정값을 확인한다.
- 점검 포인트: `isr03_m09_student.ipynb` 미션 09 셀을 실행해 출력 로그와 `isr03_m09_dataset.json` 기준값을 대조하세요.

### Step 3. 재보정 전후 정확도와 회귀 시험 결과, 반복 오류를 비교한다.
- 점검 포인트: `isr03_m09_student.ipynb` 미션 09 셀을 실행해 출력 로그와 `isr03_m09_dataset.json` 기준값을 대조하세요.

### Step 4. 도전 과제 및 파라미터 튜닝 최적화
- 점검 포인트: `isr03_m09_student.ipynb` 미션 09 셀을 실행해 출력 로그와 `isr03_m09_dataset.json` 기준값을 대조하세요.
