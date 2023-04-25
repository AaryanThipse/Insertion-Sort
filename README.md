# Insertion-Sort<br>
Insertion sort is a simple sorting algorithm that works similar to the way you sort playing cards in your hands. The array is virtually split into a sorted and an unsorted part. Values from the unsorted part are picked and placed at the correct position in the sorted part.<br>
<b><ins>Characteristics of Insertion Sort:</b></ins><br>
1.This algorithm is one of the simplest algorithm with simple implementation<br>
2.Basically, Insertion sort is efficient for small data values<br>
3.Insertion sort is adaptive in nature, i.e. it is appropriate for data sets which are already partially sorted.<br>
<br>
![insertion-sort-geeksforgeeks](https://user-images.githubusercontent.com/124968304/234182613-3da3983e-d867-42b0-9173-94ae899a1afb.gif)<br>
<br>
<b><ins>Pseudo Code of Insertion Sort</b></ins>
procedure insertionSort(A: list of sortable items)<br>
   n = length(A)<br>
   for i = 1 to n - 1 do<br>
       j = i<br>
       while j > 0 and A[j-1] > A[j] do<br>
           swap(A[j], A[j-1])<br>
           j = j - 1<br>
       end while<br>
   end for<br>
end procedure<br>



