# DAG-NoCurlに基づく潜在因子間の因果探索手法

## 実行時のスペック
```
Python 3.11
```

## コード説明
BPR.py: DAG-NoCurlによる推定を行うコード．Yu et al.(2021)のコードをベースに作成．

data_generate.py: シミュレーションのための人工データを生成するコード．Zeng et al.(2021)のコードをベースに作成．

lina_nocurl.py: 提案手法および既存手法による推定を行うコード．Yu et al.(2021)，Zeng et al.(2021)のコードをベースに作成．

real_world_data_analysis.ipynb: 実データ解析例を行うためのNotebook．

simulation_implementation.py: シミュレーションを行うためのコード．Yu et al.(2021)をベースに作成．

simulation_results.ipynb: シミュレーション結果を既存手法と提案手法で比較するためのコード．

utils.py: シミュレーション結果をcsvファイルに保存する関数を含むコード．Yu et al.(2021)をベースに作成．

## データ説明
elind1.txt: Byrne(2016)のサポートサイト(https://www.routledge.com/Structural-Equation-Modeling-With-AMOS-Basic-Concepts-Applications-and-Programming-Third-Edition/Byrne/p/book/9781138797031)から得られる教師の燃え尽き症候群に関するデータ．



Acknowledgments
本研究および関連するコードは，下記の研究に基づき作成されました．
DAG-NoCurl：https://github.com/fishmoon1234/DAG-NoCurl
MD-LiNA：https://github.com/cdt15/lingam

参考文献
Byrne, B. M. (2016). Structural Equation Modeling with AMOS: Basic Concepts, Applications, and Programming, 3nd ed.
Yu, Y., Gao, T., Yin, N., and Ji, Q. (2021). DAGs with No Curl: An Efficient DAG Structure Learning Approach, in Meila, M. and Zhang, T. eds. Proceedings of the 38th International Conference on Machine Learning, 139 of Proceedings of Machine Learning Research, 12156–12166, PMLR.
Zeng, Y., Shimizu, S., Cai, R., Xie, F., Yamamoto, M., and Hao, Z. (2021). Causal Discovery with Multi-Domain LiNGAM for Latent Factors, in Zhou, Z.-H. ed. Proceedings of the Thirtieth International Joint Conference on Artificial Intelligence, IJCAI-21, 2097–2103, International Joint Conferences on Artificial Intelligence Organization. Main Track.
