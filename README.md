eia-jsfl
========

* 取得jsfl安裝路徑：<br/>

> 由於不是使用 .mxp 安裝，安裝路徑需要找一下<br/>
> 不同版本的Flash，安裝路徑不同

1. 開啟Flash IDE<br/>
2. 新增`Flash JavaScript 檔案`，

	```Javascript
	// 清除 輸出畫面
	fl.outputPanel.clear();
	// 回傳為 file:/// URI 格式
	fl.trace(fl.configURI);
	// 回傳為 /Users/ 格式
	fl.trace(fl.configDirectory);
	```
	儲存<br/>
3. 隨意開一個Flash專案
4. 命令>執行命令(commands > Runcommand)，選擇剛剛的.jsfl
	就能取得安裝命令的資料夾路徑了

* 安裝命令：<br/>
	在mac 上，可以使用`symbolic link`，<br/>
	將整個eia-jsfl的路徑指到flash IDE 的命令資料夾

> 未完待續
