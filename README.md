# KACC
Datasets for the ACL 2021 Findings Paper "[KACC: A Multi-task Benchmark for Knowledge Abstraction, Concretization and Completion](https://arxiv.org/pdf/2004.13631.pdf)".


## Datasets

Because of the file size limit of Github, you have to unzip the KACC-L dataset first.

```
cd Datasets/
unzip KACC-L.zip
```

### Mapping Files

The id-name mapping files:

- ent2name.txt

	Mappings between all instances (include entities and concepts) and their names.

- rel2name.txt

	Mappings between all relations and their names.


### Raw Data
For KACC-S/M/L, each of them has a ``Raw`` folder, which contains these files:

- ent-triples.txt 

	Triples (`entity`, `relation`, `entity`) in the entity graph.

- cpt-triples.txt 

	Triples (`concept`, `conceptual-relation`, `concept`) in the concept graph.

- cross-triples.txt 

	Cross-view triples (`entity`, `instanceOf`, `concept`).

- 2(3)-hop-ins(sub)-triples.txt

	2-hop or 3-hop instanceOf (ins) and subclassOf (sub) triples in each dataset.

### Split Data
As our experiments are conducted on KACC-M, we provide a ``Split`` folder for KACC-M. In this folder, we provide the train/valid/test sets under the folder name of each task.

## Citation

If you use our data, please cite the paper:

```
@inproceedings{zhou2021kacc,
  title={KACC: A Multi-task Benchmark for Knowledge Abstraction, Concretization and Completion},
  author={Zhou, Jie and Hu, Shengding and Lv, Xin and Yang, Cheng and Liu, Zhiyuan and Xu, Wei and Jiang, Jie and Li, Juanzi and Sun, Maosong},
  booktitle={Proceedings of ACL 2021: Findings},
  year={2021}
}
```