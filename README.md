# ADNI Data Selection Guide

## 🌐 Website

[**Open the ADNI Data Selection Guide →**](https://idoji.github.io/ADNI-data-selection/)

ADNI의 임상 방문 이력, MRI 후보 스캔, QC 정보, T1/rs-fMRI 페어링 및 전처리 절차를 연구실 구성원과 공유하기 위한 정적 웹사이트입니다.

## Website structure

- Clinical visit history
- MRI candidate scans
- Quality control
- T1–rs-fMRI pairing
- Download and integrity checks
- BIDS organization
- rs-fMRI and T1 preprocessing
- Reproducibility and data security

## Local preview

macOS에서 저장소 폴더를 열고 다음 명령을 실행합니다.

```bash
python3 -m http.server 8000
```

브라우저에서 `http://localhost:8000`을 엽니다.

## GitHub Pages

GitHub 저장소에서 다음 순서로 활성화합니다.

1. `Settings`
2. `Pages`
3. `Build and deployment`
4. Source를 `Deploy from a branch`로 선택
5. Branch를 `main`, folder를 `/ (root)`로 선택
6. `Save`

배포 주소:

[https://idoji.github.io/ADNI-data-selection/](https://idoji.github.io/ADNI-data-selection/)

## Security

이 저장소는 공개 저장소입니다. 다음 자료를 커밋하지 마세요.

- ADNI 원본 영상 또는 임상 원자료
- RID와 민감정보가 함께 포함된 표
- 접근 토큰, 로그인 정보, cookie, 다운로드 URL
- 개인 또는 기관 내부 서버 경로

## Editing

- 본문: `index.html`
- 디자인: `assets/style.css`
- 메뉴 및 화면 동작: `assets/app.js`
