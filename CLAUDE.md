# period-site

## 프로젝트 개요
영화입시 전문 과외 홈페이지. 과외 학생 모집이 목적.
브랜드명: **피리어드 (Period.)**

## 기술 스택
- 순수 HTML/CSS/JavaScript (단일 파일: `index.html`)
- 프레임워크 없음
- GitHub Pages로 배포 (master 브랜치)

## 사이트 구조 (탭 구성)
- **홈** — 히어로, 피리어드 소개, 블로그·유튜브 링크
- **선생님** — 어드쌤(중앙대 연극영화과 수석졸업), 피리쌤(연세대 신방과) 소개
- **수업** — 수업 방식, 수업료 (1회 30만원 / 월 100만원 / 6개월+ 85만원)
- **콘텐츠** — 네이버 블로그, 유튜브 채널 링크
- **후기** — 수강생 후기 (11명 전원 합격)
- **무료상담** — Google Forms 연결

## 주요 외부 링크
- 블로그: https://blog.naver.com/songtorytelling
- 유튜브: https://www.youtube.com/channel/UC6LLKLW14n1foRQ-30JZ2Xg
- 카카오톡 오픈채팅: https://open.kakao.com/me/film_period
- 상담 신청 폼: https://forms.gle/LjpJcbkbh3YR7Zev9

## 디자인 가이드
- 컬러: 화이트 배경, 핑크 포인트 (#F1296C), 라벤더 (#DDCEDD)
- 폰트: 시스템 폰트 (-apple-system, Apple SD Gothic Neo, 맑은 고딕)
- 모바일 우선 설계, 768px 이상에서 데스크탑 레이아웃 적용

## 수정 시 주의사항
- 단일 index.html 파일 안에 HTML/CSS/JS가 모두 포함됨
- 빌드 과정 없음 — 수정 후 바로 push하면 GitHub Pages에 반영
- CSS 변수는 :root에 정의되어 있음 (--pink, --lavender, --mauve 등)
