# openmmlab-camp # balloon检测任务
# 配环境杀我

# 环境信息
torch              1.9.0+cu111  
mmcv               1.7.1  
mmcv-full          1.7.1  
mmdet              2.28.1  
mmengine           0.5.0. 
安装环境最佳顺序，在安装好pytorch+cuda基础上，先安装mim，之后用mim统一安装mmcv mmdet和mmengine

模型效果
<img width="904" alt="image" src="https://user-images.githubusercontent.com/47024870/218030426-abc72fd8-e918-418f-a846-00f8e98fbf60.png">
2023-02-09 20:06:34,582 - mmdet - INFO - Exp name: mask-rcnn_r50_fpn_1x_ballon_decent.py
2023-02-09 20:06:34,582 - mmdet - INFO - Epoch(val) [20][13]	
bbox_mAP: 0.7479, bbox_mAP_50: 0.8858, bbox_mAP_75: 0.8697, bbox_mAP_s: 0.4545, bbox_mAP_m: 0.6645, bbox_mAP_l: 0.7892, bbox_mAP_copypaste: 0.7479 0.8858 0.8697 0.4545 0.6645 0.7892, segm_mAP: 0.7822, 
segm_mAP_50: 0.8697, segm_mAP_75: 0.8697, segm_mAP_s: 0.0673, segm_mAP_m: 0.6249, segm_mAP_l: 0.8376, segm_mAP_copypaste: 0.7822 0.8697 0.8697 0.0673 0.6249 0.8376

测试结果







