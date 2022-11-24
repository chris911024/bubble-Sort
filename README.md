# bubblesort
一次比較兩個元素，如果他們的順序錯誤就把他們交換過來，每次會將最大值升到最頂端。
## 
![image](https://user-images.githubusercontent.com/67829896/203769824-d6769c53-4213-468f-aad0-d598c4be2f2b.png)
## 第一回合
* n0, n1 開始比較，把比較大的放到右邊
* n1, n2 比較，把比較大的放到右邊
* 一直做到 n-1 與 n
## 第二回合
* n0, n1 開始比較，把比較大的放到右邊
* n1, n2 比較，把比較大的放到右邊
* 一直做到 n-2, n-1 (因為 n 已經是最大，就不需要再比了)
* 不段重複以上的流程，一直做到 n-1 回合為止，就算完成整個排序了。
