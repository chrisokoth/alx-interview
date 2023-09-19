The island_perimeter function calculates and returns the perimeter of a single island represented within a rectangular grid. The grid consists of cells that can be either land (denoted by '1') or water (denoted by '0'). The key characteristics of this function are as follows:

The grid is a 2D list of integers.
Land cells have a value of '1,' while water cells have a value of '0.'
Each cell within the grid represents a square with a side length of 1 unit.
Cells are connected only horizontally and vertically, not diagonally.
The grid is completely enclosed by water, with no landmass extending beyond the grid boundaries.
There is exactly one island on the grid, and no disconnected landmasses or "lakes" are present.
The function efficiently computes and returns the perimeter of the island by considering the adjacency of land cells and accounting for the perimeter of the island's boundaries.
