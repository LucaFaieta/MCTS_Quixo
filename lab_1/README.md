# Lab1 - Set Covering
This repo contains the solution to the first laboratory of the 2023/2024 Computational Intelligence course called **Set Covering**. 

## Authors
The contributors of this repo are:
* Luca Faieta s323770 
* Stefano Barcio s320174

## Sources 
Most of the code was reproduced from what seen in class, especially from the solution to the [Set Covering Path Search](https://github.com/squillero/computational-intelligence/blob/master/2023-24/set-covering_path-search.ipynb).

## Methodology
To solve this problem, we adapted the code above mentioned. In particular, we replaced the simple queue with a priority queue and we added a parameter to the euristic to take into account the cost of the previous steps of the solution. These two changes make the algorithm a proper A*, as requested in the specifications. We decided to use the third euristic proposed in class. 

## Testing results
The following table shows the results of some simple tests. We decided to keep the probability of having a "true" tile constant to ensure consistency in the tests.

| **problem size** | **number of sets** | **number of steps** | **number of tiles** |
|:---:|:---:|:---:|:---:|
| **20** | **50** | 39 | 3 |
| **20** | **30** | 14 | 3 |
| **40** | **70** | 946 | 4 |
| **50** | **70** | 1410 | 4 |
