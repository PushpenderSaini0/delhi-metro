# Delhi Metro Network Git Map

Welcome to the Delhi Metro Network Git Map project! 🚇

This unique and fun project represents the Delhi Metro network as a Git repository. 

- `Metro Station` -> `Commit`
- `Metro Line` -> `Branch`
- `Merging of Lines` -> `Merge Commit`
- `Splitting of Lines` -> `Branching`


## Special Considerations
- To maintain a valid and acyclic Git history, we had to skip mapping connections for four stations:
  1. SEELAMPUR to WELCOME
  2. MAYAPURI to RAJOURI GARDEN
  3. SATGURU RAM SINGH MARG to KIRTI NAGAR
  4. ANAND VIHAR ISBT to KARKARDUMA

## Getting Started

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/PushpenderSaini0/delhi-metro.git
   ```

2. Explore the commit history, branches, and visualize the Delhi Metro network in a Git-centric way.

3. Have fun exploring the branches and commits to understand the structure and connections of the Delhi Metro stations.

## Creation Process

1. **Data Gathering:**
   - Station and line data were collected from a web API to kickstart the project.

2. **Graph Mapping in Python:**
   - Python scripts is used to transformed the data into a graph, where stations were nodes and connections were edges.

3. **Graph Traversal:**
   - Simple graph traversal algorithms is used to structure Git commits, branches, and merges mirroring the Delhi Metro network.

4. **GitPython Integration:**
   - `GitPython` is used as git interface for python.

> GitPython did not work when doing `--allow-unrelated-histories` and `--no-ff` merges so i had to use the os module for that.
   

## Contributing

You can raise a pull request to add new features or enhance the visualization. If you have a knack for algorithms and think there's a better way to map the metro, don't hesitate to start a discussion.