# Packing Smaller Rectangles into a Larger One
Our task is to fill Large Rectangle with given smaller ones, I encountered this problem a few years ago when I had to write a program to optimize the packing of pallets into a truck. At the time, the task was too challenging for me. The only solution I could come up with was an ugly brute-force approach, which would not have been effective anyway. As it turns out, this is an NP-hard problem, which is even described on Wikipedia:  
[Rectangle Packing on Wikipedia](https://en.wikipedia.org/wiki/Rectangle_packing#Packing_different_rectangles_in_a_given_rectangle)

During my studies, I learned about Genetic Algorithms (GA), which are perfectly suited for this type of problem.<br>
Please note that this algorithm finds very good, but rarely the most optimal solutions.
### For more information, see placement_packages.ipynb
## Here are some visualizations of found solutions:

![2522 2565](https://github.com/user-attachments/assets/302d86c0-8471-4f7e-bee8-a83b5bfdddea)
![1933 2025](https://github.com/user-attachments/assets/51fa75a2-fdab-41cc-8786-a6dd15e7393b)
![2210 2346](https://github.com/user-attachments/assets/18b90142-9500-4890-bc3a-bf17eaceefd0)
![2846 3021](https://github.com/user-attachments/assets/e9ac5754-466a-45ef-9377-03ea1a38255a)
