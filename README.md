# Minesweeper With LVGL on STM32F746GDISCO

自行移植[LVGL](https://lvgl.io/)至STM32F746G-DISCO開發版，製作Minesweeper(踩地雷)遊戲

##### 基本功能：
>  1. 開機後自動進入設定畫面，設定炸彈數量5 - 99，設定完成後開始遊戲。
>  2. 炸彈需”隨機”放置於15*8的畫面中。
>  3. 遊戲中左上角顯示炸彈總數量。
>  4. 遊戲中右上方顯示遊戲開始時間(分:秒)。
>  5. 點擊的點周邊八個點若有炸彈，顯示炸彈數量。
>  6. 點擊的點不是炸彈或炸彈周圍八個點，顯示空白，並且把相連結的空白部分全部顯示出來，直到周邊有炸彈的點。
>  7. 畫面中只剩下炸彈點未點開時顯示Win ，遊戲時間停止。
>  8. 點擊到炸彈點後顯示Fail ，並且顯示所有炸彈位置，遊戲時間停止。
>  9. 遊戲結束後，按下USR 按鍵進入設定畫面。
>  10.使用LVGL完成GUI畫面。

##### 使用環境：
>  1. STM32CubeMX Version 6.4.0
>  2. Keil µVision V5.36.0.0

##### Library
>  1. [Light and Versatile Graphics Library](https://lvgl.io/)

#### 執行結果：
<img src="https://i.imgur.com/8IuN0Zd.jpg" width="403" height="302" /><img src="https://i.imgur.com/wamN9LD.jpg" width="403" height="302" />
<img src="https://i.imgur.com/9YmiwQ3.jpg" width="403" height="302" /><img src="https://i.imgur.com/dLhtLtv.jpg" width="403" height="302" />
