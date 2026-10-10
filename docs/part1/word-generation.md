---
title: "통계로 만든 단어"
parent: "Part 1"
nav_order: 2
permalink: /part1/word-generation/
---

# 통계로 만든 단어는 얼마나 한국어다운가

같은 사전 데이터로 만든 바이그램·트라이그램 모델이 각각 2,000개씩 만든 단어를 실제 사전과 비교했습니다.

<small>데이터: 국립국어원 표준국어대사전 표제어 420,309개 (<a href="https://github.com/korean-word-game/db">korean-word-game/db</a>, 2018년 수집)</small>

---

![생성 단어의 길이 분포와 사전 비교]({{ '/assets/images/part1/word_generation_length.png' | relative_url }})

바이그램은 1글자 단어를 20.7%나 만들지만, 트라이그램은 0.3%로 실제 사전과 같고 전체 길이 분포도 사전에 더 가깝습니다.

---

![생성 단어 중 사전에 있는 단어의 비율]({{ '/assets/images/part1/word_generation_realword.png' | relative_url }})

트라이그램은 3·4글자에서 사전에 있는 단어를 훨씬 많이 만들고, 2,000개 중 서로 다른 진짜 단어도 633개에서 1,135개로 늘었습니다.
