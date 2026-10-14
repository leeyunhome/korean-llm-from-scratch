---
title: "N을 키우면"
parent: "Part 1"
nav_order: 3
permalink: /part1/ngram/
---

# N-그램의 N을 키우면 무슨 일이 생기나

같은 사전 데이터로 만든 1-그램부터 6-그램, 그리고 20-그램 모델이 각각 2,000개씩 만든 단어를 실제 사전과 비교했습니다.

<small>데이터: 국립국어원 표준국어대사전 표제어 420,309개 (<a href="https://github.com/korean-word-game/db">korean-word-game/db</a>, 2018년 수집)</small>

---

![N에 따른 사전 단어 비율과 서로 다른 진짜 단어·새 단어 수]({{ '/assets/images/part1/ngram_words.png' | relative_url }})

N이 클수록 사전에 있는 단어의 비율이 올라 4-그램에서 94%, 20-그램에서는 100%가 됩니다. 사전에 없는 새 단어는 3-그램의 856개에서 4-그램의 120개로 급격히 줄고 20-그램에서는 하나도 나오지 않아, 새 단어를 만들기보다 사전을 외워서 다시 내놓게 됩니다.

---

![N에 따른 서로 다른 N-그램 수]({{ '/assets/images/part1/ngram_patterns.png' | relative_url }})

서로 다른 N-그램의 수는 N이 커질수록 늘다가 6-그램 근처에서 거의 멈춥니다. 6-그램(1,141,426개)과 20-그램(1,151,944개)의 차이는 1%뿐입니다.
