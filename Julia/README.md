## Instructions to compile

To install Julia locally:
1. [Installation for Windows](https://www.geeksforgeeks.org/how-to-install-julia-on-windows/).
2. [Installation for Mac OS](https://www.aere.iastate.edu/~pwei/aere504x/julia-mac.html).
3. [Installation for Ubuntu](https://ferrolho.github.io/blog/2019-01-26/how-to-install-julia-on-ubuntu).

To run the code on an online compiler:
1. Go to [Tio](https://tio.run/#).
2. Select language 'Julia 1.0'
3. Copy and paste the code.
4. Add 3 arguments: 
  * Grid size
  * Number of alive cells
  * Generation
5. Click "Run".

## Debugging Information

1. Print any debugging statement using:
```julia
println("What are you printing", variable_name)
```
2. To access single element of the grid:
```julia
grid[row, col]
```
3. To write comments:
```julia
"This is a comment"
```
