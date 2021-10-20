開放式系統互聯模型 Open System Interconnection Model
https://zh.wikipedia.org/wiki/OSI%E6%A8%A1%E5%9E%8B

第七層 應用層（application layer）    L7-switch交換器    https://zh.wikipedia.org/wiki/%E5%BA%94%E7%94%A8%E5%B1%82
應用層直接和應用程式介面結合   ex:AFP,APPC,BitTorrent,CFDP,DHCP,DNS,FTAM,FTP,Gopher,HTTP,IMAP,iTMS,IRC,LDAP,Modbus,NFS,NNTP,NTP,POP3,SIP,SMB,SMTP,SNMP,SNTP,SSH,Telnet,TFTP,TSP,XMPP
  
第六層 表達層（presentation layer）   https://zh.wikipedia.org/wiki/%E8%A1%A8%E7%A4%BA%E5%B1%82
提供資料和資訊正確的語法表示變換方法  資料語法轉換,語法表示,連接管理,資料處理:資料加密和解密,資料壓縮和解壓,資料編碼和解碼   協定:HTTP/HTTPS,FTP/FTPS,SSH

第五層 會議層（session layer）    https://zh.wikipedia.org/wiki/%E4%BC%9A%E8%AF%9D%E5%B1%82
服務:認證（Authentication）,權限（Permissions）,會話恢復（Session restoration）   功能:為對談實體間建立連接,資料傳輸階段,連接釋放   協定:PAP(密碼認證協定),PPTP(點對點隧道協定),RTCP(實時傳輸控制協定),SMPP,ZIP

第四層 傳輸層（transport layer）    L4-switch交換器    https://zh.wikipedia.org/wiki/%E4%BC%A0%E8%BE%93%E5%B1%82
服務:連接導向式通訊,相同次序交付,可靠性,流量控制,擁塞避免,多路復用    協定:TCP,UDP,SPX

第三層 網路層（network layer）    Router路由器 L3-交換器(ASIC)    https://zh.wikipedia.org/wiki/%E7%BD%91%E7%BB%9C%E5%B1%82
使用IP位址來唯一標識網際網路上的裝置   協定:IP(V4,V6) 裝置:路由器

第二層 資料連結層（data link layer）    switch交換器   https://zh.wikipedia.org/wiki/%E6%95%B0%E6%8D%AE%E9%93%BE%E8%B7%AF%E5%B1%82
用於區域網路  裝置:網卡 橋接器 交換機

第一層 實體層（physical layer）   Repeater中繼器 Hub集線器    https://zh.wikipedia.org/wiki/%E7%89%A9%E7%90%86%E5%B1%82
傳輸原始資料(Byte) ex:乙太網路 數據機 光纖 雙絞線

![OSI](https://user-images.githubusercontent.com/43432054/138026129-d0019bc7-81c5-4571-96bf-14f7417ab9ac.png)
