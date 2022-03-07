# Beyond Accuracy: A Feature Crossing Method for Chinese Thesis Reviewer Recommendation

# Abstract
Peer review refers to the process of a group of reviewers jointly assessing a thesis or a journal article. Reviewer assignment constitutes the major challenge in this process. However, many studies only focus on the predictive accuracy of the matching degree between reviewers and theses. Recent works show that the unitary accuracy metric can not satisfy the requirement of maximizing the comprehensive performance of the reviewer recommendation system. In this paper, we introduce a Chinese thesis reviewer personalized recommendation model(TRPRM) for the reviewer assignment problem. The TRPRM focuses on an extra crucial metric in recommendation system evaluation: novelty. The model uses a feature crossing method to mine the interactions among different research interests of author. Moreover, we analyze the role of accuracy and novelty as indicators of recommendation quality and present novel ways of how to measure them. Lastly, we apply our model to the reviewer assignment problem using a real dataset from a university in China to verify the comprehensive performance of our proposed approach.

# Dataset Column Description

Column 1: reviewerID

Column 2: thesisID

Column 3: isMatch

Column 4: the number of review records

Column 5-34: interest similarity (definition 5)

# If you find this dataset useful, please cite the following paper:
@INPROCEEDINGS{9658668,  author={Yong, Yaoguang and Yao, Zheng and Zhao, Yawei},  booktitle={2021 IEEE International Conference on Systems, Man, and Cybernetics (SMC)},   title={Beyond Accuracy: A Feature Crossing Method for Chinese Thesis Reviewer Recommendation},   year={2021},  volume={},  number={},  pages={1151-1158},  doi={10.1109/SMC52423.2021.9658668}}
