Question:

    Create an algorithm that returns the optimal path for n number of nodes given distance and probability at each node.

    Test Case 1:

       ----------  ----------  ----------
       | Node 1 |  | Node 2 |  | Node 3 |
       ----------  ----------  ----------
           50%        65%        90%
             \         |         /
              \        |        /
             40 ft   60 ft    70 ft
                \      |      /
                 \     |     /     
                   ---------    
                   |       |
                   |  You  |   
                   |       |
                   ---------
                   
        Probability array = [.5, .65, .9]
        Distance array = [40, 60, 70]
        

    Test Case 2:

       ----------  ----------  ----------  ----------  ----------  ----------  ----------
       | Node 1 |  | Node 2 |  | Node 3 |  | Node 4 |  | Node 5 |  | Node 6 |  | Node 7 |
       ----------  ----------  ----------  ----------  ----------  ----------  ----------
           25%        50%        80%          92%          96%         98%         99%
             \         |         /            /            /           /           /
              \        |        /            /            /           /           /
             10 ft   45 ft   90 ft        100 ft       150 ft      180 ft      225 ft
                \      |      /            /            /           /           /
                 \     |     /            /            /           /           /
                   --------- ____________/            /           /           /
                   |       | ________________________/           /           /
                   |  You  | ___________________________________/           /
                   |       | ______________________________________________/
                   --------- 
                   
        Probability array = [0.25, 0.5, 0.8, 0.92, 0.96, 0.98, 0.99]
        Distance array = [10, 45, 90, 100, 150, 180, 225]
        
        
        Return an array with the best path given either test case
        
        Distance must be calculated to node and back