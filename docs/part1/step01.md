---
title: "Step 01. 낱글자 빈도"
parent: "Part 1"
nav_order: 1
permalink: /part1/step01/
---

# Step 01. 낱글자 빈도

표준국어대사전 표제어 420,309개에 쓰인 한글 글자의 빈도를 시각화했습니다.

<small>데이터: 국립국어원 표준국어대사전 표제어 (<a href="https://github.com/korean-word-game/db">korean-word-game/db</a>, 2018년 수집)</small>

---

![사전 표제어에 가장 많이 쓰인 글자 20개]({{ '/assets/images/part1/step01_top20.png' | relative_url }})

'다'와 '하'가 압도적으로 많습니다. 표제어에 '~하다' 형태의 동사·형용사가 많기 때문입니다.

---

![글자 순위별 누적 점유율]({{ '/assets/images/part1/step01_coverage.png' | relative_url }})

실제로 쓰인 2,450자 중 상위 100자가 전체 등장의 54.9%, 상위 500자가 92.7%를 차지합니다.

---

![글자별 등장 횟수의 분포]({{ '/assets/images/part1/step01_histogram.png' | relative_url }})

평균(633회)이 중앙값(28회)의 23배인, 한쪽으로 꼬리가 긴 분포입니다.

---

![초성 × 중성 조합별 등장 횟수]({{ '/assets/images/part1/step01_heatmap.png' | relative_url }})

완성형 한글 11,172자 중 실제로 쓰인 글자는 22%뿐이며, 된소리 초성과 일부 복합 모음 칸은 비어 있습니다.
