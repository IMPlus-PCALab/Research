# Research
This repo holds the research projects of our lab.
(* indicates equal contribution, # corresponding author)


<div>
  <h2>2022</h2>
	<div><img src="./resources/paper_icon/NeurIPS_2022_RM.png" width=500 height=300 />
            <div><strong>RecursiveMix: Mixed Learning with History</strong><br>
		Lingfeng Yang*, Xiang Li*, Borui Zhao, Renjie Song, Jian Yang#<br>
                in NeurIPS (<strong>Spotlight</strong>), 2022<br>
                <a href="https://arxiv.org/pdf/2203.06844.pdf">[Paper]</a>
                <a href="https://github.com/implus/implus.github.io/tree/master/resources/bibtex/NeurIPS_2022_RM.txt">[BibTex]</a>
                <a href="https://github.com/implus/RecursiveMix-pytorch">[Code]</a><img
                        src="https://img.shields.io/github/stars/implus/RecursiveMix-pytorch?style=social"/>
                <br>
                <alert>
        RecursiveMix is a simple but effective data augmentation technique that first leverages the historical input-prediction-label triplets.
		</alert>
            </div>
            <div class="spanner"></div>
        </div>        
	
  <h2></h2>
  	<div><img src="./resources/paper_icon/NeurIPS_2022_DTG.png" width=500 height=300 />
            <div><strong>DTG-SSOD: Dense Teacher Guidance for Semi-Supervised Object Detection</strong><br>
		Gang Li, Xiang Li#, Yujie Wang, Yichao Wu, Ding Liang, Shanshan Zhang#<br>
                in NeurIPS, 2022<br>
                <a href="https://openreview.net/pdf?id=0-uBrFiOVf">[Paper]</a>
                <a href="./resources/bibtex/NeurIPS_2022_DTG.txt">[BibTex]</a>
                <a href="https://github.com/ligang-cs/DTG-SSOD">[Code(to be released)]</a><img
                        src="https://img.shields.io/github/stars/ligang-cs/DTG-SSOD?style=social"/>
                <br>
                <alert>
        DTG-SSOD explores a novel “dense-to-dense” paradigm, instead of the traditional  “sparse-to-dense” paradigm, for effective semi-supervised object detection.
		</alert>
            </div>
            <div class="spanner"></div>
        </div>
	
  <h2></h2>	
	<div><img src="./resources/paper_icon/ECCV_2022_PseCo.png" width=500 height=300 />
            <div><strong>PseCo: Pseudo Labeling and Consistency Training for Semi-Supervised Object Detection</strong><br>
		Gang Li, Xiang Li#, Yujie Wang, Yichao Wu, Ding Liang, Shanshan Zhang#<br>
                in ECCV, 2022<br>
                <a href="https://arxiv.org/pdf/2203.16317.pdf">[Paper]</a>
                <a href="./resources/bibtex/ECCV_2022_PseCo.txt">[BibTex]</a>
                <a href="https://github.com/ligang-cs/PseCo">[Code]</a><img
                        src="https://img.shields.io/github/stars/ligang-cs/PseCo?style=social"/>
                <a href="https://zhuanlan.zhihu.com/p/544346080">[Blog(Chinese)]</a>
		<a href="https://www.bilibili.com/video/BV1DP411j7kg/">[Video(Chinese)]</a>
                <br>
                <alert>
        PseCo delves into two key techniques of semi-supervised learning (e.g., pseudo labeling and consistency training) for SSOD, and integrate object detection properties into them. 
		</alert>
            </div>
            <div class="spanner"></div>
        </div>

  <h2></h2>
  	<div><img src="./resources/paper_icon/arXiv_2022_UMMAE.png" width=500 height=300 />
            <div><strong>Uniform Masking: Enabling MAE Pre-training for Pyramid-based Vision Transformers with Locality</strong><br>
		Xiang Li, Wenhai Wang, Lingfeng Yang, Jian Yang#<br>
                in arXiv, 2022<br>
                <a href="https://arxiv.org/pdf/2205.10063.pdf">[Paper]</a>
                <a href="./resources/bibtex/arXiv_2022_UMMAE.txt">[BibTex]</a>
                <a href="https://github.com/implus/UM-MAE">[Code]</a><img
                        src="https://img.shields.io/github/stars/implus/UM-MAE?style=social"/>
                <a href="https://zhuanlan.zhihu.com/p/520228061">[Blog(Chinese)]</a>
                <br>
                <alert>
        UM-MAE is an efficient and general technique that supports MAE-style MIM Pre-training for popular Pyramid-based Vision Transformers (e.g., PVT, Swin).
		</alert>
            </div>
            <div class="spanner"></div>
        </div>
	
  <h2></h2>
  	<div><img src="./resources/paper_icon/CVPR_2022_DynamicMLP.png" width=500 height=300 />
            <div><strong>Dynamic MLP for Fine-Grained Image Classification by Leveraging Geographical and Temporal Information</strong><br>
		Lingfeng Yang, Xiang Li#, Renjie Song, Borui Zhao, Juntian Tao, Shihao Zhou, Jiajun Liang, Jian Yang#<br>
                in CVPR (<strong>Oral</strong>), 2022<br>
                <!-- <a href="https://arxiv.org/pdf/2106.13797.pdf">[Paper]</a> -->
                <a href="https://arxiv.org/pdf/2203.03253.pdf">[Paper]</a>
                <a href="./resources/bibtex/dynamicMLP.txt">[BibTex]</a>
                <a href="https://github.com/ylingfeng/DynamicMLP">[Code]</a><img
                        src="https://img.shields.io/github/stars/ylingfeng/DynamicMLP?style=social"/>
                <br>
                <alert>
		A very simple and effective approach for fine-grained recognition tasks using auxiliary knowledge like geographical/temporal information. We achieve SOTA results and take third place in the iNaturalist challenge at FGVC8 (CVPR21 workshop)
		</alert>
            </div>
            <div class="spanner"></div>
        </div>
	
  <h2></h2>	
	<div><img class="paper" src="./resources/paper_icon/AAAI_2022_KD.png"  width=500 height=300 />
            <div><strong>Knowledge Distillation for Object Detection via Rank Mimicking and Prediction-guided Feature Imitation</strong><br>
		Gang Li*, Xiang Li*, Yujie Wang, Shanshan Zhang#, Yichao Wu, Ding Liang
                in AAAI, 2022<br>
                <!-- <a href="https://arxiv.org/pdf/2106.13797.pdf">[Paper]</a> -->
                <a href="https://arxiv.org/pdf/2112.04840.pdf">[Paper]</a>
                <a href="./resources/bibtex/kd_rm_pfi.txt">[BibTex]</a>
                <br>
                <alert>Rank Mimicking and Prediction-guided Feature Imitation for knowledge Distillation of Dense Object Detection, A Simple and Effective Approach!</alert>
            </div>
            <div class="spanner"></div>
        </div>
</div>
