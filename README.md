# Deep Face Recognition

### Requirements

### Dataset Preparation
* Training dataset
```shell
# Download training datasets (where the faces are aligned) and organize it into the following form:
└── Deep-Face-Recognition
    ├── datasets
    │   ├── glint360k
    │   │   ├── id_1
    │   │   │   ├── 1.jpg
    │   │   │   ├── 2.jpg
    │   │   │   ├── ...
    │   │   ├── id_2
    │   │   │   ├── 1.jpg
    │   │   │   ├── 2.jpg
    │   │   │   ├── ...
    │   │   ├── ...
    │   ├── ms1mv3
    │   │   ├── id_1
    │   │   │   ├── 1.jpg
    │   │   │   ├── 2.jpg
    │   │   │   ├── ...
    │   │   ├── id_2
    │   │   │   ├── 1.jpg
    │   │   │   ├── 2.jpg
    │   │   │   ├── ...
    │   │   ├── ...
    │   ├── ...
    ├── src
    │   ├── ...
    ├── ...
```
where `id_x` and `x`.jpg can be arbitrary string.

### Model Zoo
* Performance

    |Model|[LFW](https://hal.inria.fr/file/index/docid/321923/filename/Huang_long_eccv2008-lfw.pdf)|[CFP_FF](http://www.cfpw.io/paper.pdf)|[CFP_FP](http://www.cfpw.io/paper.pdf)|[AgeDB](http://openaccess.thecvf.com/content_cvpr_2017_workshops/w33/papers/Moschoglou_AgeDB_The_First_CVPR_2017_paper.pdf)|[CALFW](https://arxiv.org/pdf/1708.08197.pdf)|[CPLFW](http://www.whdeng.cn/CPLFW/Cross-Pose-LFW.pdf)|Link|
    |:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
    ||||||||
