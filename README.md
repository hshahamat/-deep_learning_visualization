# Brain MRI analysis using a deep learning based evolutionary approach
Convolutional neural network (CNN) models have recently demonstrated impressive performance in
medical image analysis. However, there is no clear understanding of why they perform so well, or
what they have learned. In this paper, a three-dimensional convolutional neural network (3D-CNN) is
employed to classify brain MRI scans into two predefined groups. In addition, a genetic algorithm based
brain masking (GABM) method is proposed as a visualization technique that provides new insights into
the function of the 3D-CNN. The proposed GABM method consists of two main steps. In the first step,
a set of brain MRI scans is used to train the 3D-CNN. In the second step, a genetic algorithm (GA)
is applied to discover knowledgeable brain regions in the MRI scans. The knowledgeable regions are
those areas of the brain which the 3D-CNN has mostly used to extract important and discriminative
features from them. For applying GA on the brain MRI scans, a new chromosome encoding approach
is proposed. The proposed framework has been evaluated using ADNI (including 140 subjects for
Alzheimer’s disease classification) and ABIDE (including 1000 subjects for Autism classification) brain
MRI datasets. Experimental results show a 5-fold classification accuracy of 0.85 for the ADNI dataset
and 0.70 for the ABIDE dataset. The proposed GABM method has extracted 6 to 65 knowledgeable brain
regions in ADNI dataset (and 15 to 75 knowledgeable brain regions in ABIDE dataset). These regions
are interpreted as the segments of the brain which are mostly used by the 3D-CNN to extract features
for brain disease classification. Experimental results show that besides the model interpretability, the
proposed GABM method has increased final performance of the classification model in some cases
with respect to model parameters.
