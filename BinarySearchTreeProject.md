#1 Write binary search tree steps of given array [7, 5, 1, 8, 3, 6, 0, 9, 4, 2]

[0, 1, 2, 3, 4, 5, 6, 7, 8, 9]

                                          5       ==> 5 is the root
                                       /     \
                                     2         8
                                   /   \      /  \
                                  1     3    6    9      ==> numbers larger than 9, must follow the right side of the path
                                 /       \       /
==> negative numbers must       0         4     7
take place under zero 
to the left
