# 0414linux note
## CentOS8新增鍵盤語言
### 以下新增"倉頡"鍵盤為例

+ 概覽=>顯示應用程式=>地區和語言=>新增"+"=>選擇想要語言=>完成

+ 若找不到想要的輸入法時，可透過終端機新增，路徑如下
  + 概覽=>終端機=>指令 yum install ibus-table-chinese-cangjie=>登出作業系統再登入即可完成

## linux遠端連線
### putty連接CMD
+ 下載並安裝putty,下載完成後開啟檔案
  + host name輸入想連線的電腦ip，複製到下方saved sessions儲存即可開啟
  + 輸入指令systemctl status cockpit.socket即可進入,按Q鍵即可跳出
### IP連線操作圖形化介面
+ 網頁輸入IP網址連接埠9090,格式:xxx.xxx.xxx.xxx:9090
+ 登入管理者帳密即可進入進行操作 
