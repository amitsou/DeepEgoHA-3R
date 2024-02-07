# DeepEgoHA-3R

## **Deep Egocentric Human Action Anticipation & Activity Recognition Research Publications**

> Welcome to the DeepEgoHA^3R repository! Explore the forefront of Egocentric Human Activity Recognition (HAR) and Action Anticipation through Deep Learning. This collection features cutting-edge publications in multimodal computer vision, a focus of ongoing Ph.D. research at "the Vision Lab" at the University of Thessaly, Lamia. Dive into advancements in egocentric vision, particularly HAR and action anticipation. Contribute to our ongoing research by adding publications or insights. Let's collaborate at the intersection of deep learning and egocentric vision. Stay tuned for updates as we collectively navigate this captivating exploration!

## Inspiration and Credits

> This repository drew inspiration from [Egocentric Vision](https://github.com/EgocentricVision/EgocentricVision) repository, which provided valuable insights and ideas for exploring Egocentric Human Action Anticipation & Activity Recognition. We extend our gratitude to the contributors and researchers behind that repository for their work in advancing the field.

## **Sections**

* [Surveys](#surveys)
* [Egocentric Vision](#egocentric-vision)
* [Action Anticipation](#action-anticipation)
* [Deep Learning Methodologies and Architectures](#deep-learning-methodologies-and-architectures)
  * [General and Basic Methodologies](#general-and-basic-methodologies)
  * [Pre-trained Models](#pre-trained-models)
  * [Optical Flow](#optical-flow)
  * [Transformers](#transformers)
  * [Low Light](#low-light)
* [Transfer Learning](#transfer-learning)
* [Datasets](#datasets)
* [Challenges](#challenges)
* [Theses and dissertations](#theses-and-dissertations)

### Surveys

- [Deep-learning Based Egocentric Action Anticipation: A Survey](https://www.researchsquare.com/article/rs-3156532/v1) - Richard Wardle, Sareh Rowlands, 2023.
- [Video Understanding with Large Language Models:A Survey](https://arxiv.org/abs/2312.17432) - Yunlong Tang, Jing Bi, Siting Xu, Luchuan Song, Susan Liang, Teng Wang, Daoan Zhang, Jie An, Jingyang Lin, Rongyi Zhu, Ali Vosoughi, Chao Huang, Zeliang Zhang, Feng Zheng, Jianguo Zhang, Ping Luo, Jiebo Luo, Chenliang Xu, 2024
- [A Survey on Deep Learning Techniques for Action Anticipation](https://arxiv.org/abs/2309.17257) - Zeyun Zhong, Manuel Martin, Michael Voit, Juergen Gall, Jürgen Beyerer, 2023.
- [Transfer Learning in Human Activity Recognition: A Survey](https://arxiv.org/abs/2401.10185) - Sourish Gunesh Dhekane, Thomas Ploetz, 2024.
- [Visual features for ego-centric activity recognition: A survey](https://dl.acm.org/doi/abs/10.1145/3211960.3211978) - Girmaw Abebe Tadesse, Andrea Cavallaro, 2018.
- [Predicting the Future from First Person (Egocentric) Vision: A Survey](https://arxiv.org/abs/2107.13411) - Ivan Rodin, Antonino Furnari, Dimitrios Mavroedis, Giovanni Maria Farinella, 2017.
- [Long-term Action Anticipation: A Quick Survey](https://publikationen.bibliothek.kit.edu/1000162010) - Zhong, Zeyun, 2022.
- [A Survey on Recent Advances of Computer Vision Algorithms for Egocentric Video](https://arxiv.org/abs/1501.02825) - Sven Bambach, 2015.
- [Egocentric Vision-based Action Recognition: A survey](https://www.sciencedirect.com/science/article/pii/S0925231221017586) - Adrián Núñez-Marcos, Gorka Azkune, Ignacio Arganda-Carreras, 2022.
- [Analysis of the hands in egocentric vision:A survey](https://arxiv.org/abs/1912.10867) - Andrea Bandini, José Zariffa, 2019.
- [A Survey of Activity Recognition in Egocentric Lifelogging datasets](https://ieeexplore.ieee.org/document/7934659) - El Asnaoui Khalid, Aksasse Hamid, Aksasse Brahim, Ouanan Mohammed, 2017.
- [Optical flow and scene flow estimation: A survey](https://www.sciencedirect.com/science/article/abs/pii/S0031320321000480) - Mingliang Zhai, Xuezhi Xiang, Ning Lv, Xiangdong Kong,  2021.
- [AutoML: A Survey of the State-of-the-Art](https://arxiv.org/abs/1908.00709) - Xin He, Kaiyong Zhao, Xiaowen Chu, 2021.
- [A Survey of Deep Learning: From Activations to Transformers](https://arxiv.org/abs/2302.00722) - Johannes Schneider, Michalis Vlachos, 2023.
- [Deep Learning: A Comprehensive Overview on Techniques, Taxonomy, Applications and Research Directions](https://link.springer.com/article/10.1007/s42979-021-00815-1) - Iqbal H. Sarker, 2021.
- [A survey on deep learning and its applications](https://www.sciencedirect.com/science/article/abs/pii/S1574013721000198) - Shi Dong, Ping Wang, Khushnood Abbas, 2021.

### Egocentric Vision

- [An Introduction to the 3rd Workshop on Egocentric (First-person) Vision](https://ieeexplore.ieee.org/document/6910078) - Steve Mann, Kris M. Kitani, Yong Jae Lee, M. S. Ryoo, Alireza Fathi, 2014.
- [Actor and Observer: Joint Modeling of First and Third-Person Videos](https://arxiv.org/abs/1804.09627) - Gunnar A. Sigurdsson, Abhinav Gupta, Cordelia Schmid, Ali Farhadi, Karteek Alahari, 2018.
- [Activity Classification from First-Person Office Videos with Visual Privacy Protection](https://link.springer.com/chapter/10.1007/978-981-19-2445-3_25) - Partho Ghosh, Md. Abrar Istiak, Nayeeb Rashid, Ahsan Habib Akash, Ridwan Abrar, Ankan Ghosh Dastider, Asif Shahriyar Sushmit & Taufiq Hasan, 2022.
- [Deep Dual Relation Modeling for Egocentric Interaction Recognition](https://arxiv.org/abs/1905.13586) - Haoxin Li, Yijun Cai, Wei-Shi Zheng, 2019.
- [Going Deeper into First-Person Activity Recognition](https://arxiv.org/abs/1605.03688) - Minghuang Ma, Haoqi Fan, Kris M. Kitani, 2016.
- [Together Recognizing, Localizing and Summarizing Actions in Egocentric Videos](https://ieeexplore.ieee.org/document/9399266) - Abhimanyu Sahu; Ananda S. Chowdhury, 2021.
- [**Unifying Few- and Zero-Shot Egocentric Action Recognition**](https://arxiv.org/abs/2006.11393) - Tyler R. Scott, Michael Shvartsman, Karl Ridgeway, 2020.
- [Text Synopsis Generation for Egocentric Videos](https://arxiv.org/abs/2005.03804) - Aidean Sharghi, Niels da Vitoria Lobo, Mubarak Shah, 2020.
- [Actor and Observer: Joint Modeling of First and Third-Person Videos](https://arxiv.org/abs/1804.09627) - Gunnar A. Sigurdsson, Abhinav Gupta, Cordelia Schmid, Ali Farhadi, Karteek Alahari, 2018.
- [Egocentric Video Task Translation](https://arxiv.org/abs/2212.06301) - Zihui Xue, Yale Song, Kristen Grauman, Lorenzo Torresani, 2022.
- [Learning Fine-grained View-Invariant Representations from Unpaired Ego-Exo Videos via Temporal Alignment](https://arxiv.org/abs/2306.05526) - Zihui Xue, Kristen Grauman, 2023.
- [Recognizing Micro-Actions and Reactions from Paired Egocentric Videos](https://ieeexplore.ieee.org/document/7780657) - Ryo Yonetani, Kris M. Kitani, Yoichi Sato, 2016.
- [Helping Hands: An Object-Aware Ego-Centric Video Recognition Model](https://arxiv.org/abs/2308.07918) - Chuhan Zhang, Ankush Gupta, Andrew Zisserman, 2023.
- [GPT4Ego: Unleashing the Potential of Pre-trained Models for Zero-Shot Egocentric Action Recognition](https://arxiv.org/abs/2401.10039) - Guangzhao Dai, Xiangbo Shu, Wenhao Wu, 2024.
- [User-adaptive Models for Recognizing Food Preparation Activities](https://dl.acm.org/doi/abs/10.1145/2506023.2506031) - Sebastian Stein, Stephen J. McKenna, 2013.
- [A Hybrid Visual Transformer for Efficient Deep Human Activity Recognition](https://www.computer.org/csdl/proceedings-article/iccvw/2023/074400a721/1Tao9WbGL7O) - Youcef Djenouri, Ahmed Nabil Belbachir, 2023.
- [EgoEnv: Human-centric environment representations from egocentric video](https://arxiv.org/abs/2207.11365) - Tushar Nagarajan, Santhosh Kumar Ramakrishnan, Ruta Desai, James Hillis, Kristen Grauman, 2022.
- [Activity Classification from First-Person Office Videos with Visual Privacy Protection](https://link.springer.com/chapter/10.1007/978-981-19-2445-3_25) - Partho Ghosh, Md. Abrar Istiak, Nayeeb Rashid, Ahsan Habib Akash, Ridwan Abrar, Ankan Ghosh Dastider, Asif Shahriyar Sushmit & Taufiq Hasan, 2021.
- [Analyzing First-Person Stories Based on Socializing, Eating and Sedentary Patterns](https://arxiv.org/abs/1707.07863) - Pedro Herruzo, Laura Portell, Alberto Soto, Beatriz Remeseiro, 2017.
- [Pixel-Level Hand Detection with Shape-Aware Structured Forests](https://link.springer.com/chapter/10.1007/978-3-319-16817-3_5) - Xiaolong Zhu, Xuhui Jia & Kwan-Yee K. Wong, 2015.
- [Activity Recognition in Egocentric Life-Logging Videos](https://link.springer.com/chapter/10.1007/978-3-319-16634-6_33) - Sibo Song, Vijay Chandrasekhar, Ngai-Man Cheung, Sanath Narayan, Liyuan Li & Joo-Hwee Lim, 2015.
- [Egocentric Scene Understanding via Multimodal Spatial Rectifier](https://arxiv.org/abs/2207.07077) - Tien Do, Khiem Vuong, Hyun Soo Park, 2022.
- [Ego-Deliver: A Large-Scale Benchmark For Egocentric Video Analysis](https://dl.acm.org/doi/10.1145/3474085.3475336) -Haonan Qiu, Pan He, Shuchun Liu, Weiyuan Shao, Feiyun Zhang, Jiajun Wang, Liang He, Feng Wang, 2021.
- [Is First Person Vision Challenging for Object Tracking?](https://arxiv.org/abs/2108.13665) - Matteo Dunnhofer, Antonino Furnari, Giovanni Maria Farinella, Christian Micheloni, 2021.
- [Making Third Person Techniques Recognize First-Person Actions in Egocentric Videos](https://arxiv.org/abs/1910.07766) - Sagar Verma, Pravin Nagar, Divam Gupta, Chetan Arora, 2019.
- [From Third Person to First Person: Dataset and Baselines for Synthesis and Retrieval](https://arxiv.org/abs/1812.00104) - Mohamed Elfeki, Krishna Regmi, Shervin Ardeshir, Ali Borji, 2018.
- [Ego-Exo: Transferring Visual Representations from Third-person to First-person Videos](https://arxiv.org/abs/2104.07905) - Yanghao Li, Tushar Nagarajan, Bo Xiong, Kristen Grauman, 2021.
- [Understanding Social Relationships in Egocentric Vision](https://www.sciencedirect.com/science/article/abs/pii/S0031320315002289) - Stefano Alletto, Giuseppe Serra, Simone Calderara, Rita Cucchiara, 2015.
- [First Person Action Recognition Using Deep Learned Descriptors](https://ieeexplore.ieee.org/document/7780656) - Suriya Singh,Chetan Arora, C. V. Jawahar, 2016.
- [Multi-Dataset, Multitask Learning of EgocentricVision Tasks](https://ieeexplore.ieee.org/document/9361177) - Georgios Kapidis, Ronald Poppe, Remco C. Veltkamp, 2021.

### Action Anticipation

- [On the Efficacy of Text-Based Input Modalities for Action Anticipation](https://arxiv.org/abs/2401.12972) - Apoorva Beedu, Karan Samel, Irfan Essa, 2024
- [Anticipating human actions by correlating past with the future with Jaccard
  similarity measures](https://openaccess.thecvf.com/content/CVPR2021/html/Fernando_Anticipating_Human_Actions_by_Correlating_Past_With_the_Future_With_CVPR_2021_paper.html) - Basura Fernando, Samitha Herath; Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), 2021, pp. 13224-13233
- [Towards Streaming Egocentric Action Anticipation](https://ieeexplore.ieee.org/abstract/document/9956090) - Antonino Furnari, Giovanni Maria Farinella,  26th International Conference on Pattern Recognition (ICPR) 2022
- [What Would You Expect? Anticipating Egocentric Actions With Rolling-Unrolling LSTMs and Modality Attention](https://openaccess.thecvf.com/content_ICCV_2019/html/Furnari_What_Would_You_Expect_Anticipating_Egocentric_Actions_With_Rolling-Unrolling_LSTMs_ICCV_2019_paper.html) - Antonino Furnari, Giovanni Maria Farinella; Proceedings of the IEEE/CVF International Conference on Computer Vision (ICCV), 2019, pp. 6252-6261
- [Rolling-Unrolling LSTMs for Action Anticipation from First-Person Video](https://arxiv.org/abs/2005.02190) - Antonino Furnari, Giovanni Maria Farinella, 2020.
- [Predicting the Future: A Jointly Learnt Model for Action Anticipation](https://openaccess.thecvf.com/content_ICCV_2019/html/Gammulle_Predicting_the_Future_A_Jointly_Learnt_Model_for_Action_Anticipation_ICCV_2019_paper.html) - Harshala Gammulle, Simon Denman, Sridha Sridharan, Clinton Fookes; Proceedings of the IEEE/CVF International Conference on Computer Vision (ICCV), 2019, pp. 5562-5571
- [Anticipative Video Transformer](https://openaccess.thecvf.com/content/ICCV2021/html/Girdhar_Anticipative_Video_Transformer_ICCV_2021_paper.html) - Rohit Girdhar, Kristen Grauman; Proceedings of the IEEE/CVF International Conference on Computer Vision (ICCV), 2021, pp. 13505-13515
- [Leveraging the Present to Anticipate the Future in Videos](https://openaccess.thecvf.com/content_CVPRW_2019/html/Precognition/Miech_Leveraging_the_Present_to_Anticipate_the_Future_in_Videos_CVPRW_2019_paper.html) - Antoine Miech, Ivan Laptev, Josef Sivic, Heng Wang, Lorenzo Torresani, Du Tran; Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR) Workshops, 2019, pp. 0-0
- [An Outlook into the Future of Egocentric Vision](https://arxiv.org/abs/2308.07123) - Chiara Plizzari, Gabriele Goletto, Antonino Furnari, Siddhant Bansal, Francesco Ragusa, Giovanni Maria Farinella, Dima Damen, Tatiana Tommasi, 2023.
- [Action Anticipation By Predicting Future
  Dynamic Images](https://openaccess.thecvf.com/content_eccv_2018_workshops/w15/html/Rodriguez_Action_Anticipation_By_Predicting_Future_Dynamic_Images_ECCVW_2018_paper.html) - Cristian Rodriguez, Basura Fernando, Hongdong Li; Proceedings of the European Conference on Computer Vision (ECCV) Workshops, 2018, pp. 0-0
- [Anticipating Visual Representations from Unlabeled Video](https://openaccess.thecvf.com/content_cvpr_2016/html/Vondrick_Anticipating_Visual_Representations_CVPR_2016_paper.html) - Carl Vondrick, Hamed Pirsiavash, Antonio Torralba; Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition (CVPR), 2016, pp. 98-106
- [Object-centric Video Representation for Long-term Action Anticipation](https://openaccess.thecvf.com/content/WACV2024/html/Zhang_Object-Centric_Video_Representation_for_Long-Term_Action_Anticipation_WACV_2024_paper.html) - Ce Zhang, Changcheng Fu, Shijie Wang, Nakul Agarwal, Kwonjoon Lee, Chiho Choi, Chen Sun; Proceedings of the IEEE/CVF Winter Conference on Applications of Computer Vision (WACV), 2024, pp. 6751-6761
- [Anticipative Feature Fusion Transformer for Multi-Modal Action Anticipation](https://openaccess.thecvf.com/content/WACV2023/html/Zhong_Anticipative_Feature_Fusion_Transformer_for_Multi-Modal_Action_Anticipation_WACV_2023_paper.html) - Zeyun Zhong, David Schneider, Michael Voit, Rainer Stiefelhagen, Jürgen Beyerer; Proceedings of the IEEE/CVF Winter Conference on Applications of Computer Vision (WACV), 2023, pp. 6068-6077
- [DIFFANT: Diffusion Models for Action Anticipation](https://arxiv.org/abs/2311.15991) - Zeyun Zhong, Chengzhi Wu, Manuel Martin, Michael Voit, Juergen Gall, Jürgen Beyerer, 2023.
- [Knowledge Distillation for Action Anticipation
  via Label Smoothing](https://arxiv.org/abs/2004.07711) - Guglielmo Camporese, Pasquale Coscia, Antonino Furnari, Giovanni Maria Farinella, Lamberto Ballan, 2020.
- [VS-TransGRU: A Novel Transformer-GRU-based Framework
  Enhanced by Visual-Semantic Fusion for Egocentric Action
  Anticipation](https://arxiv.org/abs/2307.03918) - Congqi Cao, Ze Sun, Qinyi Lv, Lingtong Min, Yanning Zhang,2023.
- [**Seeing and Hearing Egocentric Actions: How Much CanWe Learn?**](https://arxiv.org/abs/1910.06693) - Alejandro Cartas, Jordi Luque, Petia Radeva, Carlos Segura, Mariella Dimiccoli,2019.
- [Anticipating human actions by correlating past with the future with Jaccard similarity measures](https://arxiv.org/abs/2105.12414) - Basura Fernando, Samitha Herath,2021.
- [Recognizing Personal Locations From
  Egocentric Videos](https://ieeexplore.ieee.org/document/7588113) - Antonino Furnari, Giovanni Maria Farinella, Sebastiano Battiato, 2016.
- [Egocentric Audio-Visual Object Localization](https://arxiv.org/abs/2303.13471) - Chao Huang, Yapeng Tian, Anurag Kumar, Chenliang Xu, 2023.
- [With a Little Help from my Temporal Context:Multimodal Egocentric Action Recognition](https://arxiv.org/abs/2111.01024) - Evangelos Kazakos, Jaesung Huh, Arsha Nagrani, Andrew Zisserman, Dima Damen, 2021.
- [Hybrid Egocentric Activity Anticipation Framework via Memory-Augmented Recurrent and One-shot Representation Forecasting](https://ieeexplore.ieee.org/document/9878625) - Tianshan Liu; Kin-Man Lam, 2022.
- [**Joint HandMotion and Interaction Hotspots Prediction from Egocentric Videos**](https://arxiv.org/abs/2204.01696) - Shaowei Liu, Subarna Tripathi, Somdeb Majumdar, Xiaolong Wang, 2022.
- [Summarize the Past to Predict the Future: Natural Language Descriptions of Context Boost Multimodal Object Interaction Anticipation](https://arxiv.org/abs/2301.09209) - Razvan-George Pasca, Alexey Gavryushin, Yen-Ling Kuo, Luc Van Gool, Otmar Hilliges, Xi Wang, 2023.
- [**Leveraging Next-Active Objects for Context-Aware Anticipation in Egocentric Videos**](https://arxiv.org/abs/2308.08303) - Sanket Thakur, Cigdem Beyan, Pietro Morerio, Vittorio Murino, Alessio Del Bue, 2023.
- [Memory-and-Anticipation Transformer for Online Action Understanding](https://arxiv.org/abs/2308.07893) - Jiahao Wang, Guo Chen, Yifei Huang, Limin Wang, Tong Lu, 2023.
- [Multi-Modal Temporal Convolutional Network for Anticipating Actions in Egocentric Videos](https://arxiv.org/abs/2107.09504) - Olga Zatsarynna, Yazan Abu Farha, Juergen Gall, 2021.
- [What IfWe Could Not See? Counterfactual Analysis for Egocentric Action Anticipation](https://www.ijcai.org/proceedings/2021/182) - Tianyu Zhang, Weiqing Min, Jiahao Yang, Tao Liu, Shuqiang Jiang, Yong Rui, 2021.

### Deep Learning Methodologies and Architectures

#### Geneal and Basic Methodologies

- [Fast R-CNN](https://arxiv.org/abs/1504.08083) - Ross Girshick, 2015.
- [Faster R-CNN: Towards Real-Time Object Detection with Region Proposal Networks](https://arxiv.org/abs/1506.01497) -Shaoqing Ren, Kaiming He, Ross Girshick, Jian Sun, 2015.
- [Mask R-CNN](https://arxiv.org/abs/1703.06870) - Kaiming He, Georgia Gkioxari, Piotr Dollár, Ross Girshick, 2017.
- [Deep Residual Learning for Image Recognition](https://arxiv.org/abs/1512.03385) - Kaiming He, Xiangyu Zhang, Shaoqing Ren, Jian Sun, 2015.
- [Visualizing and Understanding Convolutional Networks](https://arxiv.org/abs/1311.2901) - Matthew D Zeiler, Rob Fergus, 2013.

### Pre-Trained Models

#### Optical Flow

- [Traditional and modern strategies for optical flow: an investigation](https://link.springer.com/article/10.1007/s42452-021-04227-x) - Syed Tafseer Haider Shah & Xiang Xuezhi, 2021.

#### Transformers

- [Attention Is All You Need](https://arxiv.org/abs/1706.03762) - Ashish Vaswani, Noam Shazeer, Niki Parmar, Jakob Uszkoreit, Llion Jones, Aidan N. Gomez, Lukasz Kaiser, Illia Polosukhin, 2017.
- [A review on the attention mechanism of deep learning](https://www.sciencedirect.com/science/article/abs/pii/S092523122100477X) - Zhaoyang Niu, Guoqiang Zhong, Hui Yu, 2021.
- [BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding](https://arxiv.org/abs/1810.04805) - Jacob Devlin, Ming-Wei Chang, Kenton Lee, Kristina Toutanova, 2018.

#### Low Light

- [Attention-Based Deep Learning Framework for Action Recognition in a Dark Environment](https://www.researchgate.net/publication/376893531_Attention-Based_Deep_Learning_Framework_for_Action_Recognition_in_a_Dark_Environment) - Muhammad MunsifMuhammad MunsifSamee Ullah KhanSamee Ullah KhanNoman KhanNoman KhanSung Wook BaikSung Wook Baik, 2024
- [Going Deeper into Recognizing Actions in Dark Environments: A Comprehensive Benchmark Study](https://arxiv.org/abs/2202.09545) - Yuecong Xu, Jianfei Yang, Haozhi Cao, Jianxiong Yin, Zhenghua Chen, Xiaoli Li, Zhengguo Li, Qianwen Xu, 2023.
- [Delta Sampling R-BERT for limited data and low-light action recognition](https://arxiv.org/abs/2107.05202) - Sanchit Hira, Ritwik Das, Abhinav Modi, Daniil Pakhomov, 2023.
- [Human Action Recognition in Dark Videos](https://ieeexplore.ieee.org/document/9670923) - Harsh Rakesh Patel, Jash Tejaskumar Doshi, 2021.
- [IndGIC: Supervised Action Recognition under Low Illumination](https://arxiv.org/abs/2308.15345) - Jingbo Zeng, 2023.
- [Adaptive Unfolding Total Variation Network for Low-Light Image Enhancement](https://arxiv.org/abs/2110.00984) - Chuanjun Zheng, Daming Shi, Wentian Shi, 2021.

### Transfer Learning

- [TransNet: A Transfer Learning-Based Network for Human Action Recognition](https://arxiv.org/abs/2309.06951) - K. Alomar, X. Cai, 2023.

#### Datasets

- [IndustReal] - The IndustReal dataset contains 84 videos, demonstrating how 27 participants perform maintenance and assembly procedures on a construction-toy assembly set. WACV 2024. [[paper]](https://arxiv.org/abs/2310.17323)
- [ENIGMA-51](https://iplab.dmi.unict.it/ENIGMA-51/#paper) - ENIGMA-51 is a new egocentric dataset acquired in an industrial scenario by 19 subjects who followed instructions to complete the repair of electrical boards using industrial tools (e.g., electric screwdriver) and equipments (e.g., oscilloscope). The 51 egocentric video sequences are densely annotated with a rich set of labels that enable the systematic study of human behavior in the industrial domain. WACV 2023. [[paper]](https://arxiv.org/abs/2309.14809)
- [VidChapters-7M](https://antoyang.github.io/vidchapters.html) - VidChapters-7M, a dataset of 817K user-chaptered videos including 7M chapters in total. VidChapters-7M is automatically created from videos online in a scalable manner by scraping user-annotated chapters and hence without any additional manual annotation. NeurIPS 2023. [[paper]](https://arxiv.org/abs/2309.13952)
- [POV-Surgery](https://batfacewayne.github.io/POV_Surgery_io/) - POV-Surgery, a large-scale, synthetic, egocentric dataset focusing on pose estimation for hands with different surgical gloves and three orthopedic surgical instruments, namely scalpel, friem, and diskplacer. Our dataset consists of 53 sequences and 88,329 frames, featuring high-resolution RGB-D video streams with activity annotations, accurate 3D and 2D annotations for hand-object pose, and 2D hand-object segmentation masks. MICCAI 2023. [[paper]](https://arxiv.org/abs/2307.10387)
- [ARGO1M](https://chiaraplizz.github.io/what-can-a-cook/) - Action Recognition Generalisation dataset (ARGO1M) from videos and narrations from Ego4D. ARGO1M is the first to test action generalisation across both scenario and location shifts, and is the largest domain generalisation dataset across images and video. ICCV 2023. [[paper]](https://arxiv.org/abs/2306.08713)
- [EgoObjects] - EgoObjects, a large-scale egocentric dataset for fine-grained object understanding. contains over 9K videos collected by 250 participants from 50+ countries using 4 wearable devices, and over 650K object annotations from 368 object categories. ICCV 2023. [[paper]](https://openaccess.thecvf.com/content/ICCV2023/html/Zhu_EgoObjects_A_Large-Scale_Egocentric_Dataset_for_Fine-Grained_Object_Understanding_ICCV_2023_paper.html)
- [HoloAssist](https://holoassist.github.io/) - HoloAssist: a large-scale egocentric human interaction dataset that spans 166 hours of data captured by 350 unique instructor-performer pairs, wearing mixed-reality headsets during collaborative tasks. ICCV 2023. [[paper]](https://openaccess.thecvf.com/content/ICCV2023/html/Wang_HoloAssist_an_Egocentric_Human_Interaction_Dataset_for_Interactive_AI_Assistants_ICCV_2023_paper.html)
- [AssemblyHands](https://assemblyhands.github.io/) - AssemblyHands, a large-scale benchmark dataset with accurate 3D hand pose annotations, to facilitate the study of egocentric activities with challenging handobject interactions. CVPR 2023. [[paper]](https://openaccess.thecvf.com/content/CVPR2023/papers/Ohkawa_AssemblyHands_Towards_Egocentric_Activity_Understanding_via_3D_Hand_Pose_Estimation_CVPR_2023_paper.pdf)
- [EpicSoundingObject](https://github.com/WikiChao/Ego-AV-Loc) - Epic Sounding Object dataset with sounding object annotations to benchmark the localization performance in egocentric videos. CVPR 2023. [[paper]](https://openaccess.thecvf.com/content/CVPR2023/papers/Huang_Egocentric_Audio-Visual_Object_Localization_CVPR_2023_paper.pdf)
- [VOST](https://www.vostdataset.org/) - Video Object Segmentation under Transformations (VOST). It consists of more than 700 high-resolution videos, captured in diverse environments, which are 20 seconds long on average and densely labeled with instance masks. CVPR 2023. [[paper]](https://openaccess.thecvf.com/content/CVPR2023/html/Tokmakov_Breaking_the_Object_in_Video_Object_Segmentation_CVPR_2023_paper.html)
- [Aria Digital Twin](https://www.projectaria.com/datasets/adt/) - Aria Digital Twin (ADT) - an egocentric dataset captured using Aria glasses with extensive object, environment, and human level ground truth. This ADT release contains 200 sequences of real-world activities conducted by Aria wearers. Very challenging research problems such as 3D object detection and tracking, scene reconstruction and understanding, sim-to-real learning, human pose prediction - while also inspiring new machine perception tasks for augmented reality (AR) applications.  2023. [[paper]](https://arxiv.org/pdf/2306.06362.pdf)
- [WEAR](https://mariusbock.github.io/wear/) - The dataset comprises data from 18 participants performing a total of 18 different workout activities with untrimmed inertial (acceleration) and camera (egocentric video) data recorded at 10 different outside locations.  2023. [[paper]](https://arxiv.org/abs/2304.05088)
- [EPIC Fields](https://epic-kitchens.github.io/epic-fields/) - EPIC Fields, an augmentation of EPIC-KITCHENS with 3D camera information. Like other datasets for neural rendering, EPIC Fields removes the complex and expensive step of reconstructing cameras using photogrammetry, and allows researchers to focus on modelling problems.  2023. [[paper]](https://arxiv.org/abs/2306.08731)
- [EGOFALLS] - The dataset comprises 10,948 video samples from 14 subjects, focusing on falls among the elderly. Extracting multimodal descriptors from egocentric camera videos.  2023. [[paper]](https://arxiv.org/abs/2309.04579)
- [Exo2EgoDVC] - EgoYC2, a novel egocentric dataset, adapts procedural captions from YouCook2 to cooking videos re-recorded with head-mounted cameras. Unique in its weakly-paired approach, it aligns caption content with exocentric videos, distinguishing itself from other datasets focused on action labels.  2023. [[paper]](https://arxiv.org/abs/2311.16444)
- [EgoWholeBody](https://people.mpi-inf.mpg.de/~jianwang/projects/egowholemocap/) - EgoWholeBody, a large synthetic dataset, comprising 840,000 high-quality egocentric images captured across a diverse range of whole-body motion sequences. Quantitative and qualitative evaluations demonstrate the effectiveness of our method in producing high-quality whole-body motion estimates from a single egocentric camera.  2023. [[paper]](https://arxiv.org/abs/2311.16495)
- [Ego-Exo4D](https://ego-exo4d-data.org/) - Ego-Exo4D, a vast multimodal multiview video dataset capturing skilled human activities in both egocentric and exocentric perspectives (e.g., sports, music, dance). With 800+ participants in 13 cities, it offers 1,422 hours of combined footage, featuring diverse activities in 131 natural scene contexts, ranging from 1 to 42 minutes per video.  2023. [[paper]](https://arxiv.org/abs/2311.18259)
- [IT3DEgo] - IT3DEgo dataset: Addresses 3D instance tracking using egocentric sensors (AR/VR). Recorded in diverse indoor scenes with HoloLens2, it comprises 50 recordings (5+ minutes each). Evaluates tracking performance in 3D coordinates, leveraging camera pose and allocentric representation.  2023. [[paper]](https://arxiv.org/pdf/2312.04117.pdf)
- [Touch and Go](https://touch-and-go.github.io/) - we present a dataset, called Touch and Go, in which human data collectors walk through a variety of environments, probing objects with tactile sensors and simultaneously recording their actions on video. NeurIPS 2022. [[paper]](https://arxiv.org/pdf/2211.12498.pdf)
- [EPIC-Visor](https://epic-kitchens.github.io/VISOR/) - VISOR, a new dataset of pixel annotations and a benchmark suite for segmenting hands and active objects in egocentric video. NeurIPS 2022. [[paper]](https://proceedings.neurips.cc/paper_files/paper/2022/hash/590a7ebe0da1f262c80d0188f5c4c222-Abstract-Datasets_and_Benchmarks.html)
- [AssistQ](https://showlab.github.io/assistq/) - A new dataset comprising 529 question-answer samples derived from 100 newly filmed first-person videos. Each question should be completed with multi-step guidances by inferring from visual details (e.g., buttons' position) and textural details (e.g., actions like press/turn). ECCV 2022. [[paper]](https://arxiv.org/abs/2203.04203)
- [EgoProceL](https://sid2697.github.io/egoprocel/) - EgoProceL dataset focuses on the key-steps required to perform a task instead of every action in the video. EgoProceL consistis of 62 hours of videos captured by 130 subjects performing 16 tasks. ECCV 2022. [[paper]](https://arxiv.org/pdf/2207.10883.pdf)
- [EgoHOS](https://github.com/owenzlz/EgoHOS) - EgoHOS, a labeled dataset consisting of 11,243 egocentric images with per-pixel segmentation labels of hands and objects being interacted with during a diverse array of daily activities. Our dataset is the first to label detailed hand-object contact boundaries. ECCV 2022. [[paper]](https://arxiv.org/abs/2208.03826)
- [UnrealEgo](https://4dqv.mpi-inf.mpg.de/UnrealEgo/) - UnrealEgo, i.e., a new large-scale naturalistic dataset for egocentric 3D human pose estimation. It is the first dataset to provide in-the-wild stereo images with the largest variety of motions among existing egocentric datasets. ECCV 2022. [[paper]](https://arxiv.org/abs/2208.01633)
- [Assembly101](https://assembly101.github.io/) - Procedural activity dataset featuring 4321 videos of people assembling and disassembling 101 “take-apart” toy vehicles. CVPR 2022. [[paper]](https://arxiv.org/pdf/2203.14712.pdf)
- [EgoPAT3D](https://ai4ce.github.io/EgoPAT3D/) - A large multimodality dataset of more than 1 million frames of RGB-D and IMU streams, with evaluation metrics based on high-quality 2D and 3D labels from semi-automatic annotation. CVPR 2022. [[paper]](https://arxiv.org/abs/2203.13116)
- [AGD20K](https://github.com/lhc1224/Cross-View-AG) - Affordance dataset constructed by collecting and labeling over 20K images from 36 affordance categories. CVPR 2022. [[paper]](https://arxiv.org/abs/2203.09905)
- [HOI4D](https://hoi4d.github.io/) - A large-scale 4D egocentric dataset with rich annotations, to catalyze the research of category-level human-object interaction. HOI4D consists of 2.4M RGB-D egocentric video frames over 4000 sequences collected by 4 participants interacting with 800 different object instances from 16 categories over 610 different indoor rooms. Frame-wise annotations for panoptic segmentation, motion segmentation, 3D hand pose, category-level object pose and hand action have also been provided, together with reconstructed object meshes and scene point clouds. CVPR 2022. [[paper]](https://arxiv.org/abs/2203.01577)
- [EgoPW](https://arxiv.org/abs/2201.07929) - A dataset captured by a head-mounted fisheye camera and an auxiliary external camera, which provides an additional observation of the human body from a third-person perspective. CVPR 2022. [[paper]](https://arxiv.org/abs/2201.07929)
- [Ego4D](https://ego4d-data.org) - 3,025 hours of daily-life activity video spanning hundreds of scenarios (household, outdoor, workplace, leisure, etc.) captured by 855 unique camera wearers from 74 worldwide locations and 9 different countries. CVPR 2022. [[paper]](https://www.cs.utexas.edu/~grauman/papers/ego4d-cvpr2022.pdf)
- [N-EPIC-Kitchens](https://github.com/EgocentricVision/N-EPIC-Kitchens) - N-EPIC-Kitchens, the first event-based camera extension of the large-scale EPIC-Kitchens dataset. CVPR 2022. [[paper]](https://openaccess.thecvf.com/content/CVPR2022/html/Plizzari_E2GOMOTION_Motion_Augmented_Event_Stream_for_Egocentric_Action_Recognition_CVPR_2022_paper.html)
- [EPIC-SOUNDS](https://epic-kitchens.github.io/epic-sounds/) - [**[paper]**](https://arxiv.org/abs/2302.00646)
- [EasyCom-Clustering](https://arxiv.org/abs/2203.13166) - The first large-scale egocentric video face clustering dataset.  2022. [[paper]](https://arxiv.org/abs/2203.13166)
- [First2Third-Pose](https://github.com/nudlesoup/First2Third-Pose) - A new paired synchronized dataset of nearly 2,000 videos depicting human activities captured from both first- and third-view perspectives.  2022. [[paper]](https://arxiv.org/abs/2201.02017)
- [HMDB](https://serre-lab.clps.brown.edu/resource/hmdb-a-large-human-motion-database/) - A large human motion database [[paper]](https://arxiv.org/pdf/1505.04868.pdf)
- [TREK-100](https://machinelearning.uniud.it/datasets/trek100/) - Object tracking in first person vision. WICCV 2021. [[paper]](https://openaccess.thecvf.com/content/ICCV2021W/VOT/html/Dunnhofer_Is_First_Person_Vision_Challenging_for_Object_Tracking_ICCVW_2021_paper.html)
- [MECCANO](https://iplab.dmi.unict.it/MECCANO/) - 20 subject assembling a toy motorbike. WACV 2021. [[paper]](https://openaccess.thecvf.com/content/WACV2021/html/Ragusa_The_MECCANO_Dataset_Understanding_Human-Object_Interactions_From_Egocentric_Videos_in_WACV_2021_paper.html)
- [EPIC-Kitchens 2020](https://epic-kitchens.github.io/2020-100) - Subjects performing unscripted actions in their native environments. IJCV 2021. [[paper]](https://link.springer.com/article/10.1007/s11263-021-01531-2)
- [H2O](https://taeinkwon.com/projects/h2o/) - H2O (2 Hands and Objects), provides synchronized multi-view RGB-D images, interaction labels, object classes, ground-truth 3D poses for left & right hands, 6D object poses, ground-truth camera poses, object meshes and scene point clouds. ICCV 2021. [[paper]](https://openaccess.thecvf.com/content/ICCV2021/papers/Kwon_H2O_Two_Hands_Manipulating_Objects_for_First_Person_Interaction_Recognition_ICCV_2021_paper.pdf)
- [HOMAGE](https://homeactiongenome.org/) - Home Action Genome (HOMAGE): a multi-view action dataset with multiple modalities and view-points supplemented with hierarchical activity and atomic action labels together with dense scene composition labels. CVPR 2021. [[paper]](https://openaccess.thecvf.com/content/CVPR2021/papers/Rai_Home_Action_Genome_Cooperative_Compositional_Action_Understanding_CVPR_2021_paper.pdf)
- [EgoCom](https://github.com/facebookresearch/EgoCom-Dataset) - A natural conversations dataset containing multi-modal human communication data captured simultaneously from the participants' egocentric perspectives. TPAMI 2020. [[paper]](https://ieeexplore.ieee.org/document/9200754)
- [EGO-CH](https://iplab.dmi.unict.it/EGO-CH/) - 70 subjects visiting two cultural sites in Sicily, Italy. Pattern Recognition Letters 2020. [[paper]](https://www.sciencedirect.com/science/article/pii/S0167865519303794)
- [EPIC-Tent](https://data.bristol.ac.uk/data/dataset/2ite3tu1u53n42hjfh3886sa86) - 29 participants assembling a tent while wearing two head-mounted cameras. ICCV 2019. [[paper]](https://openaccess.thecvf.com/content_ICCVW_2019/html/EPIC/Jang_EPIC-Tent_An_Egocentric_Video_Dataset_for_Camping_Tent_Assembly_ICCVW_2019_paper.html)
- [EPIC-Kitchens 2018](https://epic-kitchens.github.io/2018) - 32 subjects performing unscripted actions in their native environments. ECCV 2018. [[paper]](https://openaccess.thecvf.com/content_ECCV_2018/html/Dima_Damen_Scaling_Egocentric_Vision_ECCV_2018_paper.html)
- [Charades-Ego](https://allenai.org/plato/charades/) - Paired first-third person videos.
- [EGTEA Gaze+](http://cbs.ic.gatech.edu/fpv/) - 32 subjects, 86 cooking sessions, 28 hours.
- [ADL](https://www.csee.umbc.edu/~hpirsiav/papers/ADLdataset/) - 20 subjects performing daily activities in their native environments.
- [CMU kitchen](http://kitchen.cs.cmu.edu/index.php) - Multimodal, 18 subjects cooking 5 different recipes: brownies, eggs, pizza, salad, sandwich.
- [EgoSeg](http://www.vision.huji.ac.il/egoseg/) - Long term actions (walking, running, driving, etc.).
- [First-Person Social Interactions](http://ai.stanford.edu/~alireza/Disney/) - 8 subjects at disneyworld.
- [UEC Dataset](http://www.cs.cmu.edu/~kkitani/datasets/) - Two choreographed datasets with different egoactions (walk, jump, climb, etc.) + 6 YouTube sports videos.
- [JPL](http://michaelryoo.com/jpl-interaction.html) - Interaction with a robot.
- [FPPA](http://tamaraberg.com/prediction/Prediction.html) - Five subjects performing 5 daily actions.
- [UT Egocentric](http://vision.cs.utexas.edu/projects/egocentric/index.html) - 3-5 hours long videos capturing a person's day.
- [VINST/ Visual Diaries](http://www.csc.kth.se/cvap/vinst/NovEgoMotion.html) - 31 videos capturing the visual experience of a subject walking from metro station to work.
- [Bristol Egocentric Object Interaction (BEOID)](https://www.cs.bris.ac.uk/~damen/BEOID/) - 8 subjects, six locations. Interaction with objects and environment.
- [Object Search Dataset](https://github.com/Mengmi/deepfuturegaze_gan) - 57 sequences of 55 subjects on search and retrieval tasks.
- [UNICT-VEDI](http://iplab.dmi.unict.it/VEDI/) - Different subjects visiting a museum.
- [UNICT-VEDI-POI](http://iplab.dmi.unict.it/VEDI_POIs/) - Different subjects visiting a museum.
- [Simulated Egocentric Navigations](http://iplab.dmi.unict.it/SimulatedEgocentricNavigations/) - Simulated navigations of a virtual agent within a large building.
- [EgoCart](http://iplab.dmi.unict.it/EgocentricShoppingCartLocalization/) - Egocentric images collected by a shopping cart in a retail store.
- [Unsupervised Segmentation of Daily Living Activities](http://iplab.dmi.unict.it/dailylivingactivities) - Egocentric videos of daily activities.
- [Visual Market Basket Analysis](http://iplab.dmi.unict.it/vmba/) - Egocentric images collected by a shopping cart in a retail store.
- [Location Based Segmentation of Egocentric Videos](http://iplab.dmi.unict.it/PersonalLocationSegmentation/) - Egocentric videos of daily activities.
- [Recognition of Personal Locations from Egocentric Videos](http://iplab.dmi.unict.it/PersonalLocations/) - Egocentric videos clips of daily.
- [EgoGesture](http://www.nlpr.ia.ac.cn/iva/yfzhang/datasets/egogesture.html) - 2k videos from 50 subjects performing 83 gestures.
- [EgoHands](http://vision.soic.indiana.edu/projects/egohands/) - 48 videos of interactions between two people.
- [DoMSEV](http://www.verlab.dcc.ufmg.br/semantic-hyperlapse/cvpr2018-dataset/) - 80 hours/different activities.
- [DR(eye)VE](http://aimagelab.ing.unimore.it/dreyeve) - 74 videos of people driving.
- [THU-READ](http://ivg.au.tsinghua.edu.cn/dataset/THU_READ.php) - 8 subjects performing 40 actions with a head-mounted RGBD camera.
- [EgoDexter](https://handtracker.mpi-inf.mpg.de/projects/OccludedHands/EgoDexter.htm) - 4 sequences with 4 actors (2 female), and varying interactions with various objects and and cluttered background.  [[paper]](https://handtracker.mpi-inf.mpg.de/projects/OccludedHands/index.htm)
- [First-Person Hand Action (FPHA)](https://guiggh.github.io/publications/first-person-hands/) - 3D hand-object interaction. Includes 1175 videos belonging to 45 different activity categories performed by 6 actors.  [[paper]](https://arxiv.org/pdf/1704.02463.pdf)
- [UTokyo Paired Ego-Video (PEV)](https://yonetaniryo.github.io/fpv_data.html) - 1,226 pairs of first-person clips extracted from the ones recorded synchronously during dyadic conversations.
- [UTokyo Ego-Surf](https://yonetaniryo.github.io/fpv_data.html) - Contains 8 diverse groups of first-person videos recorded synchronously during face-to-face conversations.
- [TEgO: Teachable Egocentric Objects Dataset](https://iamlabumd.github.io/tego/) - Contains egocentric images of 19 distinct objects taken by two people for training a teachable object recognizer.
- [Multimodal Focused Interaction Dataset](https://cvip.computing.dundee.ac.uk/datasets/focusedinteraction/) - Contains 377 minutes of continuous multimodal recording captured during 19 sessions, with 17 conversational partners in 18 different indoor/outdoor locations.
- [Online Action Detection
  ](https://link.springer.com/chapter/10.1007/978-3-319-46454-1_17) - Roeland De Geest, Efstratios Gavves, Amir Ghodrati, Zhenyang Li, Cees Snoek & Tinne Tuytelaars, 2016.
- [Breakfast](https://serre-lab.clps.brown.edu/resource/breakfast-actions-dataset/) - [**[paper]**](https://ieeexplore.ieee.org/document/6909500)
- [AVA Kinetics](https://research.google.com/ava/) - [**[paper]**](https://arxiv.org/abs/2005.00214)
- [TV Human Interactions Dataset](https://www.robots.ox.ac.uk/~vgg/data/tv_human_interactions/)
- [FPV-O](https://www.eecs.qmul.ac.uk/~andrea/fpvo.html) - [**[paper]**](https://link.springer.com/chapter/10.1007/978-3-030-20984-1_3)
- [BON](https://ieee-dataport.org/open-access/bon-egocentric-vision-dataset-office-activity-recognition) - [**[paper]**](https://arxiv.org/abs/2209.05077)
- [EgoTracks](https://ego4d-data.org/docs/data/egotracks/) - [**[paper]**](https://arxiv.org/abs/2301.03213)
- [EGOK360](https://egok360.github.io/) - [**[paper]**](https://arxiv.org/abs/2010.08055)

### Challenges

- [Ego4D](https://ego4d-data.org)- Episodic Memory, Hand-Object Interactions, AV Diarization, Social, Forecasting.
- [Epic Kithchen Challenge](https://epic-kitchens.github.io/)- Action Recognition, Action Detection, Action Anticipation, Unsupervised Domain Adaptation for Action Recognition, Multi-Instance Retrieval.
- [MECCANO](https://iplab.dmi.unict.it/MECCANO/challenge.html)- Multimodal Action Recognition (RGB-Depth-Gaze).
- [THUMOS](https://www.crcv.ucf.edu/THUMOS14/home.html) - The THUMOS challenge on action recognition for videos "in the wild"

### Theses and dissertations

- [Action Recognition in Videos using Supervised and Self-Supervised Deep Learning Techniques](https://rua.ua.es/dspace/handle/10045/125585?locale=en) - Benavent-Lledó, Manuel, 2022.
