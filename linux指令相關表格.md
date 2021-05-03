# linux指令整理

## file&directory指令
|   |file          |directory  |
|---|--------------|-----------|
|新增|Touch.vim.nano|mkdir      |
|修改|cp.mv         |cp –r.mv   |
|刪除|rm -f         |Rmdir.rm –r|
|查詢|ls.ll.find    |ls.ll.find |



## user&group指令
| |user|group|
|-|----|-----|
|新增|useradd|groupadd|
|修改|usermod|groupmod|
|刪除|userdel|geoupdel|
|查詢|id.w.who.whoami|id.w.who.whoami|



## 檔案&目錄權限
|   |file          |directory  |
|---|--------------|-----------|
|r|內容可讀|列表|
|d|可編修(不一定可刪除)|可新增&刪除|
|x|可執行|可執行shell|
