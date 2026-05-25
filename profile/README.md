<img width="1919" height="1073" alt="image" src="https://github.com/user-attachments/assets/9df647a9-3f04-4623-a821-d0c67111dc8b" /># Festi

Festi는 대학 축제 운영을 위한 통합 플랫폼입니다.

축제 방문자는 부스 위치, 운영 정보, 메뉴, 웨이팅 현황을 한 곳에서 확인하고,
부스 관리자는 부스 정보와 메뉴, 웨이팅을 직접 운영할 수 있습니다.
축제 총 관리자는 부스 배치, 푸드트럭, 신청 내역, 타임테이블, 공지사항을 관리합니다.

## Projects

| Repository | Description |
| --- | --- |
| `Festi-frontend` | 사용자, 부스 관리자, 축제 관리자용 웹/PWA 프론트엔드 |
| `Festi-backend` | Festi API 서버 |

## Features

### For Visitors

- 축제 배치도 기반 부스 탐색
- 주간 부스, 야간 부스, 푸드트럭 목록 확인
- 부스 상세 정보, 운영 시간, 메뉴 확인
- 야간 부스 웨이팅 등록 및 상태 확인
- 현재 빠르게 입장 가능한 부스 추천

### For Booth Managers

- 부스 관리자 회원가입 및 로그인
- 부스 정보, 이미지, 운영 시간 관리
- 메뉴 등록, 수정, 삭제 및 품절 처리
- 웨이팅 오픈/마감 및 호출 관리

### For Festival Admins

- 축제 기본 정보 관리
- 부스 배치 및 위치 관리
- 푸드트럭 관리
- 부스 신청 승인/반려
- 공연 타임테이블 및 공지사항 관리

## Tech Stack

| Area | Stack |
| --- | --- |
| Frontend | React, TypeScript, Vite, TailwindCSS |
| State | TanStack Query, Zustand |
| Routing | React Router |
| API | Axios |
| App | PWA |

## Goal

Festi는 축제 현장의 탐색, 대기, 운영 흐름을 더 단순하게 만드는 것을 목표로 합니다.
방문자는 필요한 정보를 빠르게 찾고, 운영자는 반복적인 현장 업무를 효율적으로 처리할 수 있도록 돕습니다.
