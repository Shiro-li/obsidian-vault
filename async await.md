
### 寫法範例

```js
async function fetchUserData(){
	const response = await fetch('/api/user');
	const data = await responese.json();
	
	console.log(data);
	return data;
}
```

- 由 `async` 的 function 開頭，搭配 `await` 等函式處理完才執行
	所以能實現讓非同步的程式語言，以同步的寫法呈現
- `async` 的本質就是 `promise`，也會有成功跟失敗 
- `await` 的等待目標是一個 `promise` 
- 要加上 `try/catch` 語法

### 為什麼需要 async/await  ?

避免 promise chaining (.then) 過多，讓程式更可讀。

[[promise]]