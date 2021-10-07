# calculator-744
Calculator at replit.com/@mkcodes/calculator

### GRAPHING HELP
___
plotAtXy(graph, x, y, appendLetter)             Plot a function. A prebuilt graph is in variable `graph.
                                                The point at X, Y on graph `graph` (a text graph) is changed
                                                to the letter appendLetter.
actualPlotAtXy(graph, x, y, appendLetter)       This is the one you should use, since it has bug fixes.
                                                Basically plotAtXy but better.
allPointsBetween(x1, y1, x2, y2)                This will get all points in between the coordinates x1, y1 and x2, y2.
allPointsBetween_float(x1, y1, x2, y2, accuracy)Difference: It gets all the points in between x1, y1, x2, y2 but it allows decimals.
                                                So you can specify an accuracy.
allPointsBetween_int(x1, y1, x2, y2, accuracy)  Think about it this way; It gets everything from allPointsBetween_float
                                                but rounds the decimals to the nearest- i mean lower- number.
Do help('testgraph-2') for page 2.

### SET THEORY HELP
___
Here are the set theory symbols and the corresponding function names.
intersection(a,b)                                      a⋂b       
union(a,b)                                             a⋃b       
subset(a,b)                                            a⊆b      
strictSubset(a,b)                                      a⊂b     
notSubset(a,b)                                         a⊄b       
superset(a,b)                                          a⊇b      
strictSuperset(a,b)                                    a⊃b      
allSubsets(a)                                          P(a)
                                                       WARNING Does not include empty set {} and includes sets twice sometimes (e.g. {1,2}, {2,1})
(already in python) a == b                             a=b       
DNE (you can use complement(a,b) considering b is all the numbers in the world) A', Ac
complement(a,b), (RECCOMMENDED)difference(a,b)         A-B, A\B
symmetricDifference(a,b)                               A⊖B, A∆B
(already in python) a in A                             a∈A      
(already in python) x not in A                         x∉A       
cartesianProduct(a,b) (might not be correct)           A×B
cardinality(a) (also exists in python: len(a))         |A|, #A   

### MATRIX HELP
___
Lists are written in this way:
 [ [1,2,3],
   [4,5,6],
   [7,8,9] ]
operationTwoLists(list1, list2, operation)        Preform a operation on two matrices.
operationMatrices(matrice1, matrice2, operation)  I forgor what this does if you really need it then ask me in a comment
negativeMatrice(matrice1)                         Makes all values in a matrice negative.
determinant2x2Matrix(matrice1)                    Get a determinant of a 2x2 matrix.

### PLOTS HELP
___
sidewaysDotPlot(graph_array, appendLetter="*", xval="", yval="")
      graph_array: The list you want to plot
      appendLetter: If it's *, the graph will look something like
      xval | *********
      [2]  | ******* etc..
      xval, yval: X and Y axis labels.
sidewaysBarGraph(graph_array, appendLetter="|", xval="", yval=""):
      Like sidewaysDotPlot but its a bar graph.
mean(x), median(x)
      Get mean and median of list.
beforeAfterLst(lst, one)
      I forgor what this does, but if you really need it ask me in a comment.
boxPlot(graph_array, outputType='array')
      graph_array: List of values
      outputType: the type of output you want (JSON for JSON or 'array' for list).
      
### DESMOS CLONE HELP
___
total(list): Return sum of all values in a list.
length(list): Length of a list.
mean(list): Mean of a list.
median(list): Median of a list. Also in graph_plots.
min(list): Minimum value of a list.
max(list): Maximum value of a list.
quartile(list, quartileNumber): Get quartile quartileNumber of a list.
quantile(lst, num): Get quantile number # num of a list lst.
stdevp(lst): Standard deviation of a popluation.
stdev(lst): Get standard deviation of a list.
mad(lst): Get mean absolute deviation of a list.

### LIST CALCULATOR
___
filterout(1,2,3,4)      Remove strings and negative numbers from list.
transform(1,2,3,4)      Remove duplicates from list.
reverselt(1,2,3,4)      Reverse a list.
mean_calc(1,2,3,4)      Calculate the mean of a list.
subt_null(1,2,3,4)      Remove None (null) values from a list.
tcsv_conv((1,2),(3,4))  Convert a list to CSV. Raises TypeError if only one row is given.
                        Example: tcsv_conv 1,2,3|4,5,6
add__list(1,2,3,4)      Add all the numbers on a list.
