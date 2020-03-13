# HOI-Learning-List
Some recent (2015-now) Human-Object Interaction Learing studies.

## Dataset
HAKE (CVPR2020) [[Website]](http://hake-mvig.cn/home/) [[Paper]](https://arxiv.org/pdf/1904.06539.pdf)

HICO-DET (WACV2018) [[Website]](http://www-personal.umich.edu/~ywchao/hico/) [[Paper]](http://www-personal.umich.edu/~ywchao/publications/chao_wacv2018.pdf)

HCVRD (AAAI2018) [[Website]](https://bitbucket.org/jingruixiaozhuang/hcvrd-a-benchmark-for-large-scale-human-centered-visual/src/master/) [[Paper]](https://pdfs.semanticscholar.org/c94f/1aaf62f87d97dd579cb6451cb9149fb4967d.pdf)

V-COCO (May 2015) [[Website]](https://github.com/s-gupta/v-coco) [[Paper]](https://arxiv.org/pdf/1505.04474.pdf)

HICO (ICCV2015) [[Website]](http://www-personal.umich.edu/~ywchao/hico/) [[Paper]](http://www-personal.umich.edu/~ywchao/publications/chao_iccv2015.pdf)

OpenImage [[Website]](https://visualgenome.org/) [[Paper]](https://arxiv.org/abs/1602.07332)

PIC [[Website]](http://picdataset.com/challenge/index/)

More...

## Method

### HOI Recognition: Image-based, to recognize all the HOIs in one image.

PaStaNet (CVPR2020) [[Code]]() [[Paper]]() 

Pairwise (ECCV2018) [[Paper]](http://openaccess.thecvf.com/content_ECCV_2018/papers/Haoshu_Fang_Pairwise_Body-Part_Attention_ECCV_2018_paper.pdf)

Learning Models for Actions and Person-Object Interactions with Transfer to Question Answering (ECCV2016) [[Code]](https://uofi.box.com/s/yflrqbser1r5m3iez1satkprawmsouag) [[Paper]](https://arxiv.org/pdf/1604.04808.pdf)

Attentional Pooling for Action Recognition (NIPS2017) [[Code]](https://github.com/rohitgirdhar/AttentionalPoolingAction) [[Paper]](https://arxiv.org/pdf/1711.01467.pdf)

Contextual Action Recognition with R\*CNN (ICCV2015) [[Code]](https://github.com/gkioxari/RstarCNN) [[Paper]](https://arxiv.org/pdf/1505.01197.pdf)

HOCNN (ICCV2015) [[Code]](https://github.com/ywchao/hico_benchmark) [[Paper]](http://www-personal.umich.edu/~ywchao/publications/chao_iccv2015.pdf)

More...

### HOI Detection: Instance-based, to detect the human-object pairs and classify the interactions.

PaStaNet (CVPR2020) [[Code]]() [[Paper]]()

DJ-RN (CVPR2020) [[Code]]() [[Paper]]()

Cascaded Human-Object Interaction Recognition (CVPR2020) [[Code]](https://github.com/tfzhou/C-HOI) [[Paper]](https://arxiv.org/pdf/2003.04262.pdf)

PPDM (CVPR2020) [[Paper]](https://arxiv.org/pdf/1912.12898.pdf)

PMFNet(ICCV2019) [[Code]](https://github.com/bobwan1995/PMFNet) [[Paper]](https://arxiv.org/abs/1909.08453)

No-Frills (ICCV2019) [[Code]](https://github.com/BigRedT/no_frills_hoi_det) [[Paper]](http://tanmaygupta.info/assets/img/no_frills/paper.pdf)

Analogy (ICCV2019) [[Code]](https://github.com/jpeyre/analogy) [[Paper]](https://www.di.ens.fr/willow/research/analogy/paper.pdf)

RPNN (ICCV2019) [[Paper]](http://openaccess.thecvf.com/content_ICCV_2019/papers/Zhou_Relation_Parsing_Neural_Network_for_Human-Object_Interaction_Detection_ICCV_2019_paper.pdf)

Deep Contextual Attention for Human-Object Interaction Detection (ICCV2019) [[Paper]](http://openaccess.thecvf.com/content_ICCV_2019/papers/Wang_Deep_Contextual_Attention_for_Human-Object_Interaction_Detection_ICCV_2019_paper.pdf)

Interactiveness (CVPR2019) [[Code]](https://github.com/DirtyHarryLYL/Transferable-Interactiveness-Network) [[Paper]](https://arxiv.org/pdf/1811.08264.pdf)

GPNN (ECCV2018) [[Code]](https://github.com/SiyuanQi/gpnn) [[Paper]](https://arxiv.org/pdf/1808.07962.pdf)

iCAN (BMVC2018) [[Code]](https://github.com/vt-vl-lab/iCAN) [[Paper]](https://arxiv.org/pdf/1808.10437.pdf)

InteractNet (CVPR2018) [[Paper]](https://arxiv.org/pdf/1704.07333.pdf)

Scaling Human-Object Interaction Recognition through Zero-Shot Learning (WACV2018) [[Paper]](http://vision.stanford.edu/pdf/shen2018wacv.pdf)

HO-RCNN (WACV2018) [[Code]](https://github.com/ywchao/ho-rcnn) [[Paper]](http://www-personal.umich.edu/~ywchao/publications/chao_wacv2018.pdf)

VSGNet (Mar 2020) [[Paper]](https://vision.ece.ucsb.edu/sites/default/files/publications/vsgnet_spatial_attention_network_for_detecting_human_object_interactions_using_graph_convolutions_0.pdf)

Visual-Semantic Graph Attention Networks for Human-Object Interaction Detection (Mar 2020) [[Paper]](https://arxiv.org/pdf/2001.02302.pdf)

Classifying All Interacting Pairs in a Single Shot (Jan 2020) [[Paper]](https://arxiv.org/pdf/2001.04360.pdf)

Deep Contextual Attention for Human-Object Interaction Detection (Oct 2019) [[Paper]](https://arxiv.org/pdf/1910.07721.pdf)

More...

## Result

HICO-DET:

|Method| Pub|Full(def) | Rare(def) | None-Rare(def)| Full(ko) | Rare(ko) | None-Rare(ko) |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|[Shen et al.](http://vision.stanford.edu/pdf/shen2018wacv.pdf)| WACV2018 |  6.46 | 4.24 | 7.12| - | - | - |
|[HO-RCNN](http://www-personal.umich.edu/~ywchao/publications/chao_wacv2018.pdf)| WACV2018 | 7.81|  5.37|  8.54|  10.41|  8.94 | 10.85 |
|[InteractNet](https://arxiv.org/pdf/1704.07333.pdf)| CVPR2018 |  9.94|  7.16 | 10.77| - | - |-|
|[GPNN](https://arxiv.org/pdf/1808.07962.pdf)| ECCV2018 |  13.11 | 9.34 | 14.23| - | - |-|
|[Xu et. al](https://www-users.cs.umn.edu/~qzhao/publications/pdf/xu2019cvpr.pdf)|ICCV2019|14.70 |13.26| 15.13|-|-|-|
|[iCAN](https://arxiv.org/pdf/1808.10437.pdf)| BMVC2018 | 14.84|  10.45 | 16.15 | 16.26  | 11.33| 17.73 |
|[Wang et. al.](http://openaccess.thecvf.com/content_ICCV_2019/papers/Wang_Deep_Contextual_Attention_for_Human-Object_Interaction_Detection_ICCV_2019_paper.pdf)|ICCV2019|16.24 |11.16| 17.75| 17.73| 12.78| 19.21|
|[Interactiveness](https://arxiv.org/pdf/1811.08264.pdf)| CVPR2019 | 17.03 | 13.42| 18.11| 19.17| 15.51|20.26|
|[No-Frills](http://tanmaygupta.info/assets/img/no_frills/paper.pdf)| ICCV2019 | 17.18 |12.17| 18.68 |-|-|-|
|[RPNN](http://openaccess.thecvf.com/content_ICCV_2019/papers/Zhou_Relation_Parsing_Neural_Network_for_Human-Object_Interaction_Detection_ICCV_2019_paper.pdf)|ICCV2019|17.35| 12.78| 18.71|-|-|-|
|[PMFNet](https://arxiv.org/pdf/1909.08453.pdf)| ICCV2019 | 17.46| 15.65| 18.00| 20.34| 17.47| 21.20|
|[Interactiveness-optimized](https://github.com/DirtyHarryLYL/Transferable-Interactiveness-Network)| CVPR2019 | 17.54	|13.80	|18.65|	19.75|	15.70|	20.96|
|[Julia et al.](https://www.di.ens.fr/willow/research/analogy/paper.pdf)| ICCV2019 | 19.40 |14.60| 20.90|-|-|-|
|[PPDM](https://arxiv.org/pdf/1912.12898.pdf)|CVPR2020|21.10 |14.46| 23.09| -|-|-|
|[DJ-RN]()| CVPR2020 | 21.06 |17.67 |22.07| 23.48| 20.00 |24.56|
|[Interactiveness+PaStaNet]()| CVPR2020 | 22.03|19.86|22.68|24.26|22.37|24.82|


V-COCO:

|Method| Pub | AP(role) |
|:---:|:---:|:---:|
|[Gupta et al.](https://arxiv.org/pdf/1505.04474.pdf)|arXiv| 31.8|
|[InteractNet](https://arxiv.org/pdf/1704.07333.pdf)|CVPR2018|40.0|
|[GPNN](https://arxiv.org/pdf/1808.07962.pdf)|ECCV2018|44.0|
|[iCAN](https://arxiv.org/pdf/1808.10437.pdf)| BMVC2018 | 45.3| 
|[Xu et. al](https://www-users.cs.umn.edu/~qzhao/publications/pdf/xu2019cvpr.pdf)| CVPR2019| 45.9|
|[Wang et. al.](http://openaccess.thecvf.com/content_ICCV_2019/papers/Wang_Deep_Contextual_Attention_for_Human-Object_Interaction_Detection_ICCV_2019_paper.pdf)| ICCV2019|47.3|
|[Interactiveness](https://arxiv.org/pdf/1811.08264.pdf)| CVPR2019 | 47.8| 
|[Zhou et. al.](https://arxiv.org/pdf/2003.04262.pdf) |CVPR2020|48.9|
|[Interactiveness-optimized](https://github.com/DirtyHarryLYL/Transferable-Interactiveness-Network)| CVPR2019 | 49.0	|
|[Interactiveness+PaStaNet]()| CVPR2020 | 51.0|
|[PMFNet](https://arxiv.org/pdf/1909.08453.pdf)|ICCV2019|52.0|
