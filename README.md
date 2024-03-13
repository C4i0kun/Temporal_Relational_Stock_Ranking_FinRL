# Temporal_Relational_Stock_Ranking_FinRL

This repository contains the [FinRL](https://github.com/AI4Finance-Foundation/FinRL)-compatile version of the temporal and relational data introduced in [Temporal_Relational_Stock_Ranking](https://github.com/fulifeng/Temporal_Relational_Stock_Ranking) repository. For more informations about the data, read the paper "Temporal Relational Ranking for Stock Prediction" [\[paper\]](https://arxiv.org/abs/1809.09441).

## Folders

The repository is organized as follows:

- `relational_data`: Folder containing the relational data compatible with FinRL.
    - `edge_indexes`: Folder containing `edge_index` numpy arrays in COO format (compatible with [PyG](https://pyg.org/)).
    - `gephi_visualizations`: Folder containing `.gexf` files to visualize the graphs in [Gephi](https://gephi.org/).
- `scripts`: Folder containing python notebooks with scripts to generate FinRL-compatible data.

## Running scripts

Before running the scripts in the `scripts` folder, you need to install some python libraries using the following command:

```bash
pip install -r requirements.txt
```

Then, you need to clone [Temporal_Relational_Stock_Ranking](https://github.com/fulifeng/Temporal_Relational_Stock_Ranking) repository:

```bash
git clone https://github.com/fulifeng/Temporal_Relational_Stock_Ranking.git
```

## Visualizing graphs

To be able to visualize the graph structures, you need to install Gephi. Check their [official website](https://gephi.org/) for more information.

## Citations in research

If you're using this data in your research, consider citing this repository and the original paper.

```
@article{feng2019temporal,
  title={Temporal relational ranking for stock prediction},
  author={Feng, Fuli and He, Xiangnan and Wang, Xiang and Luo, Cheng and Liu, Yiqun and Chua, Tat-Seng},
  journal={ACM Transactions on Information Systems (TOIS)},
  volume={37},
  number={2},
  pages={27},
  year={2019},
  publisher={ACM}
}
```