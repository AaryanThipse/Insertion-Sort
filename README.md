# Insertion-Sort<br>
Insertion sort is a simple sorting algorithm that works similar to the way you sort playing cards in your hands. The array is virtually split into a sorted and an unsorted part. Values from the unsorted part are picked and placed at the correct position in the sorted part.<br>
<b><ins>Characteristics of Insertion Sort:</b></ins><br>
1.This algorithm is one of the simplest algorithm with simple implementation<br>
2.Basically, Insertion sort is efficient for small data values<br>
3.Insertion sort is adaptive in nature, i.e. it is appropriate for data sets which are already partially sorted.<br>
<br>
![insertion-sort-geeksforgeeks](https://user-images.githubusercontent.com/124968304/234182613-3da3983e-d867-42b0-9173-94ae899a1afb.gif)<br>
<br>
<b><ins>Pseudo Code of Insertion Sort</b></ins><br>
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
<br>
This algorithm sorts an array of items by repeatedly taking an element from the unsorted portion of the array and inserting it into its correct position in the sorted portion of the array.<br>

1.The procedure takes a single argument, ‘A’, which is a list of sortable items.<br>
2.The variable ‘n’ is assigned the length of the array A.<br>
3.The outer for loop starts at index ‘1’ and runs for ‘n-1’ iterations, where ‘n’ is the length of the array.<br>
4.The inner while loop starts at the current index i of the outer for loop and compares each element to its left neighbor. If an element is smaller than its left neighbor, the elements are swapped.<br>
5.The inner while loop continues to move an element to the left as long as it is smaller than the element to its left.<br>
6.Once the inner while loop is finished, the element at the current index is in its correct position in the sorted portion of the array.<br>
7.The outer for loop continues iterating through the array until all elements are in their correct positions and the array is fully sorted.<br>



