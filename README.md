# MORU 피부과 랜딩페이지

피부과 진료 안내와 상담 문의 화면을 담은 반응형 정적 웹사이트입니다. 별도의 패키지 설치나 빌드 과정 없이 `dist/index.html`을 정적 웹 서버로 실행할 수 있습니다.

## 실행 방법

Python 3가 설치되어 있다면 프로젝트 폴더에서 다음 명령을 실행하세요.

```powershell
py -m http.server 8000 --directory dist
```

macOS 또는 Linux에서는 다음과 같이 실행할 수 있습니다.

```sh
python3 -m http.server 8000 --directory dist
```

브라우저에서 `http://localhost:8000`을 여세요. 웹 글꼴과 사진은 Google Fonts와 Unsplash에서 불러오므로 인터넷 연결이 필요합니다.

## 구성

- `dist/index.html` — 페이지 마크업, 스타일, 모바일 메뉴와 FAQ 동작
- `.openai/hosting.json` — Sites 프로젝트 식별자와 정적 배포 설정

## 수정 전 확인

페이지의 MORU 브랜드와 진료 안내 문구는 편집 가능한 시안입니다. 실제 병원명, 진료 정보, 주소, 운영 시간과 연락처를 확인해 반영하세요. 상담 양식은 시연용이며 입력 내용을 전송하거나 저장하지 않습니다.
