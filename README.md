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
