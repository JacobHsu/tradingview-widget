# tradingview-widget

tradingview [即時圖表小工具](https://tw.tradingview.com/widget/advanced-chart/)


[布林通道](https://zh.wikipedia.org/wiki/布林带)  

「中軌」為股價的平均成本，「上軌」和「下軌」可分別視為股價的壓力線和支撐線。
由布林帶衍生出兩項頗為實用的指標——**「%b指標」**和**「帶寬指標」**，以輔助布林帶的判讀和運用。

BB BB%B BBW  

```js

new TradingView.widget(
{
  ...
  "studies": [
    "BB@tv-basicstudies",
    "BollingerBandsR@tv-basicstudies",
    "BollingerBandsWidth@tv-basicstudies"
  ]
}
```

Stochastic [隨機震盪指標(KD)](https://tw.tradingview.com/scripts/stochastic/)

隨機震盪指標是一個範圍區間動量震盪指標。隨機震盪指標被設計用來顯示在一個用戶定義時間段內的收盤價位置與高/低範圍之間的比較。
通常情況下，隨機震盪指標用於三件事：識別超買和超賣水平、識別分歧、識別牛市和熊市組合或信號。

[威廉指標(%R)](https://tw.tradingview.com/scripts/williamsr/)

威廉指標(%R)是技術分析中使用的基於動量震盪指標，主要用於識別超買和超賣條件。%R基於用戶定義回顧期的當前關閉和最高處高價的比較。%R在0和-100之間震盪(注意是負值)，讀數更接近零，表明更多超買條件；接近-100表示超賣。通常%R可以基於超買和超賣條件以及總體動量變化來生成設置。

與KD雷同的地方在於，目前絕大多數的投資人也是以-80%、-20%為超賣、超買區的界線，
一旦低於-80%，表示個股正處於超賣的情況，相反的，一旦高於-20%，則正處於超買的情況。

```js

new TradingView.widget(
{
  ...
  "studies": [
    "Stochastic@tv-basicstudies",
    "WilliamR@tv-basicstudies"
  ],
}
```  
  
  
