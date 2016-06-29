Question:

   You have two linked lists, describe a function that returns the pointer to a node where they intersect
   
   Test Case 1:
   
       [1, 2, 3, 4, 5, 6, 7, 8 ...]
                    |
                    |
                  Node 5
                    |
                    |
       [3, 4, 8, 2, 5, 7, 1, 9 ...]

       Find pointer to node 5
       
    Test Case 2:
    
        [3, 4, 5]
          \
           \
          Node 3
             \
              \
        [9, 11, 3, 8, 1 ...]
        
        Find pointer to node 3