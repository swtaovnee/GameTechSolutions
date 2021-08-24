<h2 id="Game1">棋牌系統</h2>

*   [應用說明](#Game11)
*   [架構目標](#Game12)
*   [架構特性](#Game13)
*   [AWS服務](#Game14)
*   [參考架構](#Game15)
* * *



<h3 id="Game11">應用說明</h3>

棋牌系統

<h3 id="Game12">架構目標</h3>

-  多人對戰需要保持Socket 連線不中斷
-  平行運算多，多在 美工運算 和 多連線運算

<h3 id="Game13">架構特性</h3>

 提供超過400種的機型組合，從一般型、運算優化、到HPC高效機型，提供特定前端網頁表現與後台機率運算所需的計算力
- 依各個遊戲玩家表現，提供自動擴容與自動偵測機制，確保前端系統穩定
- 搭配CDN服務，加速棋牌前端網頁不論是圖片或是影片的內容派送
- 
<h3 id="Game14">AWS服務</h3>

- [Amazon Relational Database Service (Amazon RDS)](https://aws.amazon.com/tw/rds/)
- [Amazon Athena](https://aws.amazon.com/tw/athena/)
- [Amazon S3](https://aws.amazon.com/tw/s3/)
- [Amazon SageMaker](https://aws.amazon.com/tw/sagemaker/)
- [Amazon QuickSight](https://aws.amazon.com/tw/quicksight/)
- [Amazon EMR](https://aws.amazon.com/tw/emr/)

<h3 id="Game15">參考架構</h3>

參考架構
![Alt text](Game6.jpg)


* * *

