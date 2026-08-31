# 데이터분석 기초

2026-09-01(화) 09:30–17:30 · 코드잇 / AK · 애경타워 7층 아라움홀

하루 과정입니다. 실습은 **Google Colab**에서 하고, 설치할 것은 없습니다.
브라우저와 구글 계정만 있으면 됩니다.

---

## 실습 노트북

아래 **실습본** 링크를 눌러 Colab에서 열고, 상단 **파일 > 드라이브에 사본 저장**을
누른 뒤 사용하세요. 사본을 만들어야 내가 고친 내용이 남습니다.

| 교시 | 내용 | 실습본 | 완성본 |
|---|---|---|---|
| 1 | 환경과 기본 문법 | [열기](https://colab.research.google.com/github/JasonWhiteLee/ak-data-analysis-basics/blob/main/notebooks/01_%EC%8B%A4%EC%8A%B5.ipynb) | [열기](https://colab.research.google.com/github/JasonWhiteLee/ak-data-analysis-basics/blob/main/notebooks/01_%EC%99%84%EC%84%B1%EB%B3%B8.ipynb) |
| 2 | 조회와 전처리 | [열기](https://colab.research.google.com/github/JasonWhiteLee/ak-data-analysis-basics/blob/main/notebooks/02_%EC%8B%A4%EC%8A%B5.ipynb) | [열기](https://colab.research.google.com/github/JasonWhiteLee/ak-data-analysis-basics/blob/main/notebooks/02_%EC%99%84%EC%84%B1%EB%B3%B8.ipynb) |
| 3 | 결합과 집계 | [열기](https://colab.research.google.com/github/JasonWhiteLee/ak-data-analysis-basics/blob/main/notebooks/03_%EC%8B%A4%EC%8A%B5.ipynb) | [열기](https://colab.research.google.com/github/JasonWhiteLee/ak-data-analysis-basics/blob/main/notebooks/03_%EC%99%84%EC%84%B1%EB%B3%B8.ipynb) |
| 4 | 탐색과 정리 | [열기](https://colab.research.google.com/github/JasonWhiteLee/ak-data-analysis-basics/blob/main/notebooks/04_%EC%8B%A4%EC%8A%B5.ipynb) | [열기](https://colab.research.google.com/github/JasonWhiteLee/ak-data-analysis-basics/blob/main/notebooks/04_%EC%99%84%EC%84%B1%EB%B3%B8.ipynb) |
| 5 | 시각화 | [열기](https://colab.research.google.com/github/JasonWhiteLee/ak-data-analysis-basics/blob/main/notebooks/05_%EC%8B%A4%EC%8A%B5.ipynb) | [열기](https://colab.research.google.com/github/JasonWhiteLee/ak-data-analysis-basics/blob/main/notebooks/05_%EC%99%84%EC%84%B1%EB%B3%B8.ipynb) |
| 6 | 통계분석 기초 | [열기](https://colab.research.google.com/github/JasonWhiteLee/ak-data-analysis-basics/blob/main/notebooks/06_%EC%8B%A4%EC%8A%B5.ipynb) | [열기](https://colab.research.google.com/github/JasonWhiteLee/ak-data-analysis-basics/blob/main/notebooks/06_%EC%99%84%EC%84%B1%EB%B3%B8.ipynb) |
| 7 | 종합 실습 | [열기](https://colab.research.google.com/github/JasonWhiteLee/ak-data-analysis-basics/blob/main/notebooks/07_%EC%8B%A4%EC%8A%B5.ipynb) | [열기](https://colab.research.google.com/github/JasonWhiteLee/ak-data-analysis-basics/blob/main/notebooks/07_%EC%99%84%EC%84%B1%EB%B3%B8.ipynb) |

**실습본**은 핵심 코드 몇 줄이 빈칸(`____`)으로 비어 있습니다. 수업 중에 채웁니다.
**완성본**은 전부 채워져 있습니다. 복습할 때 보세요.

> 코드가 꼬였을 때는 상단 **런타임 > 모두 실행**을 누르면 처음부터 다시 돌아갑니다.

---

## 오늘 하루의 순서

```
문제 정의 → 데이터 이해 → 전처리 → 집계·비교
                                      ↓
결론·보고 ← 통계 검정 ← 시각화 ← 탐색(EDA)
```

| 교시 | 하는 일 | 이 단계에서 던지는 질문 |
|---|---|---|
| 0 | 방향성 | 이 분석으로 무엇이 달라지는가 |
| 1 | 데이터 이해 | 이 데이터는 누구를 대표하는가 |
| 2 | 전처리 | 이 결측치는 왜 생겼는가 |
| 3 | 집계·비교 | 무엇과 비교할 것인가 |
| 4 | 탐색 (EDA) | 이 평균을 믿어도 되는가 |
| 5 | 시각화 | 이 그림이 오해를 부르지 않는가 |
| 6 | 통계 검정 | 이 차이가 우연일 수 있는가 |
| 7 | 결론·보고 | 그래서 무엇을 다르게 할 것인가 |

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

## 강의 교안

**열기** 를 누르면 브라우저에서 바로 발표됩니다. 설치할 것도, 내려받을 것도 없습니다.
강의장 PC에서 쓸 거라면 **내려받기** 로 파일을 저장해 두세요 — 인터넷 없이도 열립니다.

| 교시 | 내용 | | |
|---|---|---|---|
| 0 | 방향성 (철학) | [열기](https://jasonwhitelee.github.io/ak-data-analysis-basics/%EA%B5%90%EC%95%88/0%EA%B5%90%EC%8B%9C_%EB%B0%A9%ED%96%A5%EC%84%B1_%EA%B5%90%EC%95%88.html) | [내려받기](https://raw.githubusercontent.com/JasonWhiteLee/ak-data-analysis-basics/main/%EA%B5%90%EC%95%88/0%EA%B5%90%EC%8B%9C_%EB%B0%A9%ED%96%A5%EC%84%B1_%EA%B5%90%EC%95%88.html) |
| 1 | 환경과 기본 문법 | [열기](https://jasonwhitelee.github.io/ak-data-analysis-basics/%EA%B5%90%EC%95%88/1%EA%B5%90%EC%8B%9C_%EA%B5%90%EC%95%88.html) | [내려받기](https://raw.githubusercontent.com/JasonWhiteLee/ak-data-analysis-basics/main/%EA%B5%90%EC%95%88/1%EA%B5%90%EC%8B%9C_%EA%B5%90%EC%95%88.html) |
| 2 | 조회와 전처리 | [열기](https://jasonwhitelee.github.io/ak-data-analysis-basics/%EA%B5%90%EC%95%88/2%EA%B5%90%EC%8B%9C_%EA%B5%90%EC%95%88.html) | [내려받기](https://raw.githubusercontent.com/JasonWhiteLee/ak-data-analysis-basics/main/%EA%B5%90%EC%95%88/2%EA%B5%90%EC%8B%9C_%EA%B5%90%EC%95%88.html) |
| 3 | 결합과 집계 | [열기](https://jasonwhitelee.github.io/ak-data-analysis-basics/%EA%B5%90%EC%95%88/3%EA%B5%90%EC%8B%9C_%EA%B5%90%EC%95%88.html) | [내려받기](https://raw.githubusercontent.com/JasonWhiteLee/ak-data-analysis-basics/main/%EA%B5%90%EC%95%88/3%EA%B5%90%EC%8B%9C_%EA%B5%90%EC%95%88.html) |
| 4 | 탐색과 정리 | [열기](https://jasonwhitelee.github.io/ak-data-analysis-basics/%EA%B5%90%EC%95%88/4%EA%B5%90%EC%8B%9C_%EA%B5%90%EC%95%88.html) | [내려받기](https://raw.githubusercontent.com/JasonWhiteLee/ak-data-analysis-basics/main/%EA%B5%90%EC%95%88/4%EA%B5%90%EC%8B%9C_%EA%B5%90%EC%95%88.html) |
| 5 | 시각화 | [열기](https://jasonwhitelee.github.io/ak-data-analysis-basics/%EA%B5%90%EC%95%88/5%EA%B5%90%EC%8B%9C_%EA%B5%90%EC%95%88.html) | [내려받기](https://raw.githubusercontent.com/JasonWhiteLee/ak-data-analysis-basics/main/%EA%B5%90%EC%95%88/5%EA%B5%90%EC%8B%9C_%EA%B5%90%EC%95%88.html) |
| 6 | 통계분석 기초 | [열기](https://jasonwhitelee.github.io/ak-data-analysis-basics/%EA%B5%90%EC%95%88/6%EA%B5%90%EC%8B%9C_%EA%B5%90%EC%95%88.html) | [내려받기](https://raw.githubusercontent.com/JasonWhiteLee/ak-data-analysis-basics/main/%EA%B5%90%EC%95%88/6%EA%B5%90%EC%8B%9C_%EA%B5%90%EC%95%88.html) |
| 7 | 종합 실습 + 복습 | [열기](https://jasonwhitelee.github.io/ak-data-analysis-basics/%EA%B5%90%EC%95%88/7%EA%B5%90%EC%8B%9C_%EA%B5%90%EC%95%88.html) | [내려받기](https://raw.githubusercontent.com/JasonWhiteLee/ak-data-analysis-basics/main/%EA%B5%90%EC%95%88/7%EA%B5%90%EC%8B%9C_%EA%B5%90%EC%95%88.html) |

| 조작 | |
|---|---|
| `←` `→` · 클릭 | 넘기기 |
| `F` | 전체화면 |
| `D` | 어두운 배경으로 |
| `P` 또는 인쇄 | 한 장씩 인쇄 (유인물) |

0교시에서 말할 내용은 [강의안](강의안/00_방향성_강의안.md) 에 글로 정리돼 있습니다.

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
