## 프로젝트 설명

이 프로젝트는 Instacart 데이터셋을 사용하여 재주문할 가능성이 높은 제품을 예측하는 대시보드를 제공합니다.

먼저 streamlit 프로젝트를 같은 환경에서 사용하기 위해 python 버전을 통일해야합니다.

pyenv를 사용해서 python 버전을 통일했습니다.

### pyenv 설치

for macOS

```
$brew install pyenv
```

### 가상 환경 생성 및 설정

```
# 생성
$python -m venv venv

# 설정
$source venv/bin/activate  # macOS/Linux
$.\venv\Scripts\activate   # Windows
```

### python 설치

```
$pyenv install 3.8.5
$pyenv local 3.8.5
```

### python 버전 확인

```
$ pyenv versions
  system
* 3.8.5 (set by /Users/hankuklee/dev/ai_lab/ailab_mlproject_16/.python-version)
  3.10.2
  venv34
```

### repo 구조

```
mlproject-16/
│
├── app.py
├── requirements.txt
├── .python-version
├── venv/  # .gitignore에 추가하여 GitHub에 업로드하지 않도록 합니다.
├── data/
│   └── predicted_reorders.csv
└── README.md
```
