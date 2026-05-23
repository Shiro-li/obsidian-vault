#javascript 
# setInterval()  
  
用途：  
每隔一段時間，重複執行一次指定程式  
  
語法：  
setInterval(要執行的函式, 間隔時間)  
  
例子：  
setInterval(() => {  
console.log("Hello");  
}, 1000);  
  
結果：  
每 1000 毫秒（1秒）  
輸出一次 "Hello"  
  
理解：  
像是幫程式開啟一個自動循環計時器  
  
常見用途：  
- 倒數計時器  
- 時鐘  
- 遊戲循環  
- 自動更新畫面  
  
補充：  
1000 毫秒 = 1 秒