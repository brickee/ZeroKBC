# ZeroKBC

A comprehensive benchmark that covers all scenarios of zero-shot Knowledge Base Completion (KBC) task.

## Description

We systematically examine different possible scenarios of zero-shot KBC and categorize 3 zero-shot scenarios with 8 fine-grained settings. 

* Zero-Shot Entity KBC (ZeroE)
When we see a new entity, we need to predict all the possible links between this new entity and existing entities. We may  know some context for it (some connections between this new entity and the existing KG) or we need the textual descriptions of it in the absence of connections.

* Zero-Shot Relation KBC (ZeroR):
When we see a new relation, predict if this relation exists in any pair of the entities. We will always have the textual descriptions of new relations to distinguish them.

* Zero-Shot Both KBC (ZeroB):
Predict the link for both a newly added relation and a newly added entity. Textual description is necessary for the relations as in ZeroR and entity descriptions are also required in the absence of context.

![alt](example.jpg)

## Dataset
Please find the dataset [here](https://github.com/brickee/ZeroKBC/blob/main/ZeroKBC.zip).

## Citation

If you extend or use this dataset, please cite the paper (to appear).


<!-- ```text
@inproceedings{chen-etal-2021-probing,
 author = {Chen, Pei  and Liu, Kang  and Chen, Yubo  and Wang, Taifeng  and Zhao, Jun},
 booktitle = {Proceedings of the 16th Conference of the European Chapter of the Association for Computational Linguistics: Main Volume},
 month = {April},
 pages = {2042--2048},
 publisher = {Association for Computational Linguistics},
 title = {Probing into the Root: A Dataset for Reason Extraction of Structural Events from Financial Documents},
 year = {2021}
}
``` -->