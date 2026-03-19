# 👋 Hi, I'm [你的名字]

🎓 畢業於國立臺北科技大學資訊與財金管理系  
💻 完成「跨域 Java 軟體工程師就業養成班」結訓  
🌐 精通日文，具備跨文化溝通能力  

---

## 🚀 技術
- **後端開發**：Java、Spring Boot、Spring MVC、Hibernate、Restful API  
- **資料庫**：SQL Server、Transact-SQL、資料庫設計與整合  
- **前端技術**：HTML/CSS、Bootstrap、JavaScript、jQuery、Ajax  
- **版本控管**：Git、團隊協作與專題開發  

---

## 📂 代表性專案
### EduConnect：基於 Spring Boot 架構之線上家教媒合與視訊教學系統
【大專專題題目】
EduConnect：基於 Spring Boot 架構之線上家教媒合與視訊教學系統

【大專專題說明】

在現今蓬勃發展的線上教育市場中，我們觀察到傳統的家教媒合平台常面臨「排課衝突」、「缺乏一站式上課環境」以及「金流對帳繁瑣」等三大痛點。為此，我們團隊開發了「EduConnect 線上家教媒合與視訊教學系統」，這是一款涵蓋排班、結帳到線上授課的 B2C 全端 Web 應用服務。

面試時，若要向廠商介紹本專題，我們的核心亮點可分為以下三個技術與商業面向：

1. 嚴謹的資料庫設計與防超賣機制 (Concurrency Control)
排課系統最致命的錯誤就是「同時段重複預約」。本專題後端採用 Java Spring Boot 開發，結合 MySQL 資料庫。我們在預約核心邏輯中導入了 @Transactional 事務管理與資料庫 Unique Key 約束。當面對高併發的搶課情境時，系統能確保「產生訂單、鎖定時段」的原子性（Atomicity），完美阻絕資料不同步與超賣風險。

2. 零延遲的線上視訊教學整合 (Online Video Classroom Integration)
為實現真正的「一站式」學習體驗，系統突破了僅提供媒合資訊的限制，直接整合了線上視訊教學室。我們透過 API 串接主流視訊通訊服務（WebScoket），確保師生在預約時段能進入專屬的線上教室。這不僅解決了實體授課的地理限制，也展現了團隊在處理即時通訊、前端多媒體應用的技術整合能力。

3. 虛擬錢包架構與第三方金流儲值系統 (Virtual Wallet & ECPay Integration)
為提供流暢的預約體驗並降低每次搶課時的交易延遲，系統導入了「虛擬錢包 (Wallet)」機制。我們串接了綠界 ECPay 第三方金流進行儲值：系統會先在站內生成訂單，將加密後的交易參數帶入綠界閘道完成信用卡授權。付款成功後，系統透過非同步回呼 (Callback) 將交易紀錄寫入 wallet_log 進行稽核（Audit），並安全地更新使用者的錢包餘額。這種「先儲值、後扣款」的雙層交易架構，成功將耗時的外部金流 API 與高併發的搶課預約邏輯完美解耦 (Decoupling)，同時確保了每一筆資金流動的資料一致性與可追溯性。
---

## 📫 聯絡方式
- Email: [n7792868@gmail.com]  
- LinkedIn: [你的 LinkedIn 連結]  
- GitHub: [你的 GitHub 連結]  

---

✨ 持續學習與精進，期待在軟體開發領域中發揮專業並創造價值。

<!--
**Mihun7111/Mihun7111** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
