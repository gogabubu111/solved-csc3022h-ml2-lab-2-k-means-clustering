Download Link: https://assignmentchef.com/product/solved-csc3022h-ml2-lab-2-k-means-clustering
<br>
Implement (in C++) the <em>K-means</em> clustering algorithm [MacQueen, 1967] with a Euclidean distance metric. See online tutorials at:

<ul>

 <li>http://www.saedsayad.com/clustering kmeans.htm</li>

</ul>

Use the implemented K-means algorithm to cluster the following 8 examples (table 1) into 3 clusters.

When running K-means, set the initial seeds (initial centroid of each cluster) as examples 1, 4 and 7.

Table 1: Data (examples have two attributes: <em>X</em>, <em>Y </em>, both in range: [1, 10]).

<table width="173">

 <tbody>

  <tr>

   <td width="118">Example Number</td>

   <td width="26">X</td>

   <td width="29">Y</td>

  </tr>

  <tr>

   <td width="118">1</td>

   <td width="26">2</td>

   <td width="29">10</td>

  </tr>

  <tr>

   <td width="118">2</td>

   <td width="26">2</td>

   <td width="29">5</td>

  </tr>

  <tr>

   <td width="118">3</td>

   <td width="26">8</td>

   <td width="29">4</td>

  </tr>

  <tr>

   <td width="118">4</td>

   <td width="26">5</td>

   <td width="29">8</td>

  </tr>

  <tr>

   <td width="118">5</td>

   <td width="26">7</td>

   <td width="29">5</td>

  </tr>

  <tr>

   <td width="118">6</td>

   <td width="26">6</td>

   <td width="29">4</td>

  </tr>

  <tr>

   <td width="118">7</td>

   <td width="26">1</td>

   <td width="29">2</td>

  </tr>

  <tr>

   <td width="118">8</td>

   <td width="26">4</td>

   <td width="29">9</td>

  </tr>

 </tbody>

</table>

<strong>Question 1: </strong>How many iterations are needed for k-means to converge?

In a text file output the results of each iteration (for each cluster, list the examples that fall into each cluster), and the centroids of each cluster, <strong>e.g.:</strong>

Iteration 1

Cluster 1: 1, 2, 3

Centroid: (3.0, 9.5)

Cluster 2: 4, 5, 6

Centroid: (6.5, 5.25)

Cluster 3: 7, 8

Centroid: (1.5, 3.5)

<ul>

 <li>··</li>

</ul>

Iteration N

Cluster 1: 8, 7, 6

Centroid: (1.5, 3.5)

Cluster 2: 5, 4, 3

Centroid: (6.5, 5.25)

Cluster 3: 2, 1

Centroid: (3.0, 9.5)

In a ZIP file, place the source code, makefile, and the output text file (answer to question 1). Upload the ZIP file to <em>Vula </em>before 10.00 AM, Monday, 12th of August, 2019.

<h1>References</h1>

[MacQueen, 1967] MacQueen, J. (1967). Some methods for classification and analysis of multivariate observations. In <em>Proceedings of the Berkeley Symposium on Mathematics, Statistics and Probability</em>, pages 281–297, Berkeley, USA. University of California Press.