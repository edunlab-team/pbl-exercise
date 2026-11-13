# [ISR03 - 미션 07] 운용 주체 최종 판정을 위한 정보분석관 심층 검토(HITL) 워크플로우 설계

> **보안 및 활용 주의**: 본 자료는 교육용 가상 데이터(`isr03_m07_dataset.json`)만을 다룹니다. 실제 부대명, 좌표, 장비 제원 등 군사 비밀은 절대 입력하지 마세요.

## 1. 실습 준비물
- 실습 노트북: `isr03_m07_student.ipynb` (정답 참고: `isr03_m07_solution.ipynb`)
- 가상 데이터셋: `isr03_m07_dataset.json`

## 2. 필수 산출물
- `src/hitl/isr03_approval_workflow.py (필수)`
- `docs/isr03_hitl_guide.md (필수)`

## 3. 단계별 수행 및 검증 가이드
### Step 1. M7 코드를 실행해 검토 순서와 차단된 규칙 위반 사례를 확인한다.
- 점검 포인트: `isr03_m07_student.ipynb` 미션 07 셀을 실행해 출력 로그와 `isr03_m07_dataset.json` 기준값을 대조하세요.

### Step 2. 무결성 검증 실패(FL0112)가 채택이 아닌 보류로 처리된 흐름을 확인한다.
- 점검 포인트: `isr03_m07_student.ipynb` 미션 07 셀을 실행해 출력 로그와 `isr03_m07_dataset.json` 기준값을 대조하세요.

### Step 3. 2인 교차 검토가 동작하는지, 보류 기한 초과 시 상신되는지 확인한다.
- 점검 포인트: `isr03_m07_student.ipynb` 미션 07 셀을 실행해 출력 로그와 `isr03_m07_dataset.json` 기준값을 대조하세요.

### Step 4. 감사 로그 변조 후 검증 결과가 어떻게 바뀌는지 본다.
- 점검 포인트: `isr03_m07_student.ipynb` 미션 07 셀을 실행해 출력 로그와 `isr03_m07_dataset.json` 기준값을 대조하세요.

### Step 5. 도전 과제 및 파라미터 튜닝 최적화
- 점검 포인트: `isr03_m07_student.ipynb` 미션 07 셀을 실행해 출력 로그와 `isr03_m07_dataset.json` 기준값을 대조하세요.
