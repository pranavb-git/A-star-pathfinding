# A-star-pathfinding
A* Pathfinding algorithm implemented in Python and visualisation through pygame

Run the main.py file on IDE with an interpreter having **_pygame_** (preferably Python **3.10**)

A* achieves better performance by using heuristics to guide its search.
more about A* on wiki : https://en.wikipedia.org/wiki/A*_search_algorithm

First click marks the cell to be **Source** point and Second click marks the cell to be **Destination** point 

<img width="300" alt="1" src="https://github.com/pranavb-git/A-star-pathfinding/assets/121572703/9970344a-f3ee-4195-b588-42275608b568"> <img width="300" alt="2" src="https://github.com/pranavb-git/A-star-pathfinding/assets/121572703/96dddb17-c351-457a-80ce-43a5302d17e3">

Any further clicks, convert the cells into **barriers**, we can create a pattern of walls which can't be entered 

<img width="300" alt="3" src="https://github.com/pranavb-git/A-star-pathfinding/assets/121572703/4ab6f791-d62a-49e0-bb53-e551749df30c">

We can use right click to reset the cell (to turn the cell white). This can be used to reset the postions of Source and Destination as well.

Upon pressing the SPACE bar, the A-star pathfinding algorithm starts executing. We use heuristics to optimally find the path. All the element that enter the open set are marked green and later marked red once the exit the set.

<img width="200" alt="4" src="https://github.com/pranavb-git/A-star-pathfinding/assets/121572703/eb21ee48-e0ac-4260-85e1-82771e99cf2c">   .   <img width="200" alt="5" src="https://github.com/pranavb-git/A-star-pathfinding/assets/121572703/d28ec946-0a9a-4dd9-9adf-7b0f18d034a6">   .   <img width="200" alt="6" src="https://github.com/pranavb-git/A-star-pathfinding/assets/121572703/9da2f257-b4bc-448b-bf28-239301a4529c">

Once the destination is reached, We reconstruct the path and mark the path in Violet color

<img width="300" alt="8" src="https://github.com/pranavb-git/A-star-pathfinding/assets/121572703/82c7dab4-4c04-4e1a-900c-eadeea7585a7">

Press **C** to clear the board completely.

Press **R** to reset,i.e. Clear the board retaining the Source and Destination along with the Barriers.

<img width="300" alt="3" src="https://github.com/pranavb-git/A-star-pathfinding/assets/121572703/4ab6f791-d62a-49e0-bb53-e551749df30c">


Grid size is set to be 40 x 40 . We can change the size of grid by changing the value of ROWS to desired value which is a factor of 800.

Thank You
