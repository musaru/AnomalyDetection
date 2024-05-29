# AnomalyDetection
**#Anomaly Detection in Weakly Supervised Videos Using Multistage Graphs and General Deep Learning Based Spatial–Temporal Feature Enhancement**

**Abstract**
Weakly supervised video anomaly detection (WS-VAD) is a crucial research domain in
computer vision for the implementation of intelligent surveillance systems. Many researchers have been
working to develop WS-VAD systems using various technologies by assessing anomaly scores. However,
they are still facing challenges because of lacking effective feature extraction. To mitigate this limitation,
we propose a multi-stage deep-learning model for separating abnormal events from normality to extract the
hierarchical effective features. In the first stage, we extract two stream features using pre-trained techniques:
the first stream employs a ViT-based CLIP module to select top-k features, while the second stream
utilizes a CNN-based I3D module integrated into the Temporal Contextual Aggregation (TCA) mechanism.
These features are concatenated and fed into the second-stage module, where an Uncertainty-regulated
Dual Memory Units (UR-DMU) model is employed to learn representations of regular and abnormal
data simultaneously. The UR-DMU integrates global and local structures, leveraging Graph Convolutional
Networks (GCN) and Global and Local Multi-Head Self Attention (GL-MHSA) modules to capture video
associations. Subsequently, feature reduction is achieved using the multilayer-perceptron (MLP) integration
with the Prompt-Enhanced Learning (PEL) module via the knowledge-based prompt. Finally, we employed
a classifier module to predict the snippet-level anomaly scores. In the training phase, the based function
transfers the snippet-level scores into bag-level predictions for learning high activation in anomalous cases.
Our approach integrates these cutting-edge technologies and methodologies, offering a comprehensive
solution to video-based anomaly detection. Extensive experiments on ShanghaiTech, XD-Violence, and
UCF-Crime datasets validate the superiority of our method over state-of-the-art approaches by a substantial
margin. We believe that our model holds significant promise for real-world applications, demonstrating
superior performance and efficacy in anomaly detection tasks.
INDEX TERMS Temporal contextual aggregation (TCA),
For details code please see the below link:
**https://github.com/yatoyun/PEL4VAD-test**
