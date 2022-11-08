## OSI 模型與TCP/IP protocal suite

## OSI有七層?簡述其功能
- OSI有七層
  - 實體層
    - 該層包括涉及資料傳輸的實體設備。 
  - 資料連結層
    - 促進兩者之間的資料傳輸。
  - 網路層
    - 負責促進兩個不同網路之間的資料傳輸。
  - 傳輸層
    - 也負責處理流量控制和錯誤控制。
  - 工作階段層
    - 該層負責處理開啟和關閉兩個裝置之間的通訊。
  - 呈現層
    - 該層主要負責準備資料以供應用程式層使用
  - 應用程式層
    - 這是唯一一個直接與來自使用者的資料進行互動的層。

## 底下網路設備運作在哪一層? Hub, switch, router, L4-switch, proxy
## TCP/IP有那些層?寫出與OSI七層模型的對應!

## 簡述底下應用層協定(英文全名與簡單功能說明):
- HTTP vs HTTPs
  - HTTP
    - HyperText Transfer Protocol 超文本傳輸協定
    - HTTP是一種用於分佈式、協作式和超媒體訊息系統的應用層協定
    - HTTP是全球資訊網的數據通信的基礎。
  - HTTPS
    - 超文本傳輸安全協定（HyperText Transfer Protocol Secure，HTTPS；
    - 常稱為HTTP over TLS、HTTP over SSL或HTTP Secure
    - HTTPS是一種透過計算機網路進行安全通訊的傳輸協定。
    - HTTPS經由HTTP進行通訊，但利用SSL/TLS來加密封包。
    - HTTPS開發的主要目的，是提供對網站伺服器的身分認證，保護交換資料的隱私與完整性。
 - DNS vs DNSsec
   - DNS
      - DNS的原始設計不包含任何安全細節；相反的，它被設計成一個可擴增的分散式系統(Distributed system)。 域名系統安全擴展
    - DNSsec
      - DNSSEC嘗試在其中添加安全性，同時仍保持向下相容性。
 - telnet vs ssh
   - telnet
      - telnet是明码传输
   - ssh 
      - SSH是加密传输
  - ftp vs sftp
    - ftp
       - ftp連接到在遠程主機上的FTP伺服器程序。用戶通過客戶機程序向伺服器程序發出命令，伺服器程序執行用戶所發出的命令，並將執行的結果返回到客戶機。
     - sftp
        - 一種多傳輸協議，相當於加密版的FTP。當你在FTP伺服器上收發文件的時候，你面臨兩個風險。
  - smtp, pop3
    - pop3
      - pop3透過電腦上的Outlook將主機上的信件下載到電腦上，如果Outlook沒有特別設定，Outlook不會將主機上的郵件刪除。
     - smtp
        - smtp舉例來說，你使用Outlook把10封信下載到電腦上，你看完信後，將其中的兩封信刪除，這個狀態會被同步到主機上、主機上的這兩封信也會被刪除。
    - SNMP
      - SNMP 是用於管理和監視網路元素的廣泛接受的通訊協定之一。大多數專業級網路元素都具有配套的 SNMP 代理程式。必須啟用并設定這些代理程式，以與網路管理系統 (NMS) 進行通訊。
## 簡述底下傳輸層協定(英文全名與簡單功能說明):TCP vs UDP
- TCP
  - reliable(可靠的) vs unreliable(不可靠的)
  - TCP three-way handshaking(三項交握)  
     - TCP 是一種 連接導向 (connection-oriented) 的通訊協定，是其建立虛擬連線 (virtual connection) 的方式。
  - TCP syn flood attack
## 簡述底下網路層協定(英文全名與簡單功能說明): IP   ICMP
  - IP
      - 標識主機：更具體地說，標識其網路介面，並且提供主機在網路中的位置。
  - ICMP
      - 在lP主機、路由器之間傳遞網路通不通、主機是否可達、路由是否可用等反映網路本身狀況的控制消息。
