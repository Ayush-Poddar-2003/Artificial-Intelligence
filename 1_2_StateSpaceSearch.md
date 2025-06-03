![alt text](Images/SSS.png)

# State Space Search?
Process in which successive states of an instance are considered  
with the intention to find goal state.  

Problems are modelled as **State Space**  
Set of states and connection between them to represent a problem.  
Graph is used for representation.  

    S : { S, A, Action(s), Result(s,a), Cost(s,a) }
    
    A => Set of all actions
    S => Set of all states
    s => Single state from S

For eg : 8 Puzzle  
Objective is to search the goal state

---

## Searching Types


| Feature             | **Uninformed Search** (Blind)                                  | **Informed Search** (Heuristic)                                      |
| ------------------- | -------------------------------------------------------------- | -------------------------------------------------------------------- |
| **Knowledge Used**  | Search without information | Search with infromation |
| **Knowledge Used**  | No knowledge used | Uses Knowledge |
| **Time/Space Complexity** | Usually higher                                                 | Usually lower with good heuristics                                   |
| **Efficiency**      | Generally less efficient                                       | More efficient due to guided search                                  |
| **Memory Usage**    | Often high in BFS, low in DFS                                  | Depends on the heuristic used                                        |
| **Goal Direction**  | Explores blindly, not goal-directed                            | Moves towards goal using heuristic                                   |
| **Examples**        | BFS, DFS, Uniform Cost Search, DLS, IDS                        | Best-First Search, A\*, Greedy Search, Hill Climbing                 |
