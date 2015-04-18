# pushmo-solver

Solves simple Pushmo levels using a depth-first search with depth cap and heuristic sorting. Should probably use iterative deepening or something else, a better heuristic, and a hash set for keeping track of already-expanded moves (but I can't get it to work under Rust 1.0 Beta). Currently only checks very basic jumping rules. It should be easy to add new mechanics by editing PuzzleSolver's get_reachable_at() and get_potential_moves_at(). Inspired by https://github.com/euske/pushmo-solver
