>排序算法总结
 
排序法 | 平均时间 | 最坏情况 | 稳定度 | 备注        
----- | ------- | ------- | ----- | ------------
冒泡法 |  O(n*n) |  O(n*n) | 稳定   | n小时较好(简单)
选择法 |  O(n*n) |  O(n*n) | 不稳定 | n小时较好(简单)
直接插入法 | O(n*n) | O(n*n) | 稳定   | 大部分已排序较好
快排法 | O(nlogn) | O(n*n) | 不稳定 | n大时较好，基本有序时不好(复杂)
归并法 | O(nlogn) | O(nlogn) | 稳定 | n大时较好(较复杂)
希尔法 | O(nlogn) | O(nlogn) | 不稳定 | n小时较好(较复杂)
堆排序 | O(nlogn) | O(nlogn) | 不稳定 | n大时较好(较复杂)

- O(n*n)性能

平方阶：冒泡法、选择排序法、直接插入法

稳定性：冒泡法和直接插入法稳定，选择排序不稳定

性能：数据规模小时，直接插入和选择排序差不多；数据规模大时，冒泡最差；

- O(nlogn)性能

对数阶：快排法、归并、希尔和堆排序

稳定性：快排、希尔和堆排序不稳定，归并稳定

性能：快排效率最高，不适合大数据，且基本有序时接近冒泡排序；归并排序效率不错，数据规模大时，优于希尔和堆排序；堆排序在大数据时效果很明显；
 
