# Polars Recipes

실용적인 데이터 처리를 위한 Polars 레시피 모음입니다.

## 시작하기

### 1. 저장소 복제

```bash
git clone https://github.com/dschloe/polars_recipes.git
cd polars_recipes
```

## 설치 방법

### 1. 가상 환경 설치
- 폴더 최상위 경로에서 가상환경을 설치
```
pip install virtualenv # 기존에 이미 설치 한 적 있다면 생략 가능
virtualenv venv
```

### 2. 가상 환경 접속

가상환경 생성 및 필요 패키지 설치:

```bash
# 가상환경 생성
python -m venv venv

# 가상환경 활성화
# Windows
venv\Scripts\activate
# macOS/Linux
source venv/bin/activate
```

### 3. 주요 라이브러리 설치 
```
# 필요 패키지 설치
pip install -r requirements.txt
```

## 테스트 방법
### 3. 테스트 방법
- 본 교재에는 `.ipynb` 파일들이 있습니다. 
- `.ipynb` 파일의 경우
  + `jupyter lab`에서 실행됩니다. 
```bash
jupyter lab
```

## 에러 문의
- 소스코드는 출판 당시에는 큰 문제가 없으나, 라이브러리 버전업이 되면 교재와 일치하지 않을 수 있습니다.
- 교재의 코드 에러 발생이 생기면 본 깃허브 코드를 확인하여 주시기를 바랍니다.
- 권장방법 : 메뉴 Issues-New Issues-메모 남기기-Submit new issue
- Evan : jhjung@dschloe.com

## 온라인강의
- Youtube : https://www.youtube.com/@darkgreenchloeJJ-pe6gq

## License
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

# 작가의 다른 서적
- Streamlit 으로 프로젝트 한방에 끝내기 With 파이썬 (개정 2판)
- 판매링크
    + 부크크 (종이책) : https://bookk.co.kr/bookStore/67930908f3250118b233df2d
    + 교보문고(온라인) : https://product.kyobobook.co.kr/detail/S000215755814
    + 예스 24 : https://www.yes24.com/Product/Goods/142704643
    + 알라딘 : https://www.aladin.co.kr/shop/wproduct.aspx?ItemId=358041499
    + 책소개 : https://dschloe.github.io/ds-projects/2024/01/book_intro/