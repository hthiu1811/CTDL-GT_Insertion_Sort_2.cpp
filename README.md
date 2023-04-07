# CTDL-GT_Insertion_Sort_2.cpp
Intertion Sort
Nguon tham khao : https://cafedev.vn/thuat-toan-insertion-sort-gioi-thieu-chi-tiet-va-code-vi-du-tren-nhieu-ngon-ngu-lap-trinh/
Vi du : 

12, 11, 13, 5, 6

Hãy để chúng ta lặp lại i = 1 (phần tử thứ hai của mảng) đến 4 (phần tử cuối cùng của mảng)

i = 1. Vì 11 nhỏ hơn 12 nên di chuyển 12 và chèn 11 vào trước 12

11, 12, 13, 5, 6

i = 2. 13 sẽ vẫn ở vị trí của nó vì tất cả các phần tử trong A [0..I-1] đều nhỏ hơn 13

11, 12, 13, 5, 6

i = 3. 5 sẽ di chuyển về đầu và tất cả các phần tử khác từ 11 đến 13 sẽ di chuyển trước một vị trí so với vị trí hiện tại của chúng.

5, 11, 12, 13, 6

i = 4. 6 sẽ chuyển đến vị trí sau 5, và các phần tử từ 11 đến 13 sẽ di chuyển trước một vị trí so với vị trí hiện tại của chúng.

5, 6, 11, 12, 13


Or ex : 
![cafedev-vi-du-thuat-toan-insertion-sort-1](https://user-images.githubusercontent.com/129465517/230522447-52994fef-75c0-4a2a-8871-a0a02786b92e.png)
