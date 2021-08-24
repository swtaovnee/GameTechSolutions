<h2 id="Game1">三方金流系統</h2>

*   [應用說明](#Game11)
*   [架構目標](#Game12)
*   [架構特性](#Game13)
*   [AWS服務](#Game14)
*   [參考架構](#Game15)
* * *



<h3 id="Game11">應用說明</h3>

三方金流系統

<h3 id="Game12">架構目標</h3>

- 連接幾十家銀行API ，不能掉單
- 資料庫需要備援充足 (異地備援, 抗監管) 
- 連接銀行需要中國IP，並且透過跳板轉送指令
- 資料庫需要即時同步資料
- 風控 (轉移資金能力）

<h3 id="Game13">架構特性</h3>

- 提供多樣性資料庫系統，滿足不同客戶間遊戲建置的需求
- 運用代管型資料庫系統，可以輕鬆管理與高度擴展資料庫系統
- 透過異地同步資料備份確保資料安全無虞
- 透過讀寫分離機制，加速資料存取機制
- 資料加密，保証充值會員資料不致遭竊


<h3 id="Game14">AWS服務</h3>

- [Amazon EC2](https://aws.amazon.com/tw/ec2/instance-types/)
- [Amazon EBS](https://aws.amazon.com/tw/ebs/volume-types/)
- [Amazon Relational Database Service (RDS)](https://aws.amazon.com/tw/rds/)


<h3 id="Game15">參考架構</h3>

參考架構
![Alt text](game3.jpg)


* * *

