# 基於集成學習方法之電力輔助市場調頻備轉交易量預測建模 Ensemble Learning Methods on Microgrid Volume Forecast

資料來源：台電電力交易平台、農業氣象觀測網監測系統

收集期間：2021/11/1-2022/2/28，共 2880 筆資料

# 1. 問題介紹
分散式能源概念下的微電網(micro-grid) 因能夠有效經由輸配設備匯集並共用區域性的電力資源，因而被納入台電電力交易平台的電力輔助市場機制，以整合民間與國營的電力資源。然過去微電網的研究著重於分配與調節電力的技術，然而市場機制的管理效率亦可能嚴重影響電力 輔助市場中供需的不確定性，造成供電可靠性下降。因此，本研究採用台電公開交易平台上的交易資料，結合政府公開資料中的氣候資料，透過 SARIMAX 與倒傳遞網路(Back-Propagation Network, BPN)的混合模型，進行輔助交易市場中調頻備轉交易量的預測。研究結果指出集成模型可提升預測的準確度，顯示結合線性與非線性模型在優化預測效果的表現。

# 2. 建模流程
<img width="1135" alt="image" src="https://github.com/nd2237/Ensemble-Learning-Methods-on-Microgrid-Volume-Forecast/assets/144366661/17a80183-3c3c-4510-88a7-496f610b1ad9">



