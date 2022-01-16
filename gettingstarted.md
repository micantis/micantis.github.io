# Getting Started with Micantis WorkBook

Here are three basic functions to try in **WorkBook**:

Preface: All of the naviagation in the application happens via the button with three horizontal lines in the top left corner of the app window. This button opens the naviagation sidebar.

![WorkBook's navigation button](/images/workbook_home.png)

### 1. Graph some data. 
A. Click the three horizontal lines (naviagation) button in the top left corner of the window, and pick Graphs.
B. You'll see a list of data starting with most recent. You can double click on a few different items in the table to select them (tip: you can also right click on an item for more options).
C. Then choose a graph type from the drop-down menu at the bottom to open the graph. 
D. There are lots of options on the graph, including zooming in/out, adding/removing Y-axes, changing scales, and more. Right clicking offers you a menu as well. There's an "i" button in the bottom-right of the graph window that has helpful tips.

### 2. Create a cell. 
A. When you first open the software, it starts on the "Cells" table (to get back there, click the nav button on the top left corner, then choose Cells). 
B. Find the button with a pencil and a plus sign in the top right corner and click it.
C. In the cell editing view you can enter a name, choose a cell design (click the '+' button to register your choice), and edit the cell design parameters. There are many menus and inputs in the cell specification you can explore.
D. Changing values here only edits this single cell. "Template" cell components, constituent materials, and whole cell designs can be saved and edited (and deleted) in the library. Experiments are faster way to define many cells (that's up next).

### 3. Generate an experiment. 
A. Click on the navigation button in the top left corner and choose Experiments. 
B. You can open an existing experiment (double click) or create a new one from scratch (click the pencil/plus button in the top right corner).
C. The experiment menus let you define a set of control variables and noise variables. Then you can pick the design matrix from a range of DOEs. The experiment then will generate all the cells with the correct properties. You can build and test these cells, associate test data with the cell definitions, and analyze it as it's generated on the tester.
D. Start by choosing a "base" cell (don't forget to click the plus button to register your choice), and work your way through the experiment tabs from left to right. There are text tips on each page to help you get started.


### Bonus: Try an analysis.
The analysis produces results for each cell based on test data (if there are multiple files associated with a cell, it will concatenate the data in date order). Then it will correlate the results with the design properties defined on each cell. 

Click on the navigation button in the top-left and pick Analysis. You can select Experiment to analyze all the cells in one experiment, Pick Cells to select an arbitrary grouping of cells, or Pick Data to pick individual test data files.