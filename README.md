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
