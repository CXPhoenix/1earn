<p align="center">
    <img src="./assets/img/banner/logo.png">
</p>

<p align="center">
    <img src="https://img.shields.io/badge/Category-knowledge-red.svg">
    <img src="https://img.shields.io/github/repo-size/CXPhoenix/1earn?color=yellow">
    <img src="https://img.shields.io/github/last-commit/CXPhoenix/1earn.svg?color=blue">
    <img src="https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg?color=brightgreen">
</p>

> 萬事開頭難，然後一直開頭一直難……

<p align="center">
    <img src="./assets/img/banner/readme.jpg">
</p>

* **簡介**：本專案的初衷是分享知識資源，讓更多人接觸和了解資安、運維領域，但原團隊表示：「受限於本人能力有限，難免會有錯誤和借鑑的地方，對於內容中有疑問或建議請提交 issue」。
* **定位**：ffffffff0x 團隊維護的資安知識框架
* **專案地址**：[原始 GitHub 專案頁面](https://github.com/ffffffff0x/1earn)
* **學習路線圖**：初學者或想快速建構知識結構請訪問 [roadmap](./roadmap.md)

---

## 專案檔案一覽

* **[Security](./1earn/Security/Power-PenTest.md)**

    * **[資安工具](./1earn/Security/安全工具)** - 各類資安工具的使用介紹

    * **資安資源**
        * 靶機
            * HTB
            * VulnHub
                * [DC 系列](./1earn/Security/安全資源/靶機/VulnHub/DC) - DC 系列靶場，難度簡單至中等，可以學習各種提權和 CMS 漏洞利用，推薦初學者挑戰
                * [It’s_October](./1earn/Security/安全資源/靶機/VulnHub/It’s_October)
                * [Kioptrix 系列](./1earn/Security/安全資源/靶機/VulnHub/Kioptrix) - Kioptrix 系列靶場，難度簡單至中等，推薦初學者挑戰
                * [Mission-Pumpkin](./1earn/Security/安全資源/靶機/VulnHub/Mission-Pumpkin) - 難度適中，偏向於加解密比較多，漏洞利用內容較少
                * [symfonos 系列](./1earn/Security/安全資源/靶機/VulnHub/symfonos) - 頗有難度的靶場，內容豐富，難度中等，漏洞利用內容很多，推薦有一定經驗者挑戰
            * Wargames
                * [Bandit](./1earn/Security/安全資源/靶機/Wargames/Bandit/Bandit-WalkThrough.md)

    * **BlueTeam**
        * [分析](./1earn/Security/BlueTeam/分析.md) - 分析工具與分析案例
        * [安全強化](./1earn/Security/BlueTeam/加固.md) - 系統、應用程式安全強化的方法和工具資源
        * [資安建設](./1earn/Security/BlueTeam/安全建設.md) - 有關查殺、監控、蜜罐的資源
        * [鑑識](./1earn/Security/BlueTeam/取證.md) - 內容涉及作業系統的鑑識、web 的鑑識、檔案的鑑識
        * [應急](./1earn/Security/BlueTeam/應急.md) - 應急資源、溯源案例
        * [筆記](./1earn/Security/BlueTeam/筆記) - 涉及磁碟鑑識、記憶體鑑識、USB 鑑識等內容
        * [實驗](./1earn/Security/BlueTeam/實驗) - 涉及流量分析實戰、安防設施搭建等內容

    * **Crypto**
        * [Crypto](./1earn/Security/Crypto/Crypto.md) - 介紹各種編碼和加密演算法及相關的工具

    * **CTF**
        * [CTF](./1earn/Security/CTF/CTF.md) - 收集 CTF 相關的工具和 writeup 資源
        * [writeup](./1earn/Security/CTF/writeup) - 自己參與的一些比賽記錄

    * **ICS**
        * [工控協議](./1earn/Security/ICS/工控協議.md) - 總結各類工控協議的知識點
        * [上位機資安](./1earn/Security/ICS/上位機安全.md) - 總結上位機資安相關的知識點
        * [PLC 攻擊](./1earn/Security/ICS/PLC攻擊.md) - 總結 PLC 攻擊的相關知識點
        * [S7comm 相關](./1earn/Security/ICS/S7comm相關.md) - 記錄 S7comm 相關錯誤類型、功能碼和相關參數
        * [實驗](./1earn/Security/ICS/實驗) - 模擬環境搭建和 PLC 攻擊實驗

    * **IOT**
        * 韌體資安
            * [韌體資安](./1earn/Security/IOT/固件安全/固件安全.md) - 記錄 IOT 韌體分析的知識點，包括韌體提取、韌體分析、韌體解密等
            * [實驗](./1earn/Security/IOT/固件安全/實驗) - 分析韌體實驗
        * 無線電資安
            * [實驗](./1earn/Security/IOT/無線電安全/實驗) - 無線電資安實驗
        * 硬體資安
            * [Device-Exploits](./1earn/Security/IOT/硬件安全/Device-Exploits.md) - 嵌入式設備相關漏洞利用，不太熟悉這一塊，內容不多
            * [HID](./1earn/Security/IOT/硬件安全/HID) - 和組員製作的 HID 實物記錄

    * **MobileSec**
        * [Android 資安](./1earn/Security/MobileSec/Android安全.md) - 記錄一些安卓資安相關的內容，這塊掌握較少

    * **RedTeam**
        * 安防設備
            * [Bypass 技巧](./1earn/Security/RedTeam/安防設備/Bypass技巧.md) - 記錄 WAF 繞過手段
            * [SecDevice-Exploits](./1earn/Security/RedTeam/安防設備/SecDevice-Exploits.md) - 常見的資安設備的漏洞利用方法
        * 後滲透
            * [後滲透](./1earn/Security/RedTeam/後滲透/後滲透.md) - 後滲透知識點的大綱
            * [權限提升](./1earn/Security/RedTeam/後滲透/權限提升.md) - 作業系統和資料庫的提權方法
            * [權限維持](./1earn/Security/RedTeam/後滲透/權限維持.md) - 權限維持的各種方法和資源
            * [實驗](./1earn/Security/RedTeam/後滲透/實驗)
        * 軟體服務資安
            * [CS-Exploits](./1earn/Security/RedTeam/軟體服務安全/CS-Exploits.md) - 收集軟體、業務應用服務漏洞的滲透手段和 CVE 漏洞
            * [DesktopApps-Exploits](./1earn/Security/RedTeam/軟體服務安全/DesktopApps-Exploits.md) - 收集桌面軟體的滲透手段和 CVE 漏洞
        * 協議資安
            * [Protocol-Exploits](./1earn/Security/RedTeam/協議安全/Protocol-Exploits.md) - 按照協議歸類各種漏洞、攻擊手段
        * 資訊收集
            * [連接埠資安](./1earn/Security/RedTeam/資訊收集/端口安全.md) - 記錄連接埠滲透時的方法和思路
            * [空間測繪](./1earn/Security/RedTeam/資訊收集/空間測繪.md) - 收集搜尋引擎語法資源
            * [資訊收集](./1earn/Security/RedTeam/資訊收集/資訊收集.md) - 記錄資訊收集方面各類技術，如漏洞掃描、IP 掃描、連接埠掃描、DNS 枚舉、目錄枚舉、指紋等
        * 語言資安
            * [語言資安](./1earn/Security/RedTeam/語言安全)
        * 雲端資安
            * [公有雲資安](./1earn/Security/RedTeam/雲安全/公有雲安全.md) - 雲主機利用工具，滲透案例，相關知識點
        * 作業系統資安
            * [Linux 資安](./1earn/Security/RedTeam/OS安全/Linux安全.md) - 包含 Linux 口令破解，漏洞利用、取得 Shell
            * [OS-Exploits](./1earn/Security/RedTeam/OS安全/OS-Exploits.md) - 收集作業系統的 CVE 漏洞
            * [Windows 資安](./1earn/Security/RedTeam/OS安全/Windows安全.md) - 包含 Windows PTH、PTT，漏洞利用、提權、遠端執行命令
            * [實驗](./1earn/Security/RedTeam/OS安全/實驗)
        * Web 資安
            * [前端攻防](./1earn/Security/RedTeam/Web安全/前端攻防.md) - 前端解密，繞過訪問
            * [BS-Exploits](./1earn/Security/RedTeam/Web安全/BS-Exploits.md) - 全面收集 Web 漏洞 POC | Payload | EXP
            * [IDOR](./1earn/Security/RedTeam/Web安全/IDOR.md) - 整個部分結構大部分基於烏雲的幾篇密碼找回、邏輯漏洞類文章，在其基礎上記錄和歸納
            * [靶場](./1earn/Security/RedTeam/Web安全/靶場)
            * [Web_Generic](./1earn/Security/RedTeam/Web安全/Web_Generic)
            * [Web_Tricks](./1earn/Security/RedTeam/Web安全/Web_Tricks)

    * **Reverse**
        * [Reverse](./1earn/Security/Reverse/Reverse.md)
        * [實驗](./1earn/Security/Reverse/實驗)
        * [FILE](./1earn/Security/Reverse/FILE)

* **Develop**

    * **版本控制**
        * [Git 學習筆記](./1earn/Develop/版本控制/Git學習筆記.md) - 記錄 Git 的用法和平時使用 GitHub 遇到的問題

    * **標記語言**
        * [HTML](./1earn/Develop/標記語言/HTML)
        * [JSON](./1earn/Develop/標記語言/JSON)
        * [XML](./1earn/Develop/標記語言/XML)

    * **視覺化**
        * [gnuplot](./1earn/Develop/視覺化/gnuplot)

    * **正則**
        * [regex](./1earn/Develop/正則/regex.md) - 常用正則表達式和相關資源

    * **Web**
        * [Speed-Web](./1earn/Develop/Web/Speed-Web.md)
        * [HTTP](./1earn/Develop/Web/HTTP)
        * [筆記](./1earn/Develop/Web/筆記)

* **Integrated**

    * **資料庫**
        * [Power-SQL](./1earn/Integrated/資料庫/Power-SQL.md)
        * [Speed-SQL](./1earn/Integrated/資料庫/Speed-SQL.md)
        * [筆記](./1earn/Integrated/資料庫/筆記)
        * [實驗](./1earn/Integrated/資料庫/實驗)

    * **虛擬化**
        * [Docker](./1earn/Integrated/虛擬化/Docker)

    * **Linux**
        * [God-Linux](./1earn/Integrated/Linux/God-Linux.md) - 記錄 Linux 下的特殊操作，收集的較少，後面會慢慢添加
        * [Power-Linux](./1earn/Integrated/Linux/Power-Linux.md) - 設定指南，記錄各種服務搭建與設定過程
        * [Secure-Linux](./1earn/Integrated/Linux/Secure-Linux.md) - Linux 加固+維護+應急回應參考
        * [Speed-Linux](./1earn/Integrated/Linux/Speed-Linux.md) - 命令速查手冊，記錄各種基本命令操作
        * [筆記](./1earn/Integrated/Linux/筆記)
        * [實驗](./1earn/Integrated/Linux/實驗) - 各種 Linux 服務的搭建過程和案例

    * **Network**
        * [Speed-Net](./1earn/Integrated/Network/Speed-Net.md) - 各類幀、報文格式、遮罩等
        * [Power-Net](./1earn/Integrated/Network/Power-Net.md) - 記錄 TCP/IP 協議棧的協議

    * **Windows**
        * [Secure-Win](./1earn/Integrated/Windows/Secure-Win.md) - Windows 加固+維護+應急回應參考
        * [Speed-Win](./1earn/Integrated/Windows/Speed-Win.md) - 記錄 Windows 下 CMD 常用命令
        * [筆記](./1earn/Integrated/Windows/筆記)
        * [實驗](./1earn/Integrated/Windows/實驗) - 涉及域環境搭建、基礎服務搭建
        * [Powershell](./1earn/Integrated/Windows/PowerShell/PowerShell筆記.md)

* **Plan**

    * [Misc-Plan](./1earn/Plan/Misc-Plan.md) - 各種小技巧
    * [Team-Plan](./1earn/Plan/Team-Plan.md) - 團隊協作解決方案
    * [Thinking-Plan](./1earn/Plan/Thinking-Plan.md) - 問題解決方式的記錄和學習
    * [VM-Plan](./1earn/Plan/VM-Plan.md) - VMWare 常見問題記錄

---

## 三板斧

`收集、歸納、分享` 我認為這是知識學習的「三板斧」

收集，很好理解，比如收集各種學習的資源，看過的論文、文章，和各種工具

歸納，或者說是總結與分類，將自己學習過程中的心得體會記載下來，寫成各種筆記，文章，將收集的資源整理歸類

 分享，在部落格上傳一篇文章也好，在 QQ 群幫助群友解決一個問題也好，都是分享

沒有收集和歸納的能力，整個學習的過程就像是在用一個菜籃子接水，留不住的，同樣，如果不願意分享，就像是在閉門造車，無法接觸到不同的觀點，沒人指正你的問題，久而久之有可能想法變得偏執，並且固步自封

---

## 閱讀建議

`本專案所有文件均在 VSCode 編輯器中編寫，故只相容 VSCode 側邊預覽的 Markdown 語法，暫不考慮相容其他編輯器的 Markdown 語法`

~~由於 GitHub 的 Markdown 引擎 kramdown 不支援 [TOC] 連結，以及各種不相容的排版問題，導致閱讀體驗極不友善，因此~~ 建議還是下載/clone 到本地閱讀
```
git clone --depth 1 https://github.com/ffffffff0x/1earn.git
```

建議的閱讀體驗
* [VSCode](https://code.visualstudio.com/) + [FiraCode](https://github.com/tonsky/FiraCode) (推薦，整個專案在 VSCode 環境下編寫，基本不會出現排版問題)
* [Typora](https://www.typora.io/)

> 如果 clone 速度太慢，可以先匯入碼雲中（選擇從 URL 中匯入），再進行 clone：https://blog.gitee.com/2018/06/05/github_to_gitee/?from=homepage

> 提高 release 速度，可以參考這幾篇文章 https://jinfeijie.cn/post-805.html、https://blog.csdn.net/weixin_44821644/article/details/107574297?utm_source=app

> 現在只需按下句號（.）鍵，即可啟用 web 版 VSCode 瀏覽本專案

---

以下是該專案的靈感來源

* [Micro8-滲透沉思錄](https://www.secpulse.com/archives/98814.html)
* [Teach Yourself Programming in Ten Years](http://norvig.com/21-days.html)
* [To Find a Better Solution, Ask a Better Question  Member Feature Stories  Medium](https://medium.com/s/story/to-find-a-better-solution-ask-a-better-question-3be7fee5af65)
* [The Magpie Developer](https://blog.codinghorror.com/the-magpie-developer/)

---

## CONTRIBUTORS & Thanks

- [CONTRIBUTORS](./assets/CONTRIBUTORS.md)

---

## 聯絡我

- 如果您有任何其他方面的問題或建議，可以在 issue 提出或傳送郵件至 D2hwakH7BS5E@protonmail.com

---

## Disclaimer & License

- <sup>本專案採用 [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/deed.zh) 協議。</sup>
    - <sup>共享 — 在任何媒介以任何形式複製、發行本作品。</sup>
    - <sup>改編 — 修改、轉換或以本作品為基礎進行創作在任何用途下，甚至商業目的。</sup>
    - <sup>署名 — 您必須給出適當的署名，提供指向本許可協議的連結，同時標明是否（對原始作品）作了修改。您可以用任何合理的方式來署名，但是不得以任何方式暗示許可人為您或您的使用背書。</sup>
    - <sup>沒有附加限制 — 您不得適用法律術語或者技術措施從而限制其他人做許可協議允許的事情。</sup>
- <sup>註：本專案所有檔案僅供學習和研究使用，請勿使用專案中的技術原始碼用於非法用途，任何人造成的任何負面影響，與本人無關。</sup>

---

> 由 ffffffff0x 創建
>
> 由 CXPh03n1x 使用 Cline (Grok 3) 進行翻譯；CXPh03n1x 進行確認與不適當處修正
