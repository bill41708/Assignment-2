# Assignment 2

###  資料標準化

* 除以255

* 因為每個像素都是在0 到 255 之間，標準化之後就變成了 0 到 1 之間



沒有加dropout以前 traindata的準確率有0.9982 可是testdata準確率只有0.980
以0.2dropout為例  traindata的準確率為0.9954 testdata準確率有0.984
因此加上dropout後才不訓練過於請傾向訓練資料
