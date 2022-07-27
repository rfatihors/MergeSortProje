# MergeSortProje
Merge Sort Projesi 
[16,21,11,8,12,22] -> Merge Sort

1-Merge sort a göre aşamalar:

 => [16,21,11] - [8,12,22]
 => [16] - [21,11] - [8,12] - [22]
 => [16] - [21] - [11] - [8] - [12] - [22]
 =>[16] - [11,21] - [8,12] - [22]
 =>[11,16,21] - [8,12,22]
 => [8,11,12,16,21,22]

2-Big-O gösterimi:
  O(nlogn) şeklinde olmalı, 6 eleman olduğundan O(6log6)
