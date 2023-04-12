# A Network Analysis of Game of Thrones
## Description
Jon Snow, Daenerys Targaryen, or Tyrion Lannister? Who is the most important character in Game of Thrones? Let's see what mathematics can tell us about this!

In this project, we will look at the character co-occurrence network and its evolution over the five books in R.R. Martin's hugely popular book series A Song of Ice and Fire (perhaps better known as the TV show Game of Thrones). We will look at how the importance of the characters changes over the books using different centrality measures.

This project uses a dataset parsed by Andrew J. Beveridge and Jie Shan which is available [here](https://github.com/mathbeveridge/asoiaf). For more information on this dataset have a look at [the Network of Thrones blog](https://networkofthrones.wordpress.com/).
## Usage
Clone this repository and open the Jupyter notebook file (`*.ipynb`) in a Jupyter environment with Python kernel support. Make sure to install the required packages such as `pandas`, `numpy`, and `matplotlib`. You can do this by running the following commands in a code cell within the notebook:
```python
!pip install pandas numpy matplotlib
```
Once the packages are installed, run the code cells in the notebook to generate the plots and analyses.

If you don't have a Jupyter environment set up, you can install Jupyter Notebook and the Python kernel using the following steps:

1. Install Jupyter Notebook by following the instructions on the [official Jupyter website](https://jupyter.org/install).

2. Ensure you have Python installed. If not, you can download and install Python from the [official Python website](https://www.python.org/downloads/).
## Contents
1. **Winter is Coming. Let's load the dataset ASAP!:** Load in and inspect the edge list of the first book.
2. **Time for some Network of Thrones:** Create a graph object for the first book.
3. **Populate the network with the DataFrame:** Add nodes and edges information to the network for book 1.
4. **The most important character in Game of Thrones:** Find the most important characters according to degree centrality.
5. **The evolution of character importance:** Plot the evolution of degree centrality over the books for some of the characters.
6. **What's up with Stannis Baratheon?:** Find the importance and evolution of characters according to betweenness centrality.
7. **What does Google PageRank tell us about GoT?:** Find the importance and evolution of characters according to PageRank.
8. **Correlation between different measures:** Find the correlation between the three methods of measuring importance.
9. **Conclusion:** Find the most important character in the fifth book according to degree centrality, betweenness centrality, and PageRank.