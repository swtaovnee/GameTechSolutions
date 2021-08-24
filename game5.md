<h2 id="Game1">老虎機</h2>

*   [應用說明](#Game11)
*   [架構目標](#Game12)
*   [架構特性](#Game13)
*   [AWS服務](#Game14)
*   [參考架構](#Game15)
* * *



<h3 id="Game11">應用說明</h3>

線上真人百家樂是透線上直播的方式，以真人發牌方式，透過直播系統將檯面發牌資訊，即時提供遊戲玩家，以杜絕過往電腦全自動發牌或機械手臂發牌所帶來的顧忌，希望可以有更公平公正的遊戲方式。

<h3 id="Game12">架構目標</h3>

-  前端網頁表現 Loading 很重
-  機率表現要 獨立運算
-  各個遊戲表現差異化大，機皇佔比 80%

<h3 id="Game13">架構特性</h3>

- 提供超過400種的機型組合，從一般型、運算優化、到HPC高效機型，提供特定前端網頁表現與後台機率運算所需的計算力
- 依各個遊戲玩家表現，提供自動擴容與自動偵測機制，確保前端系統穩定
- 搭配CDN服務，加速老虎機前端網頁不論是圖片或是影片的內容派送

<h3 id="Game14">AWS服務</h3>

- [Amazon EC2](https://aws.amazon.com/tw/ec2/instance-types/)
- [Amazon EBS](https://aws.amazon.com/tw/ebs/volume-types/)
- [Amazon CloudFront](https://aws.amazon.com/tw/cloudfront/)


<h3 id="Game15">參考架構</h3>

參考架構
![Alt text](Game5.jpg)


* * *

