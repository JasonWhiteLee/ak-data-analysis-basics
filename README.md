# 데이터분석 기초 — 실습 데이터

2026-09-01 사내 교육(코드잇/AK) 실습용 데이터셋 모음.
Colab에서 URL로 바로 읽어 쓰기 위한 저장소입니다.

## 파일

| 파일 | 행 | 설명 |
|---|---|---|
| `superstore_orders.csv` | 10,239 | **실습용.** 결측·이상치·중복을 의도적으로 포함 |
| `superstore_orders_raw.csv` | 10,194 | 원본 (Tableau 공식 샘플) |
| `superstore_returns.csv` | 296 | 반품 여부 |
| `superstore_people.csv` | 4 | 지역 담당자 |
| `online_retail.csv` | 541,909 | UCI Online Retail (영국 온라인 소매, 2010-12~2011-12) |
| `olist/*.csv` | — | Olist 브라질 커머스 8개 테이블 |

## 읽는 법

```python
import pandas as pd

BASE = 'https://raw.githubusercontent.com/JasonWhiteLee/ak-data-analysis-basics/main/'

orders  = pd.read_csv(BASE + 'superstore_orders.csv', parse_dates=['Order Date','Ship Date'])
returns = pd.read_csv(BASE + 'superstore_returns.csv')
retail  = pd.read_csv(BASE + 'online_retail.csv', parse_dates=['InvoiceDate'])
olist   = pd.read_csv(BASE + 'olist/olist_orders_dataset.csv')
```

## 출처

- Superstore — Tableau 공식 샘플 데이터
- Online Retail — UCI Machine Learning Repository (Dataset 352)
- Olist — [olist/work-at-olist-data](https://github.com/olist/work-at-olist-data) (CC BY-NC-SA 4.0)
