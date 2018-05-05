# 学习活动单：分治法（Divide and Conquer）

## 快速排序法（Quicksort）
快速排序法比选择排序法还要迅速，对于大型的表单则更加明显。事实上，这是目前最好的排序方法之一。以下是快速排序法执行的方法。

从全部的物件中随机挑选出一个物件，然后把它放在天平的一端。

然后将它与其他剩余的物件——比较，将较轻的放在左侧，随机选出的物件放在中间，较重的则放在右侧。（有可能在结束时，两边物件的数量不一样）

选择其中一侧，将该侧所有物件重复上面的步骤。再将另一侧的物件也做一样的处理。

记得记住一开始选择的物件要保持在中间。

在剩余的物件里一直重复这些步骤，直到每一组都只剩一个物件。一旦所有物件组都只剩一个物件，所有物件便会被分成由最轻到最重的顺序。

![](/img/act7img1.png)

整个过程需要比较几次？

我们可以发现，快速排序法比选择排序法更有效率，除非你一开始就选择到最轻或者最重的那个物件。如果你够幸运，一开始就选到中间的重量，相较于需要28次才能完成的选择排序法，快速排序法能以14次比较来完成排序。在任何情况下，快速排序法都不会比选择排序法差，甚至更快速！

> 高手挑战：假如快速排序法意外的一直选到最轻的物件，则需要几次比较来获得结果？