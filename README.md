# Structural-entropy-minimisation
The java code of algorithm of structure entroy minimisation 
example
java -jar deDoc.jar xxx/xxx/xxx/hicGraph

We treat Hic matrix as the adjacent matrix of the hicGraph which is the input of this algorithm. The format is
3
1 2 1.0
1 3 2.0
2 3 3.0
The first line is the number of bins in the graph
The second line is the edge: first_bin second_bin reads
.splitted by space. The node_id start from 1.
Resultfile (hicGraph.deDoc(E) or hicGraph.deDoc(M)) is the result of communities found by algorithm deDoc(E) or deDoc(M). Each line is a tad. And it will print the 2D-nSE of the hicGraph.

To compute 1D-nSE, use command
java -jar onednSE.jar xxx/xxx/xxx/hicGraph
The result is the 1D-nSE of this hicGraph.

To get the java source code, you just need to decompress dedoc.jar and onednSE.jar using software such as WinRAR.

P.S. The input Hi-C matrix should be symmetric matrix
