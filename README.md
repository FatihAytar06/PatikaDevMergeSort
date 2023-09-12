# PatikaDevMergeSort

## [16, 21, 11, 8, 12, 22]

1. Adım dizi parçalara ayrılır:

[16, 21, 11] | [8, 12, 22]

[16] | [21, 11] | [8] | [12, 22]

[16] | [11, 21] | [8] | [12, 22]

2. Adım parçalar birleştirilir:

[11, 16, 21] | [8, 12, 22]

[8, 11, 12, 16, 21, 22]

Big-O gösterimi = O(nlogn)
