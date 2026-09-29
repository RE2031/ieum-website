# 자람새 웹사이트 원본 버전 백업 및 복원 안내

이 프로젝트는 모바일 반응형 및 블로그형 메인 개편 작업을 진행하기 전의 원본 상태를 여러 방식으로 완벽하게 보존해 두었습니다. 언제든지 원본 상태를 확인하거나 되돌릴 수 있습니다.

---

## 1. 브라우저에서 바로 원본 버전 열기 (가장 간편한 방법)
웹 브라우저에서 아래 파일로 접속하시면 수정 전의 기존 원본 화면을 그대로 확인하실 수 있습니다.
* **[index-original.html](file:///C:/Users/Jae%20Lee/jaramsae-website/index-original.html)** (기존 PC 중심 레이아웃 원본)

웹사이트 메인 화면의 사이드바/모바일 메뉴에서도 **「↩️ 원래 버전(PC 원본) 보기」** 버튼을 눌러 언제든 이동할 수 있습니다.

---

## 2. 전체 파일 독립 폴더 백업
수정 전의 모든 소스 코드가 별도의 독립된 폴더에 100% 동일하게 백업되어 있습니다.
* **백업 경로:** `C:\Users\Jae Lee\jaramsae-website-original-backup\`

---

## 3. Git을 통한 원본 복원 및 브랜치 전환
Git 저장소에 원본 커밋 시점의 브랜치와 태그가 등록되어 있습니다.

### 원본 버전 브랜치로 전환하기
```bash
git checkout backup-original
```

### 다시 최신 반응형/블로그 버전으로 돌아오기
```bash
git checkout main
```

### 태그로 확인하기
* 태그 이름: `original-version`
```bash
git checkout original-version
```
