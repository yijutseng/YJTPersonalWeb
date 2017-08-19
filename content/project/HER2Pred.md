+++
# Date this page was created.
date = "2016-10-01"

# Project title.
title = "應用機器學習方法進行多臨床參數分析以建立癌症預後預測之模型"

# Project summary to display on homepage.
summary = "建立乳癌預後預測模型。乳癌預後預測標的為一年內再復發情形，未來可幫助乳癌案例的介入追蹤決策，進一步達到早期診斷，早期治療以的目的。"

# Optional image to display on homepage (relative to `static/img/` folder).
#image_preview = "bubbles.jpg"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["ehr","data-mining","breast-cancer"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = false

# Optional featured image (relative to `static/img/` folder).
[header]
#image = "headers/bubbles-wide.jpg"
#caption = "My caption :smile:"

+++

### 補助單位

長庚醫院

### 執行期間

2016/10/01 - 2017/09/30

### 計畫摘要

基於乳癌細胞所呈現的雌性激素受體 (estrogen receptor, ER)、孕激素受體 (progesterone receptor, PR) 與第二型人類表皮生長因子接受體 (human epidermal growth factor 2 (HER2) receptor)，乳癌可被分為多種亞型，並做為治療與預後的依據。研究指出，HER2在約20-25%的乳癌患者中過度表現，而HER2過度表現的患者容易癌細胞轉移與乳癌復發，存活期較短，且治療效果也較差。為了即時檢測第二型人類表皮生長因子的表現，目前多使用血清第二型人類表皮生長因子 (serum HER2 (sHER2) level)，文獻指出，在乳癌復發前，可測得較高的單一sHER2測量值。然而，使用單一sHER2測量值預測乳癌預後仍有其限制，除了設定單一閾值所造成的低敏感度外，單一測量值也無法表示病程與臨床表徵的連續變化，其他與乳癌復發預測有關的因子，如TNM tumor stage、雌性激素受體與孕激素受體等數值也無法一併分析。本計畫預計使用機器學習演算法，搭配多重測量值 (multiple measurements) 資料整合演算法，使用2002至2016年間在長庚紀念醫院林口院區與台北院區接受乳癌治療的病患資料，包括腫瘤相關資料 (TNM tumor stage、雌性激素受體表現、孕激素受體表現與第二型人類表皮生長因子接受體表現) 以及連續性的sHER2測量值，建立乳癌預後預測模型。乳癌預後預測標的為一年內再復發情形。此預測模型將可幫助乳癌案例的介入追蹤決策，進一步達到早期診斷，早期治療以及改善治療成效的目的。