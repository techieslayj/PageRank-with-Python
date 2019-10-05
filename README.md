# PageRank-with-Python
General PageRank algorithm with Python

# Goals
Here I create a simple form the PageRank model which seeks to rank webpages based on in-links and out-links using two methods, direct and power methods. Essentially I create an adjacency matrix in which describes the structure of links, where a '1' in the (i,j) position of the matrix indicates a link from site j to site i. Diagonals are zero because we do not consider self-links. In the end I demonstrate how we can make the PageRank algorithm into an eigenvalue problem and therefore find R (a column vector of PageRanks).

The code is commented rather often and the detailed report is added to the repository, if you have any other questions or critiques please feel free to ask. Thanks
