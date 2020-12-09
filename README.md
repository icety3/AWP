# Multiview Clustering via Adaptively Weighted Procrustes (AWP)

In this paper, we make a multiview extension of the spectral rotation technique raised in single view spectral clustering research. Since spectral rotation is closely related to the Procrustes Analysis for points matching, we point out that classical Procrustes Average approach can be used for multiview clustering. Besides, we show that direct applying Procrustes Average (PA) in multiview tasks may not be optimal theoretically and empirically, since it does not take the clustering capacity differences of different views into consideration. Other than that, we propose an Adaptively Weighted Procrustes (AWP) approach to overcome the aforementioned deficiency. Our new AWP weights views with their clustering capacities and forms a weighted Procrustes Average problem accordingly. The optimization algorithm to solve the new model is computational complexity analyzed and convergence guaranteed. Experiments on five real-world datasets demonstrate the effectiveness and efficiency of the new models.

# Citation

If you find our paper or this project helps your research, please kindly consider citing our paper in your publications.
```bash
@inproceedings{nie2018multiview,
  title={Multiview clustering via adaptively weighted procrustes},
  author={Nie, Feiping and Tian, Lai and Li, Xuelong},
  booktitle={Proceedings of the 24th ACM SIGKDD international conference on knowledge discovery \& data mining},
  pages={2022--2030},
  year={2018}
}
```



