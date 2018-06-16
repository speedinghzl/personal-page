+++
title = "Weakly-supervised semantic segmentation network with deep seeded region growing"
date = "2018-02-28"
authors = ["Zilong Huang", "Xinggang Wang", "Jiasi Wang", "Wenyu Liu", "Jingdong Wang"]
math = true
highlight = false

publication_types = ["1"]

publication = "IEEE Conference on Computer Vision and Pattern Recognition"
publication_short = "CVPR"

abstract = "This paper studies the problem of learning image semantic segmentation networks only using image-level labels as supervision, which is an important problem since it can significantly reduce human annotation efforts. Recent state-ofthe-art methods on this problem first infer the sparse and discriminative regions using deep classification networks for each object class, then train semantic segmentation networks using the discriminative regions as supervision. Inspired by the traditional image segmentation methods of seeded region growing, we propose to train semantic segmentation networks starting from the discriminative regions and progressively increase the pixel-level supervision using the idea of seeded region growing. The seeded region growing module is integrated in a deep segmentation network and can benefit from deep features. Different from conventional deep networks which has fixed/static supervision, the proposed weakly-supervised network produce some labels for its input data using the contextual information within an image. The proposed method significantly outperforms the weakly-supervised semantic segmentation methods using static supervision, and obtains the state-of-the-art performance on both PASCAL VOC 2012 and COCO, which are 63.2% mIoU score on the PASCAL VOC 2012 test set and 26.0% mIoU score on the COCO dataset."

url_pdf = "http://openaccess.thecvf.com/content_cvpr_2018/papers/Huang_Weakly-Supervised_Semantic_Segmentation_CVPR_2018_paper.pdf"
url_code = "https://github.com/speedinghzl/DSRG"

list_format = 3

+++
