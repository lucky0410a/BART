# BART
---
README: 氣球模擬風險測驗  
AUTHORS: RaccoTsai, HanTing  
NEWS: 2020/06/04  

---
```
random_score = Math.floor(Math.random()*10)+1;
```
Math.random() : 隨機產生出0~1之間的小數  
Math.floor() : 將所有的小數無條件捨去到比自身小的最大整數  
- 將Math.random()產生出來的數去乘上2就會得到0-2之間的小數，乘上3就會得到0-3之間的小數  
- Math.random()*2放進Math.floor()中就會得到0或1的結果 => 0.0000...02到1.9999...98之間的隨機小數  

Math.floor(Math.random()*x)+1 : 範圍1-x  
```
document.getElementById("random_text").value = random_score;
```
document : 此DOM（Document Object Model）的document  
- .getElementById() : 取得網頁中該 id 的第一個元素，也就是頁面中有一樣的id，則只有第一個會被取得  
- .value : 找到為此id底下的tag的value屬性值  
```
document.getElementById("alert").innerHTML = "你的氣球已經炸了!!";
```
- .innerHTML : 取得網頁內的 id 元素後，即可將想要寫入的字串或 HTML Code 寫入至 id 元素的區塊內  
```
alert("BOOM!!")
```
- alert() : 用來彈出對話視窗  
```
onclick="totalSum()"
```
- onclick = "" : JavaScript onclick 事件（Event）用來觸發某種 JavaScript 動作
