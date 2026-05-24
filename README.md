# IT Certification Difficulty Index

국내외 IT, 보안, 클라우드, 데이터, AI, 프로젝트관리 자격증을 **자격증 취득 난이도** 기준으로 H1~H10 등급으로 분류한 저장소입니다.

## 목적

- 자격증별 취득 난이도 비교
- 개인 학습 로드맵 설계
- 채용 및 역량 평가 참고
- 직무별 요구 자격증 매트릭스 작성

## 난이도 체계

| 등급 | 점수 | 대표 학습시간 | 설명 |
|---|---:|---:|---|
| H1 | 1 | 40h | 입문 |
| H2 | 2 | 80h | 기초 |
| H3 | 3 | 130h | 초중급 |
| H4 | 4 | 180h | 중급 |
| H5 | 5 | 260h | 중상급 |
| H6 | 6 | 400h | 상급 |
| H7 | 7 | 550h | 고급 |
| H8 | 8 | 700h | 전문가 |
| H9 | 9 | 1,000h | 최상급 |
| H10 | 10 | 1,200h+ | 최고난도 |

## 주요 자격증 요약

| 자격증 | 분야 | 대표 학습시간 | 난이도 |
|---|---|---:|---:|
| AWS Cloud Practitioner | Cloud | 40h | H1 |
| AWS AI Practitioner | Data / AI | 50h | H1 |
| 리눅스마스터 2급 | Linux | 70h | H2 |
| SQLD | Database | 80h | H2 |
| 정보처리기사 | Software Engineering | 130h | H3 |
| CPPG | Privacy / GRC | 130h | H3 |
| 빅데이터분석기사 | Data / AI | 180h | H4 |
| Azure Administrator AZ-104 | Cloud | 180h | H4 |
| AWS Data Engineer Associate | Data / AI | 180h | H4 |
| 정보보안기사 | Security | 260h | H5 |
| PMP | Project Management | 260h | H5 |
| CISA | IT Audit / GRC | 280h | H5 |
| CKA | Kubernetes | 260h | H5 |
| AWS Security Specialty | Security | 400h | H6 |
| CISSP | Security | 550h | H7 |
| SQLP | Database / Tuning | 550h | H7 |
| ADP | Data Analysis | 700h | H8 |
| ISMS-P 인증심사원 | GRC | 550h | H7 |
| 정보관리기술사 | Architecture | 1,200h | H10 |

## 문서

- [난이도 산정 기준](docs/methodology.md)
- [난이도별 자격증 목록](docs/by-difficulty.md)
- [분야별 자격증 목록](docs/by-domain.md)
- [국내 자격증](docs/domestic.md)
- [해외 자격증](docs/international.md)
- [폐지 또는 대체 자격증](docs/retired-or-replaced.md)

## 데이터

원본 데이터는 `data/certifications.yml`에 관리합니다.

```text
data/certifications.yml       # 자격증 원본 데이터
data/difficulty-levels.yml    # 난이도 정의
```

## 주의사항

이 저장소의 난이도는 공식 난이도가 아닙니다. IT 기본지식이 있는 응시자의 순공부시간, 시험범위, 실기 여부, 경력요건, 시나리오형 문제 비중, 공개 합격률 또는 체감 취득 난이도를 종합한 추정값입니다.

각 자격증은 H1~H10 중 하나의 난이도만 가집니다.
