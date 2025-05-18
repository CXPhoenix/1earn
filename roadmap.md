# 學習路線圖

---

「文件偶爾更新，若發現連結失效或內容錯誤，歡迎透過 issue 告知我。」

---

## 前言

安全知識點非常多且繁雜，要想掌握必須花費大量時間。如果僅僅看了文章、複製貼上做個筆記、收藏了某個 POC 就認為自己會了、懂了，這種淺嘗輒止到頭來還是會坑了自己，一定要動手實踐。

美團的這篇技術文章寫得非常好：[工作中如何做好技術積累](https://tech.meituan.com/2018/04/16/study-vs-work.html)。以下是其中的一部分，分享給大家：

---

古人云：「紙上得來終覺淺，絕知此事要躬行。」學習領域有所謂的 721 模型：個人的成長 70% 來自於崗位實踐，20% 來自向他人學習，10% 來自於培訓。雖然這種理論存在爭議，但對於工程師們來說，按照實踐、學習和培訓的方式進行重要性排序，大致是不錯的。所以重視實踐，在實踐中成長是最重要的學習原則。

人類的認知有兩種：感性認知和理性認知。這兩種認知互相不可替代。實踐很大程度上來自感性學習，看書更像是理性學習。以學開汽車為例，很難想像有人能夠僅僅通過學習書本知識就會開汽車。

書本知識主要是傳道——講述抽象原型，而對其具體應用場景的講述往往含糊其辭，對抽象原型之間的關係也是淺嘗輒止。採用同樣精確的語言去描述應用場景和關聯關係將會失去重點，讓人摸不著頭腦。所以，僅僅通過看書來獲得成長就像是用一條腿走路。

重視實踐，充分運用感性認知潛能，在專案中磨練自己，才是正確的學習之道。在實踐中，在某些關鍵動作上刻意練習，也會取得事半功倍的效果。

---

以下我將以安全工程師的角度來構建一個基本的學習路線圖。由於我個人偏向 Web 與 Misc，因此不包含逆向內容，請見諒。

如果您擅長逆向、Pwn、Mobile 安全或其他安全相關技能，且提供了相關教學或部落格、筆記等，歡迎提交 PR，一起構建此路線圖。

![](./assets/img/roadmap.png)

## 入門知識

基本功很重要

- 虛擬機使用 - 學會安裝、使用虛擬機，明白 VMware 幾種網路連接的區別
    - 略

- 如何科學上網 - 懂的都懂
    - 略

- Markdown 語法 - 學會記筆記也很重要
    - 略

---

## 基礎開發知識

- 字元編碼 - 沒什麼好說的，基本功
    - 略

- Git 及 GitHub 的使用 - 多參與開源專案可以快速提高開發水平
    - [Git 學習筆記](./1earn/Develop/版本控制/Git學習筆記.md)

- 資料類型的處理
    - XML
    - JSON

- 正則表達式 - 了解正則語法
    - [Regex](./1earn/Develop/正則/regex.md)

- Python - 掌握語法，能夠編寫 POC，能夠按需求修改 EXP
    - 略

---

## WEB 開發

- DotNet
    - 暫時還沒學完 : )

- Java
    - 暫時還沒學完 : )

- PHP
    - 暫時還沒學完 : )

---

## 基礎運維知識

### Linux 運維

- Linux 是什麼
    - [發行版](./1earn/Integrated/Linux/筆記/發行版.md)
    - [程序](./1earn/Integrated/Linux/筆記/程序.md)

- Linux 基礎指令
    - [Speed-Linux](./1earn/Integrated/Linux/Speed-Linux.md)

- Linux 服務搭建 - 至少要學會怎麼搭建 httpd、nginx
    - [Power-Linux](./1earn/Integrated/Linux/Power-Linux.md)

- Docker 使用 - 必須要掌握的，可以節省您大量時間
    - [Speed-Docker](./1earn/Integrated/虛擬化/Docker/Speed-Docker.md)

### 網路知識

- TCP/IP 模型 - 需要明白什麼是 IP、MAC，各層的常見協議有哪些及分別的作用
    - 略

### Windows 伺服器

- Windows 下常用指令
    - [Speed-Win](./1earn/Integrated/Windows/Speed-Win.md)

- Windows 伺服器能做什麼
    - [Windows 基礎服務搭建](./1earn/Integrated/Windows/實驗/Windows基礎服務搭建.md)

---

## Web 基礎

- HTTP 協議
    - 略

- HTML + JS
    - 略

- Web 基礎漏洞
    - [Web_Generic](./1earn/Security/RedTeam/Web安全/Web_Generic/Web_Generic.md)

- Web 邏輯漏洞
    - [IDOR](./1earn/Security/RedTeam/Web安全/IDOR.md)

