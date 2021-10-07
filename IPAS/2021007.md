# 管理_1_資訊安全管理概念

- [資安威脅](#資安威脅)

- [資通安全目標CIA](#資通安全目標CIA)

資通安全風險之形成

NIST網路安全框架(CSF)
   目的
NIST風險評估架構

MITRE ATT&CK
MITRE DEfend(2021)
MITRE ENgage(2021)
ZERO trust network

## 資安威脅
- IOT security
  - 控制智慧燈泡的橋接器裝置CVE-2020-6007
  - [CVE](https://cve.mitre.org/)
  - [NATIONAL VULNERABILITY DATABASE](https://nvd.nist.gov/vuln/detail/CVE-2020-6007)
- printer security  
  - [8萬臺印表機連接埠可從公開網路存取有被駭之虞，臺灣曝險印表機數量全球第三(2020)](https://www.ithome.com.tw/news/138421)
    - IPP連接埠網際網路列印協定（Internet Printing Protocol，IPP）
    - TCP 631埠發送呼叫，結果一天內就偵測到79,174臺印表機，這些印表機都因未加裝防火牆，而直接可由IPv4網際網路上查詢到。
    - 約5.8萬臺的IPP實作是CUPS（Common Unix Printing System，Unix通用列印系統）
    - [Exploiting Multifunction Printers During A Penetration Test Engagement](https://medium.com/@nickvangilder/exploiting-multifunction-printers-during-a-penetration-test-engagement-28d3840d8856)
  - [微軟Windows列印多工緩衝處理器(Print Spooler)](https://www.ithome.com.tw/news/145579)
    - CVE-2021-34527  == >遠端執行任意程式碼
    - [微軟Windows列印多工緩衝處理器(Print Spooler)存在安全漏洞(CVE-2021-34527)，允許攻擊者遠端執行任意程式碼，請儘速確認並進行防護補強！]()
- DDOS
  - [DDOS 2021 ithome專刊](https://www.ithome.com.tw/tags/ddos) 
  - [DDoS攻擊 ithome專刊](https://www.ithome.com.tw/tags/ddos%E6%94%BB%E6%93%8A)
  - [殭屍網路發動大規模DDoS攻擊，每秒發出逾1,700萬次HTTP請求2021-08-23](https://www.ithome.com.tw/news/146339)
- APT
- Ransomeware
  - [Targeted Ransomware](https://www.ithome.com.tw/tags/targeted-ransomware) 
  - [勒索軟體任務小組（Ransomware Task Force）ithome 2020-12-23](https://www.ithome.com.tw/news/141825)

## 資通安全目標CIA

### 資訊安全重要基本觀念
```
機密性(Confidentiality)
完整性(Integrity)
可用性(Availability)

鑑別性(Authenticity)
可靠度(Reliability)
不可否認性(Non-repudiation)
可歸責性(Accountability)
```
```
邊界與分類(Boundary and classification)
職務區隔(Segregation of duties, SOD)
縱深防禦(Layered defense, defense in depth)
單一脆弱點(Single point of failure, SPOF)
阿奇里斯腱(Achilles heel)
木桶理論(Bucker principle）
僅知原則(Need to know)
```

### 資訊安全目標_機密性、完整性與可用性
```
   1.1.1.CIA
   1.1.2.各種破壞CIA的情境
   1.1.3.保護CIA的方法
```

### 資通安全的主要目標:CIA triad:

- 資通安全的主要目標，基本上就是保護資訊的「機密性(Confidentiality)」、「完整性(Integrity)」及「可用性(Availability)」(簡稱C.I.A.)

- [機密性](https://zh.wikipedia.org/wiki/%E4%BF%9D%E5%AF%86)[(Confidentiality)](https://en.wikipedia.org/wiki/Confidentiality)
  - 防止【非授權人員】<<存取>>資訊，確保資訊秘密性
- 完整性(Integrity)
  - 防止【非授權人員】<<竄改>>資訊，確保資訊正確性
- 可用性(Availability)
  - 防止系統故障或人為惡意【阻斷服務DOS/DDOS】，確保{資訊與資訊處理}<<服務>>的可獲得性

- 法規遵循(Law compliance)
  - [守規（Regulatory compliance； 法遵；合規）](https://zh.wikipedia.org/wiki/%E5%AE%88%E8%A7%84)，指公司或機構需採取措施確保其行為（包括員工的行為）遵守相關的法律、法規 

```
[51]下列何者是「機密性」的正確意涵？
(A) 確保被使用的為正確資料，未遭人竄改   (B) 確保網路通訊中的參與者，不會拒絕承認他們的行為
(C) 確保資訊服務隨時可被取用            (D) 防止未經授權的人或系統存取資料或訊息
```

```
[52]請問「確保已授權之使用者可適時、可靠的存取資料與資源」所代表的意義是下列何者？
(A) 機密性  (B) 完整性   (C) 可用性    (D) 可讀性
```

## 資訊安全管理系統(ISMS)
```
   1.2.1.資訊安全管理系統（Information Security Management System, ISMS）
   1.2.2.導入ISMS的目的
   1.2.3.導入ISMS的過程與程序
   1.2.4.導入ISMS的關鍵主義事項
```
