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
abstract  = {Instance weighting has been widely applied to phrase-based machine translation
	domain adaptation. However, it is challenging to be applied to Neural Machine
	Translation (NMT) directly, because NMT is not a linear model. In this paper,
	two instance weighting technologies, i.e., sentence weighting and domain
	weighting with a dynamic weight learning strategy, are proposed for NMT domain
	adaptation. Empirical results on the IWSLT English-German/French tasks show
	that the proposed methods can substantially improve NMT performance by up to
	2.7-6.7 BLEU points, outperforming the existing baselines by up to 1.6-3.6 BLEU
	points.},
url       = {https://www.aclweb.org/anthology/D17-1155}
}
