# gtlibrary
Repository of extensive-form games

The folder includes two datasets of extensive-form games.

The files **dataset1_names.txt** and **dataset2_names** include the name of respectively the first and the second datasets.
The file **dataset1.txt** includes the first dataset.
The files **dataset2 - 1st part.txt**, **dataset2 - 2nd part.txt**, **dataset2 - 3rd part.txt** include the second dataset.

# How to read the files

Every line of the file is a game.

Every game is described by a dictionary with the following keys:
- _key_, the name of the game (_string_);
- _size_, the size of the game (_integer_);
- _actions_, a vector of vectors each of which lists the actions that lead from the vertex to a leaf (_list_);
- _players_, a vector of vectors each of which lists the players acting from the vertex to a leaf (_list_);
- _utility_, a vector of utility vectors, one for each leaf (_list_).
