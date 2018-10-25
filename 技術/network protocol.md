# netork model

Layer-functionties-protocol-hardware-data format

# OSI

### Layer-7:Application 應用層
>* 不安全的協定:telnet(23)  ftp(20/21)  http(80)      DNS(53)
>* 安全的協定:   ssh(22)    sftp(22?)   https(443)    DNSsec(53)
>* HUb

### Layer-6:Presentation 表達層
>* 格式轉換format 加解密
>* 

### Layer-5:session 會議層
>* 
>* 

### Layer-4:Transport 傳輸層
>* TCP vs UDP
>* port address

### Layer-3:network 網路層
>* IP address
>* router(路由器):(動態路由 vs 靜態路由)[路由協定:路怎麼走 RIP BGP] 

### Layer-2:Data link 資料連結層
>* MAC address
>* switch(交換器)

### Layer-1:Physical 實體層
>* frame
>* HUb

# TCP


# TCP vs OSI

# protocol協定

### telnet
>* 遠端連線
>* 一種應用層協定
>* 1969年開發出來
>* 使用虛擬終端機的形式，提供雙向、以文字字串為主的命令列介面互動功能
>* 不安全
### ftp
>* 促進檔案的共用（電腦程式或資料）
>* 鼓勵間接或者隱式的使用遠端電腦
>* 向用戶封鎖不同主機中各種檔案儲存系統（File system）的細節
>* 可靠和高效的傳輸資料
>* 不安全
### http (HyperText Transfer Protocol)
>* 快取處理
>* 頻寬最佳化及網路連接的使用
>* 錯誤通知的管理
>* 訊息在網路中的傳送
>* 不安全
### DNS (Domain Name System)
>* 每一級域名長度的限制是63個字元，域名總長度則不能超過253個字元
>* 可以在網址列直接輸入並存取，而不需要安裝外掛程式
>* 一些駭客通過偽造DNS伺服器將用戶引向錯誤網站，以達到竊取用戶隱私資訊的目的
>* 任何一個使用IP的電腦網路可以使用DNS來實現他自己的私有名稱系統
>* 不安全
### ssh (Secure Shell)
