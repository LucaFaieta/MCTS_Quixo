# Lab9 - Black Box problem
This repo contains the solution to the ninth? laboratory of the 2023/2024 Computational Intelligence course. 

## Authors
The contributors of this repo are:
* Luca Faieta s323770 
* Stefano Barcio s320174

## Sources 
Most of the code was reproduced from what seen in class with a little help from **Essentials of Metaheuristics** by Sean Luke.

## Explaination
To solve this problem, we decided to try to use the islands method presented in class and in the book, trying to make it fit such problem. We decided this type of approach after a more classical ES didn't work(too much exploitation), but sadly neither the island one that we implemented really helped us(in this case too much exploration).However the idea was to use three islands (SerieA,SerieB and LegaPro) with fixed threshold for migration.We also used tournament selection for choosing the parents, a very strong bit wise mutation and a completly random one cut crossover.In conclusion our method was too rough and didn't turn out too well, i hope that you visitor may help us clarify and improve our code.

