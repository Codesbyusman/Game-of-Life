# Game-of-Life

&nbsp; &nbsp; &nbsp; &nbsp; **Game of Life (or just “Life”) is not really a game. There’s no winning or losing or destroying your opponent mentally and spiritually. Life is a “cellular automaton” - a system of cells that live on a grid, where they live, die and evolve according to the rules that govern their world**.

&nbsp; &nbsp; &nbsp; &nbsp; Life’s simple, elegant rules give rise to astonishingly complex emergent behavior. It is played on a 2-D grid.Each square in the grid contains a cell, and each cell starts the game as either “alive” or “dead”. Play proceeds in rounds. During each round, each cell looks at its 8 immediate neighbors and counts up the
number of them that are currently alive. A 2D matrix of size 30x30 was used to make the grid and then rules were applied to see the fate of cells in each iteration. It runs for the infinte times with giving a pause option to user to enter the time in seconds or by default shows the changing after pause of 1 sec. The cell then updates its own liveness according to the folowing 4 rules:

- Any live cell with 0 or 1 live neighbors becomes dead, because of underpopulation
- Any live cell with 2 or 3 live neighbors stays alive, because its neighborhood is just right
- Any live cell with more than 3 live neighbors becomes dead, because of overpopulation
- Any dead cell with exactly 3 live neighbors becomes alive, by reproduction

### Note : 
&nbsp; &nbsp; &nbsp; &nbsp; * represents the alive cells and (space) ' ' represents the dead cells.

