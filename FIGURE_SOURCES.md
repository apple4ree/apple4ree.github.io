

## Satellite investigation images (2026-10-12)

Acquired through the user-authorized Notion research page and its data/method subpages. No signed URLs, account metadata or page screenshots are published.

- `satellite-landsat-bands.png` — USGS Landsat 8–9 Collection 2 Level 2 밴드 규격 · 데이터 조사 기록. Source: https://www.usgs.gov/landsat-missions/landsat-collection-2-level-2-science-products. Reference/input material, not a new experimental result.
- `satellite-asos-sample.png` — 기상청 ASOS 지상관측자료 · 데이터 조사 기록. Source: https://data.kma.go.kr/data/grnd/selectAsosRltmList.do. Reference/input material, not a new experimental result.
- `satellite-asos-stations.png` — 기상청 ASOS 관측 지점 정보 · 데이터 조사 기록. Source: https://data.kma.go.kr/data/grnd/selectAsosRltmList.do. Reference/input material, not a new experimental result.
- `satellite-dctnet-reference.png` — Zhao et al., Discrete Cosine Transform Network for Guided Depth Map Super-Resolution, CVPR 2022, Figure 2. Source: https://openaccess.thecvf.com/content/CVPR2022/html/Zhao_Discrete_Cosine_Transform_Network_for_Guided_Depth_Map_Super-Resolution_CVPR_2022_paper.html. Reference/input material, not a new experimental result.

Investigation page: https://app.notion.com/p/1a81c024c0b4804cbd4bd752429eddd6

## Satellite July 2026 retraining report

Source: https://kma.damilab.cc/viewer.html?file=%EC%9E%AC%ED%95%99%EC%8A%B5_%EC%9D%B4%EC%9C%A0%EC%99%80_%EA%B2%B0%EA%B3%BC_selfcontained.html
Index: https://kma.damilab.cc/ (dated 2026-07-31). Original inline PNG assets exported from the report viewer.

- `kma-cloudy-reference.png` — 구름이 포함된 GK2B 참조 영상. Team research; source image preserved.
- `kma-cloudy-output.png` — 구름 참조 조건의 복원 예시. Team research; source image preserved.
- `kma-clear-reference.png` — 맑은 조건의 GK2B 참조 영상. Team research; source image preserved.
- `kma-clear-output.png` — 맑은 참조 조건의 복원 예시. Team research; source image preserved.
- `kma-monthly-ground-validation.png` — Landsat·복원 결과와 ASOS 지면온도의 월별 편차·RMSE. Team research; source image preserved.
- `kma-lst-retraining.png` — LST 복원 비교 · 보간, 이전 모델, 재학습 모델, Landsat 기준. Team research; source image preserved.
- `kma-seoul-comparison.png` — 서울 복원 영상 · 같은 시점의 5가지 결과. Team research; source image preserved.

Evaluation notes: 2.359→1.382 K is the same 110 test patches; 3.01→1.86 K is one LST example. Cloudy/clear examples have different dates. Monthly ASOS figure is aggregate n=632, not a Seoul-only figure.
