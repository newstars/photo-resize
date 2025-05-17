# 📸 Photo Layout to PDF

A4 용지 위에 여러 장의 사진을 보기 좋게 배치하여 PDF로 저장할 수 있는 웹 앱입니다.  
**브라우저에서만 동작**하며, 서버 없이 GitHub Pages에서 호스팅됩니다.

🔗 **바로가기**: [https://newstars.github.io/photo-resize/](https://newstars.github.io/photo-resize/)

---

## ✨ 주요 기능

- ✅ **열은 항상 2개 고정**, 행은 자동 증가
- ✅ **사진 비율 유지**, 긴 변(가로 또는 세로)에 맞게 리사이즈
- ✅ **2, 4, 6, 8장 배치 템플릿 지원**
- ✅ **A4 사이즈(794×1123px)** 기준 출력
- ✅ **PDF 미리보기 및 다운로드**
- ✅ **자동 파일명 생성**: `photo_YYYYMMDD_000.pdf` 형식
- ✅ **날짜가 바뀌면 번호 자동 초기화**

---

## 🖼 미리보기 예시

| 2장 (1열 2행) | 4장 (2열 2행) |
|---------------|---------------|
| ![2장](docs/demo_2.png) | ![4장](docs/demo_4.png) |

| 6장 (2열 3행) | 8장 (2열 4행) |
|---------------|---------------|
| ![6장](docs/demo_6.png) | ![8장](docs/demo_8.png) |

> 💡 `docs/demo_*.png` 이미지 파일을 리포지토리에 넣으면 자동으로 렌더링됩니다.

---

## 🚀 사용 방법

1. 위의 [사이트 링크](https://newstars.github.io/photo-resize/)에 접속
2. 사진 개수 선택 (2, 4, 6, 8)
3. 각 틀을 클릭하여 사진 업로드
4. `📄 PDF 미리보기` 또는 `📥 PDF 다운로드` 클릭

모든 처리는 **로컬 브라우저에서만 실행되며, 사진은 서버로 전송되지 않습니다**.

---

## 💻 Git 사용법 (업로드 & 배포)

```bash
# 저장소 클론
git clone https://github.com/newstars/photo-resize.git
cd photo-resize

# 수정 및 커밋
vim index.html   # 또는 VSCode 등으로 수정
git add .
git commit -m "레이아웃 수정 및 파일명 자동 생성 추가"
git push origin main