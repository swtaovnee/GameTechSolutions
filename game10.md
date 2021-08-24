<h2 id="Game1">成人直播/點播</h2>

*   [應用說明](#Game11)
*   [架構目標](#Game12)
*   [架構特性](#Game13)
*   [AWS服務](#Game14)
*   [參考架構](#Game15)
* * *



<h3 id="Game11">應用說明</h3>

成人直播/點播

<h3 id="Game12">架構目標</h3>

- 源站只能放中國境外
- 走騰訊雲CDN加速，使用推拉留功能
- 多種轉碼引擎，應對多種終端設備，提供不同解析
- 尋找便宜CDN流量為大宗
- 前端網頁需要做切片加密處理，降低監管封鎖
<h3 id="Game13">架構特性</h3>

- 不需設定、管理或維護基礎設施。您只需提交包含所需影片處理設定的任務即可開始使用
- 內建包含 HLS、DASH、Quick、TimeWebM和 MP4 等格式轉換機制
- 運用內容交付網路 (CDN) 服務，以低延遲和高速傳輸的方式影片安全地交付給全球的客戶
- 提供最進階的安全功能，包括欄位層級加密和 HTTPS 支援
- AWS Shield、AWS WAF 和 Amazon Route 53 無縫整合，以防禦多種類型的攻擊，包括網路和應用程式層級的 DDoS 攻擊。

<h3 id="Game14">AWS服務</h3>

- [Amazon Interactive Video Service (Amazon IVS)](https://aws.amazon.com/tw/ivs/)
- [AWS Shield](https://aws.amazon.com/tw/shield/)
- [AWS WAF](https://aws.amazon.com/tw/waf/)
- [Amazon CloudFront](https://aws.amazon.com/tw/cloudfront/)
- [Amazon Route 53](https://aws.amazon.com/tw/route53/)


<h3 id="Game15">參考架構</h3>

參考架構
![Alt text](Game10.jpg)


* * *

