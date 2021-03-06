<h2 id="Game1">棋牌系統</h2>

*   [應用說明](#Game11)
*   [架構目標](#Game12)
*   [架構特性](#Game13)
*   [AWS服務](#Game14)
*   [參考架構](#Game15)
* * *



<h3 id="Game11">應用說明</h3>

棋牌系統是棋類和牌類遊戲的總稱。主要有樸克牌、鬥地主、象棋、軍棋、五子棋、麻將等遊戲

<h3 id="Game12">架構目標</h3>

-  多人對戰需要保持Socket 連線不中斷
-  平行運算多，多在 美工運算 和 多連線運算

<h3 id="Game13">架構特性</h3>

- 提供超過400種的機型組合，從一般型、運算優化、到HPC高效機型，提供特定前端網頁表現與後台機率運算所需的計算力
- 依各個遊戲玩家表現，提供自動擴容與自動偵測機制，確保前端系統穩定
- 搭配CDN服務，加速棋牌前端網頁不論是圖片或是影片的內容派送

<h3 id="Game14">AWS服務</h3>

- [Amazon EC2](https://aws.amazon.com/tw/ec2/instance-types/)
- [Amazon EBS](https://aws.amazon.com/tw/ebs/volume-types/)
- [Amazon CloudFront](https://aws.amazon.com/tw/cloudfront/)

<h3 id="Game15">參考架構</h3>

EC2參考架構
![Alt text](Game2-1.jpg)

K8S參考架構
![Alt text](Game2-2.jpg)
* * *

