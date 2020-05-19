# KACC
KACC: A Multi-task Benchmark for Knowledge Abstraction, Concretization and Completion


### Data 

Because of the file size limit of Github, you have to unzip the KACC-large dataset first.

```
cd data/
unzip KACC-large.zip
```
The id-name mapping files:

- entity2name.txt

- concept2name.txt

- relation2name.txt


Each of the dataset has three files:

- ent-triples.txt 

	Triples (`entity`, `relation`, `entity`) in the entity graph.

- cpt-triples.txt 

	Triples (`concept`, `meta-relation`, `concept`) in the concept graph.

- cross-triples.txt 

	Cross-view triples (`entity`, `instance_of`, `concept`).
