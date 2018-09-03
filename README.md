# SortAlgorithm

> 非线性时间比较类排序：通过比较来决定元素间的相对次序，由于其时间复杂度不能突破O(nlogn)，因此称为非线性时间比较类排序。

> 线性时间非比较类排序：不通过比较来决定元素间的相对次序，它可以突破基于比较排序的时间下界，以线性时间运行，因此称为线性时间非比较类排序。 

| 排序算法 |	时间复杂度(平均) | 时间复杂度(最坏) | 时间复杂度(最好) | 空间复杂度 | 稳定性 |
|--------|--------|--------|--------|--------| --------| 
| 冒泡排序 |	O(n<sup>2<sub>) | O(n<sup>2<sub>) | O(n) | O(1) | 稳定 |
| 选择排序 |	O(n<sup>2<sub>) | O(n<sup>2<sub>) | O(n<sup>2<sub>) | O(1) | 不稳定 |
| 插入排序 |	O(n<sup>2<sub>) | O(n<sup>2<sub>) | O(n) | O(1) | 稳定 |
| 希尔排序 |	O(n<sup>1.5<sub>) | O(n<sup>2<sub>) | O(n) | O(1) | 不稳定 |
| 快速排序 |	O(N*logN) | O(n<sup>2<sub>) | O(N*logN) | O(N*logN) | 不稳定 |
| 归并排序 |	O(N*logN) |	O(N*logN) |	O(N*logN) | O(n) | 稳定 |
| 堆排序	| O(N*logN) | O(N*logN) | O(N*logN) | 不稳定 |
| 基数排序 |	O(d(n+r)) | | | O(n+r) | 稳定 |