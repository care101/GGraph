# GGraph
GGraph is a structure-aware graph processing system.

* It can be seamlessly integrated with existing graph processing systems with few APIs. 

* It proposes an efficient graph processing approach with the property of graph structure into consideration. It mainly uses a novel low overhead repartition scheme to dynamically divide the hot-vertices together so as to skip the load of the inactive vertices. 

* It reduces data accessing cost and speeds up convergance rate. We integrate GGraph with Gemini. Comprehensive experimental results show that GGraph reduces the data access time by up to 77.3% and spares the number of updates by up to 53.1%. As a result, GGraph gets a performance improvement up to 3.2 times.

### Run algorithm
PageRank
``` shell
./toolkits/pagerank <data dir> <vertices num> <iteration num>
```

SSSP
``` shell
./toolkits/SSSP <data dir> <vertices num> <root vertex>
```

BFS
``` shell
./toolkits/BFS <data dir> <vertices num> <root vertex>
```

CC
``` shell
./toolkits/CC <data dir> <vertices num> 
```
