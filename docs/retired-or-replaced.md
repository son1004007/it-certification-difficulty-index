# 폐지 또는 대체 자격증

신규 취득 후보에서는 제외하거나 우선순위를 낮추는 자격증 목록입니다.

| 자격증 | 상태 | 대체 또는 처리 방향 | 난이도 |
|---|---|---|---:|
| AWS SysOps Administrator Associate | replaced | AWS CloudOps Engineer Associate 기준으로 관리 | H4 |
| TensorFlow Developer Certificate | retired | 신규 취득 후보에서 제외. 과거 이력 비교용으로만 관리 | H4 |

## 관리 기준

- `active`: 현재 유효한 자격증
- `retiring`: 은퇴 예정 자격증
- `retired`: 폐지 또는 응시 종료 자격증
- `replaced`: 후속 시험 또는 대체 자격증이 있는 경우
- `unknown`: 확인 필요

상태값은 `data/certifications.yml`의 `status` 필드로 관리합니다.
