# Google-Colab-만들기

# 📘 구글 코랩(Google Colab) 사용법

구글 코랩은 Python을 웹 브라우저에서 실행할 수 있는 강력한 도구입니다. 특히 머신러닝/딥러닝에 많이 사용됩니다. 아래는 주요 기능과 사용법을 요약한 도표입니다.

## 🔹 구글 코랩 사용법 요약표

| 항목 | 설명 | 예시 / 팁 |
|------|------|-----------|
| **1. 접속 방법** | [https://colab.research.google.com](https://colab.research.google.com) 에 접속 | 구글 계정 필요 |
| **2. 새 노트북 만들기** | "파일 > 새 노트북" 클릭 | `.ipynb` 파일 생성 |
| **3. 셀(Cell) 종류** | 코드 셀, 텍스트 셀(Markdown) | 코드: Python 실행, 텍스트: 문서 작성 |
| **4. 코드 실행** | 셀에 코드 작성 후 `Shift + Enter` 또는 ▶️ 클릭 | `print("Hello, Colab!")` |
| **5. 파일 업로드** | `from google.colab import files` → `files.upload()` | GUI로 파일 업로드 가능 |
| **6. 구글 드라이브 연동** | `from google.colab import drive` → `drive.mount('/content/drive')` | 드라이브 파일 사용 가능 |
| **7. 라이브러리 설치** | `!pip install 라이브러리명` | 예: `!pip install transformers` |
| **8. 런타임 유형 변경** | "런타임 > 런타임 유형 변경 > GPU/TPU" 선택 | 딥러닝 작업 시 GPU 필수 |
| **9. 노트북 저장** | 자동 저장 (Google Drive) / 수동 저장 가능 | "파일 > 드라이브에 사본 저장" |
| **10. GitHub와 연동** | "파일 > GitHub에서 열기" 또는 push/pull | 노트북을 GitHub에 올릴 수 있음 |

---

## 📌 추가 팁

- ✅ **단축키 사용**: `Ctrl + M + B` (아래 셀 추가), `Ctrl + M + D` (셀 삭제)
- 🔐 **비공개 데이터 사용 시 주의**: 토큰, API 키 등은 `.env`로 분리하거나 숨기기
- 📊 **시각화 라이브러리**: `matplotlib`, `seaborn` 등 시각화도 가능
- 📁 **작업 디렉토리**: `!ls`, `!pwd`로 현재 위치 확인 가능

---

## ✅ GitHub에 업로드할 때 팁

- `.ipynb` 파일은 GitHub에서 미리보기가 지원됩니다.
- 이 사용법을 `README.md`에 포함하면 문서화가 잘 됩니다.
- 예제 노트북과 함께 저장하면 학습자에게 큰 도움이 됩니다.
