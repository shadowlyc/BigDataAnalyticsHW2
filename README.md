# Big Data Analytics HW2

### heatmap 圖片請到 ipynb 內看

#### 幾個參數的影響

max_depth：越小，速度越快，但是畫成圖後也比較單一，max_depth 越大，圖上形成的 block 就越多。
<br><br>
learning_rate：測試 learning_rate = 0.2 和 0.4 時的程式執行時間<br>
0.2 : 168.104151964 seconds<br>
0.4 : 155.092997074 seconds<br>
可知 learning rate 多少會影響到建立模型的時間
<br><br>
min_child_weight：建立模型最少需要的樣本數，分別用 5 跟 500 來測試（如程式碼，參考 cell 第一行的註解）
形成的圖 block 較大，但數量較少
<br><br>
subsample：決定要抽多少子樣本來建立模型，會影響到模型本身的精確度，抽的樣本多就會越接近真實的狀態
