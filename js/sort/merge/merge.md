##合并排序（Merge sort）则是一种被广泛使用的排序方法。

**它的基本思想是，将两个已经排序的数组合并，要比从头开始排序所有元素来得快。因此，可以将数组拆开，分成n个只有一个元素的数组，然后不断地两两合并，直到全部排序完成。**


以对数组[3, 2, 4, 5, 1] 进行从小到大排序为例



1. 将数组分成[3, 2, 4]和[5, 1]两部分。

2. 将[3, 2, 4]分成[3, 2]和[4]两部分。

3. 将[3, 2]分成[3]和[2]两部分，然后合并成[2, 3]。

4. 将[2, 3]和[4]合并成[2, 3, 4]。

5. 将[5, 1]分成[5]和[1]两部分，然后合并成[1, 5]。

6. 将[2, 3, 4]和[1, 5]合并成[1, 2, 3, 4, 5]。
