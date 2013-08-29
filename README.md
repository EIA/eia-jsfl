eia-jsfl
========

* 安裝jsfl命令:
先開啟Flash IDE 介面,<br/>
並在命令>執行命令<br/>
 (commands > Runcommand)


```Javascript
  // 清除 輸出畫面
  fl.outputPanel.clear();
  // 回傳為 file:/// URI 格式
  fl.trace(fl.configURI);
  // 回傳為 /Users/ 格式
  fl.trace(fl.configDirectory);
```
就能取得安裝命令的路徑了




