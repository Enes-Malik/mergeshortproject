# Merge Short Projet
### Proje 2
##### [16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız. <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[16,21,11,8,12,22]<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[16,21,11] &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;   [8,12,22]<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[16,21]&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[11] &nbsp;&nbsp;&nbsp;&nbsp;[8,12]&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [22]<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[16]&nbsp;&nbsp;&nbsp;&nbsp; [21]&nbsp;&nbsp;&nbsp;&nbsp; [11]&nbsp;&nbsp;&nbsp;&nbsp; [8]&nbsp;&nbsp;&nbsp;&nbsp; [12]&nbsp;&nbsp;&nbsp;&nbsp; [22]<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[16,21]&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[11] &nbsp;&nbsp;&nbsp;&nbsp;[8,12]&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [22]<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[11,16,21] &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;   [8,12,22]<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[8,11,12,16,21,22]<br>

Sorgu sayısı n-1. n dominant faktör bu yüzden big-o notaion O(n)
İşlem her seferinde yarıya iniyor \(2^x=n\) -> \(logn=x\) big-o notain O(\(logn\))
Time comlexity = O(\(nlogn\))