- 靶場 - 如果有空閒時間可以打打靶場練習
    - [靶場](https://github.com/No-Github/1earn/tree/master/1earn/Security/RedTeam/Web%E5%AE%89%E5%85%A8/%E9%9D%B6%E5%9C%BA)

## Web 進階

- 各類通用漏洞利用
    - [BS-Exploits](./1earn/Security/RedTeam/Web安全/BS-Exploits.md)

- OOB
    - [OOB](./1earn/Security/RedTeam/Web安全/Web_Tricks/OOB.md)

- JWT
    - [JWT 安全](./1earn/Security/RedTeam/Web安全/Web_Tricks/JWT安全.md)

## 原始碼檢測

- 暫時還沒學完 : )

---

## 主機安全

### Linux

- Linux 權限、檔案
    - [認證](./1earn/Integrated/Linux/筆記/認證.md)
    - [檔案](./1earn/Integrated/Linux/筆記/檔案.md)

- Linux 提權、漏洞利用
    - [OS-Exploits](./1earn/Security/RedTeam/OS安全/OS-Exploits.md#linux)

- Linux LOL
    - [Linux 安全](./1earn/Security/RedTeam/OS安全/Linux安全.md#lol)

### Windows

- Windows 認證體系
    - [認證](./1earn/Integrated/Windows/筆記/認證.md)

- Windows 提權、漏洞利用
    - [OS-Exploits](./1earn/Security/RedTeam/OS安全/OS-Exploits.md#windows)

- Windows LOL
    - [Windows-LOL](./1earn/Security/RedTeam/OS安全/實驗/Windows-LOL.md)

- Windows RDP 利用
    - [Windows 安全](./1earn/Security/RedTeam/OS安全/Windows安全.md#rdp)

- Windows 憑證抓取
    - [Windows 安全](./1earn/Security/RedTeam/OS安全/Windows安全.md#認證)

---

## 後滲透

### 權限提升

- Linux 提權
    - [OS-Exploits](./1earn/Security/RedTeam/OS安全/OS-Exploits.md#linux)

- Windows 提權
    - [OS-Exploits](./1earn/Security/RedTeam/OS安全/OS-Exploits.md#windows)

- 第三方軟體提權
    - [權限提升](./1earn/Security/RedTeam/後滲透/權限提升.md)

### 權限維持

- 各種 WebShell
    - [權限維持](./1earn/Security/RedTeam/後滲透/權限維持.md#web)

- Windows 權限維持
    - [權限維持](./1earn/Security/RedTeam/後滲透/權限維持.md#win)

- Linux 權限維持
    - [權限維持](./1earn/Security/RedTeam/後滲透/權限維持.md#linux)

- 各類 C2、免殺
    - [權限維持](./1earn/Security/RedTeam/後滲透/權限維持.md#c2-rat)

### Windows 域

- 工作組、域是什麼、如何搭建域環境
    - [工作組](./1earn/Integrated/Windows/筆記/工作組.md)
    - [域](./1earn/Integrated/Windows/筆記/域.md)
    - [Windows 域搭建](./1earn/Integrated/Windows/實驗/Windows域搭建.md)

- Kerberos
    - [認證](./1earn/Integrated/Windows/筆記/認證.md#域認證)

- 域憑證抓取
    - [Windows 安全](./1earn/Security/RedTeam/OS安全/Windows安全.md#域)

- 域控提權
    - [OS-Exploits](./1earn/Security/RedTeam/OS安全/OS-Exploits.md#域)

- PTH/K/T
    - [PTH](./1earn/Security/RedTeam/OS安全/Windows安全.md#pth)
    - [PTT](./1earn/Security/RedTeam/OS安全/Windows安全.md#ptt)

- Exchange
    - [Exchange 搭建](./1earn/Integrated/Windows/實驗/Exchange搭建.md)
    - [Exchange](./1earn/Security/RedTeam/後滲透/實驗/Exchange.md)

---

## 藍隊技能

### 藍隊服務搭建

### 分析技術

- Linux 日誌、資訊
    - [日誌](./1earn/Integrated/Linux/筆記/日誌.md)
    - [資訊](./1earn/Integrated/Linux/筆記/資訊.md)

- Windows 日誌、資訊
    - [日誌](./1earn/Integrated/Windows/筆記/日誌.md)
    - [資訊](./1earn/Integrated/Windows/筆記/資訊.md)

- 惡意檔案分析
    - [分析](./1earn/Security/BlueTeam/分析.md)

### 鑑識技術

- 檔案鑑識
    - [鑑識](./1earn/Security/BlueTeam/取證.md#檔案取證)

- 記憶體鑑識
    - [記憶體鑑識](./1earn/Security/BlueTeam/筆記/記憶體取證.md)

- 流量分析
    - [流量分析](./1earn/Security/BlueTeam/實驗/流量分析.md)

- 應用程式、WEB、資料庫鑑識
    - [鑑識](./1earn/Security/BlueTeam/取證.md#應用程式取證)
