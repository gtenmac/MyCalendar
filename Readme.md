# MyCalendar 我的行事曆
    這是在Build School高壓的前端訓練，所完成的作品。

## 技術
### - Bootstrap
### - JavaScript
### - Google Map API
### - Fontawesome

## 設計概念
* 透過Bootstrap設計出網頁框架
* 透過JavaScript來計算年月日，並且用Selector來精準地控制版面，並動態增加行事曆內容
* 每一個行程透過loaclStorage來存放，用年月日(2018-10-29)當作key，Value用JSON存放行程內容
* 透過新增行程裡的地圖，透過API來轉換經緯度，並一起存放然後標記起來
* 每個日曆上的行程是一個Button，而在新增的時候就會註冊onclick以便於修改，並且也會把這個行程的Index放在Button的Value，就不必再比對是哪一個行程而在刪除。
## 圖片
![Alt text](https://github.com/gtenmac/MyCalendar/blob/master/%E8%A1%8C%E4%BA%8B%E6%9B%86.png)