# nmt_instance_weighting

This is the instruction of implementation for the paper "Instance Weighting for Neural Machine Translation Domain Adaptation".

For the sentence weigting and domian weighting, you just need to add a weight to the NMT objective function.

For the batch weighting method, you can refer to the original Nematus settings: domain_interpolation_data_iterator.py

@InProceedings{wang-EtAl:2017:EMNLP20174,

author    = {Wang, Rui  and  Utiyama, Masao  and  Liu, Lemao  and  Chen, Kehai  and  Sumita, Eiichiro},

title     = {Instance Weighting for Neural Machine Translation Domain Adaptation},

booktitle = {Proceedings of the 2017 Conference on Empirical Methods in Natural Language Processing},

month     = {September},

year      = {2017},

address   = {Copenhagen, Denmark},

pages     = {1482--1488},

url       = {https://www.aclweb.org/anthology/D17-1155}
}
