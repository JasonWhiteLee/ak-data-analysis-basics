# 데이터분석 기초


## 실습 노트북

아래 **실습본** 링크를 눌러 Colab에서 열고, 상단 **파일 > 드라이브에 사본 저장**을
누른 뒤 사용하세요. 사본을 만들어야 내가 고친 내용이 남습니다.

| 교시 | 내용 | 실습본 | 정답본 |
|---|---|---|---|
| 1 | 환경과 기본 문법 | [열기](https://colab.research.google.com/github/JasonWhiteLee/ak-data-analysis-basics/blob/main/notebooks/1%EA%B5%90%EC%8B%9C_%ED%99%98%EA%B2%BD%EA%B3%BC_%EA%B8%B0%EB%B3%B8%EB%AC%B8%EB%B2%95_%EC%8B%A4%EC%8A%B5.ipynb) | [열기](https://colab.research.google.com/github/JasonWhiteLee/ak-data-analysis-basics/blob/main/notebooks/1%EA%B5%90%EC%8B%9C_%ED%99%98%EA%B2%BD%EA%B3%BC_%EA%B8%B0%EB%B3%B8%EB%AC%B8%EB%B2%95_%EC%A0%95%EB%8B%B5.ipynb) |
| 2 | 조회와 전처리 | [열기](https://colab.research.google.com/github/JasonWhiteLee/ak-data-analysis-basics/blob/main/notebooks/2%EA%B5%90%EC%8B%9C_%EC%A1%B0%ED%9A%8C%EC%99%80_%EC%A0%84%EC%B2%98%EB%A6%AC_%EC%8B%A4%EC%8A%B5.ipynb) | [열기](https://colab.research.google.com/github/JasonWhiteLee/ak-data-analysis-basics/blob/main/notebooks/2%EA%B5%90%EC%8B%9C_%EC%A1%B0%ED%9A%8C%EC%99%80_%EC%A0%84%EC%B2%98%EB%A6%AC_%EC%A0%95%EB%8B%B5.ipynb) |
| 3 | 결합과 집계 | [열기](https://colab.research.google.com/github/JasonWhiteLee/ak-data-analysis-basics/blob/main/notebooks/3%EA%B5%90%EC%8B%9C_%EA%B2%B0%ED%95%A9%EA%B3%BC_%EC%A7%91%EA%B3%84_%EC%8B%A4%EC%8A%B5.ipynb) | [열기](https://colab.research.google.com/github/JasonWhiteLee/ak-data-analysis-basics/blob/main/notebooks/3%EA%B5%90%EC%8B%9C_%EA%B2%B0%ED%95%A9%EA%B3%BC_%EC%A7%91%EA%B3%84_%EC%A0%95%EB%8B%B5.ipynb) |
| 4 | 탐색과 정리 | [열기](https://colab.research.google.com/github/JasonWhiteLee/ak-data-analysis-basics/blob/main/notebooks/4%EA%B5%90%EC%8B%9C_%ED%83%90%EC%83%89%EA%B3%BC_%EC%A0%95%EB%A6%AC_%EC%8B%A4%EC%8A%B5.ipynb) | [열기](https://colab.research.google.com/github/JasonWhiteLee/ak-data-analysis-basics/blob/main/notebooks/4%EA%B5%90%EC%8B%9C_%ED%83%90%EC%83%89%EA%B3%BC_%EC%A0%95%EB%A6%AC_%EC%A0%95%EB%8B%B5.ipynb) |
| 5 | 시각화 | [열기](https://colab.research.google.com/github/JasonWhiteLee/ak-data-analysis-basics/blob/main/notebooks/5%EA%B5%90%EC%8B%9C_%EC%8B%9C%EA%B0%81%ED%99%94_%EC%8B%A4%EC%8A%B5.ipynb) | [열기](https://colab.research.google.com/github/JasonWhiteLee/ak-data-analysis-basics/blob/main/notebooks/5%EA%B5%90%EC%8B%9C_%EC%8B%9C%EA%B0%81%ED%99%94_%EC%A0%95%EB%8B%B5.ipynb) |
| 6 | 관계와 분석 에이전트 | [열기](https://colab.research.google.com/github/JasonWhiteLee/ak-data-analysis-basics/blob/main/notebooks/6%EA%B5%90%EC%8B%9C_%EB%B6%84%EC%84%9D%EC%97%90%EC%9D%B4%EC%A0%84%ED%8A%B8_%EC%8B%A4%EC%8A%B5.ipynb) | (정답본 없음) |
| 7 | 복습과 정리 | [열기](https://colab.research.google.com/github/JasonWhiteLee/ak-data-analysis-basics/blob/main/notebooks/7%EA%B5%90%EC%8B%9C_%EB%B3%B5%EC%8A%B5_%EC%A0%95%EB%A6%AC_%EC%8B%A4%EC%8A%B5.ipynb) | [열기](https://colab.research.google.com/github/JasonWhiteLee/ak-data-analysis-basics/blob/main/notebooks/7%EA%B5%90%EC%8B%9C_%EB%B3%B5%EC%8A%B5_%EC%A0%95%EB%A6%AC_%EC%A0%95%EB%8B%B5.ipynb) |

**실습본**은 핵심 코드 몇 줄이 빈칸(`____`)으로 비어 있습니다. 수업 중에 채웁니다.
**정답본**은 전부 채워져 있습니다. 복습할 때 보세요.

> 코드가 꼬였을 때는 상단 **런타임 > 모두 실행**을 누르면 처음부터 다시 돌아갑니다.

---

## 강의 교안

교시마다 교안이 둘입니다. **소개 파트**는 노트북에 들어가기 전에, **정리 파트**는 실습이 끝난 뒤에 씁니다.

- **열기** — 브라우저에서 바로 발표됩니다. 설치할 것도, 내려받을 것도 없습니다.
- **PDF** — 내려받아 두면 인터넷 없이도 열립니다. 강의장 PC나 유인물용으로 쓰세요. (슬라이드 한 장 = 한 페이지)

| 교시 | 내용 | 소개 파트 | 정리 파트 |
|---|---|---|---|
| 1 | 환경과 기본 문법 | [열기](https://jasonwhitelee.github.io/ak-data-analysis-basics/%EA%B5%90%EC%95%88/1%EA%B5%90%EC%8B%9C_%EC%86%8C%EA%B0%9C_%EA%B5%90%EC%95%88.html) · [PDF](https://github.com/JasonWhiteLee/ak-data-analysis-basics/raw/main/%EA%B5%90%EC%95%88/pdf/1%EA%B5%90%EC%8B%9C_%EC%86%8C%EA%B0%9C_%EA%B5%90%EC%95%88.pdf) | [열기](https://jasonwhitelee.github.io/ak-data-analysis-basics/%EA%B5%90%EC%95%88/1%EA%B5%90%EC%8B%9C_%EC%A0%95%EB%A6%AC_%EA%B5%90%EC%95%88.html) · [PDF](https://github.com/JasonWhiteLee/ak-data-analysis-basics/raw/main/%EA%B5%90%EC%95%88/pdf/1%EA%B5%90%EC%8B%9C_%EC%A0%95%EB%A6%AC_%EA%B5%90%EC%95%88.pdf) |
| 2 | 조회와 전처리 | [열기](https://jasonwhitelee.github.io/ak-data-analysis-basics/%EA%B5%90%EC%95%88/2%EA%B5%90%EC%8B%9C_%EC%86%8C%EA%B0%9C_%EA%B5%90%EC%95%88.html) · [PDF](https://github.com/JasonWhiteLee/ak-data-analysis-basics/raw/main/%EA%B5%90%EC%95%88/pdf/2%EA%B5%90%EC%8B%9C_%EC%86%8C%EA%B0%9C_%EA%B5%90%EC%95%88.pdf) | [열기](https://jasonwhitelee.github.io/ak-data-analysis-basics/%EA%B5%90%EC%95%88/2%EA%B5%90%EC%8B%9C_%EC%A0%95%EB%A6%AC_%EA%B5%90%EC%95%88.html) · [PDF](https://github.com/JasonWhiteLee/ak-data-analysis-basics/raw/main/%EA%B5%90%EC%95%88/pdf/2%EA%B5%90%EC%8B%9C_%EC%A0%95%EB%A6%AC_%EA%B5%90%EC%95%88.pdf) |
| 3 | 결합과 집계 | [열기](https://jasonwhitelee.github.io/ak-data-analysis-basics/%EA%B5%90%EC%95%88/3%EA%B5%90%EC%8B%9C_%EC%86%8C%EA%B0%9C_%EA%B5%90%EC%95%88.html) · [PDF](https://github.com/JasonWhiteLee/ak-data-analysis-basics/raw/main/%EA%B5%90%EC%95%88/pdf/3%EA%B5%90%EC%8B%9C_%EC%86%8C%EA%B0%9C_%EA%B5%90%EC%95%88.pdf) | [열기](https://jasonwhitelee.github.io/ak-data-analysis-basics/%EA%B5%90%EC%95%88/3%EA%B5%90%EC%8B%9C_%EC%A0%95%EB%A6%AC_%EA%B5%90%EC%95%88.html) · [PDF](https://github.com/JasonWhiteLee/ak-data-analysis-basics/raw/main/%EA%B5%90%EC%95%88/pdf/3%EA%B5%90%EC%8B%9C_%EC%A0%95%EB%A6%AC_%EA%B5%90%EC%95%88.pdf) |
| 4 | 탐색과 정리 | [열기](https://jasonwhitelee.github.io/ak-data-analysis-basics/%EA%B5%90%EC%95%88/4%EA%B5%90%EC%8B%9C_%EC%86%8C%EA%B0%9C_%EA%B5%90%EC%95%88.html) · [PDF](https://github.com/JasonWhiteLee/ak-data-analysis-basics/raw/main/%EA%B5%90%EC%95%88/pdf/4%EA%B5%90%EC%8B%9C_%EC%86%8C%EA%B0%9C_%EA%B5%90%EC%95%88.pdf) | [열기](https://jasonwhitelee.github.io/ak-data-analysis-basics/%EA%B5%90%EC%95%88/4%EA%B5%90%EC%8B%9C_%EC%A0%95%EB%A6%AC_%EA%B5%90%EC%95%88.html) · [PDF](https://github.com/JasonWhiteLee/ak-data-analysis-basics/raw/main/%EA%B5%90%EC%95%88/pdf/4%EA%B5%90%EC%8B%9C_%EC%A0%95%EB%A6%AC_%EA%B5%90%EC%95%88.pdf) |
| 5 | 시각화 | [열기](https://jasonwhitelee.github.io/ak-data-analysis-basics/%EA%B5%90%EC%95%88/5%EA%B5%90%EC%8B%9C_%EC%86%8C%EA%B0%9C_%EA%B5%90%EC%95%88.html) · [PDF](https://github.com/JasonWhiteLee/ak-data-analysis-basics/raw/main/%EA%B5%90%EC%95%88/pdf/5%EA%B5%90%EC%8B%9C_%EC%86%8C%EA%B0%9C_%EA%B5%90%EC%95%88.pdf) | [열기](https://jasonwhitelee.github.io/ak-data-analysis-basics/%EA%B5%90%EC%95%88/5%EA%B5%90%EC%8B%9C_%EC%A0%95%EB%A6%AC_%EA%B5%90%EC%95%88.html) · [PDF](https://github.com/JasonWhiteLee/ak-data-analysis-basics/raw/main/%EA%B5%90%EC%95%88/pdf/5%EA%B5%90%EC%8B%9C_%EC%A0%95%EB%A6%AC_%EA%B5%90%EC%95%88.pdf) |
| 6 | 관계와 분석 에이전트 | [열기](https://jasonwhitelee.github.io/ak-data-analysis-basics/%EA%B5%90%EC%95%88/6%EA%B5%90%EC%8B%9C_%EC%86%8C%EA%B0%9C_%EA%B5%90%EC%95%88.html) · [PDF](https://github.com/JasonWhiteLee/ak-data-analysis-basics/raw/main/%EA%B5%90%EC%95%88/pdf/6%EA%B5%90%EC%8B%9C_%EC%86%8C%EA%B0%9C_%EA%B5%90%EC%95%88.pdf) | [열기](https://jasonwhitelee.github.io/ak-data-analysis-basics/%EA%B5%90%EC%95%88/6%EA%B5%90%EC%8B%9C_%EC%A0%95%EB%A6%AC_%EA%B5%90%EC%95%88.html) · [PDF](https://github.com/JasonWhiteLee/ak-data-analysis-basics/raw/main/%EA%B5%90%EC%95%88/pdf/6%EA%B5%90%EC%8B%9C_%EC%A0%95%EB%A6%AC_%EA%B5%90%EC%95%88.pdf) |
| 7 | 복습과 정리 | [열기](https://jasonwhitelee.github.io/ak-data-analysis-basics/%EA%B5%90%EC%95%88/7%EA%B5%90%EC%8B%9C_%EC%86%8C%EA%B0%9C_%EA%B5%90%EC%95%88.html) · [PDF](https://github.com/JasonWhiteLee/ak-data-analysis-basics/raw/main/%EA%B5%90%EC%95%88/pdf/7%EA%B5%90%EC%8B%9C_%EC%86%8C%EA%B0%9C_%EA%B5%90%EC%95%88.pdf) | — |

교안 원본은 GitHub 의 [`교안/`](https://github.com/JasonWhiteLee/ak-data-analysis-basics/tree/main/%EA%B5%90%EC%95%88) 폴더에, PDF 는 [`교안/pdf/`](https://github.com/JasonWhiteLee/ak-data-analysis-basics/tree/main/%EA%B5%90%EC%95%88/pdf) 에 있습니다.
**전체를 한 번에 받으려면** [ZIP 내려받기](https://github.com/JasonWhiteLee/ak-data-analysis-basics/archive/refs/heads/main.zip) — 노트북·데이터·교안·PDF 가 모두 들어 있습니다.


---

## 실습 데이터

노트북이 아래 주소에서 자동으로 읽어 옵니다. 따로 내려받지 않아도 됩니다.

| 파일 | 행 | 쓰는 곳 |
|---|---|---|
| `superstore_orders.csv` | 10,239 | 1·3·4·5·7교시 — 어느 유통사 4년치 주문 내역 |
| `superstore_returns.csv` | 296 | 3·7교시 — 반품 여부 |
| `superstore_people.csv` | 4 | 3교시 — 지역 담당자 |
| `online_retail.csv` | 541,909 | 2교시 — 영국 온라인 소매 1년치 |
| `olist/*.csv` | 8개 표 | 6교시 — 브라질 커머스 (주문·리뷰) |
| `superstore_orders_raw.csv` | 10,194 | 참고용 원본 |

```python
import pandas as pd

BASE = 'https://raw.githubusercontent.com/JasonWhiteLee/ak-data-analysis-basics/main/'

orders  = pd.read_csv(BASE + 'superstore_orders.csv', parse_dates=['Order Date', 'Ship Date'])
returns = pd.read_csv(BASE + 'superstore_returns.csv')
retail  = pd.read_csv(BASE + 'online_retail.csv', parse_dates=['InvoiceDate'])
olist   = pd.read_csv(BASE + 'olist/olist_orders_dataset.csv')
```

> `superstore_orders.csv` 에는 **결측치·이상치·중복값이 일부러 들어 있습니다.**
> 실무 데이터에서 겪는 일을 수업 중에 직접 만나기 위한 것입니다.
> 손대지 않은 원본이 필요하면 `superstore_orders_raw.csv` 를 쓰세요.

---

---

## 준비물

- **노트북** (개인 지참)
- **구글 계정 로그인** — Colab 사용에 필요합니다
- 설치할 프로그램은 없습니다

---

## 데이터 출처

- **Superstore** — Tableau 공식 샘플 데이터
- **Online Retail** — UCI Machine Learning Repository (Dataset 352)
- **Olist** — [olist/work-at-olist-data](https://github.com/olist/work-at-olist-data) · CC BY-NC-SA 4.0
