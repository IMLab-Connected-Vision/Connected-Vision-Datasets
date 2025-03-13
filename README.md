# Connected-Vision-Datasets
<p align="center"> The table below provides an overview of various publicly available vision datasets used in action recognition, anomaly detection, and human activity recognition. Each dataset varies in terms of class diversity, resolution, and application focus. </p>

| #  | Dataset                                   | No of Classes | <p align="center">Description </p> |
|----|--------------------------------------------|--------------|-------------|
| 1  | [NTU RGB+D](https://rose1.ntu.edu.sg/dataset/actionRecognition/) | 120 | <p align="justify"> This dataset is a large-scale, multi-view dataset with RGB, IR, Depth, and Skeleton modalities, featuring 100,000+ video sequences. It is captured from 106 subjects, three views, and 155 viewpoints. The data offers 96 illuminations and background variations, with videos averaging 3 seconds at 30 FPS. </p>|
| 2  | [PKU-MMD](https://www.icst.pku.edu.cn/struct/Projects/PKUMMD.html) | 51 | <p align="justify"> PKU-MMD consists of 1,076 long video sequences, performed by 66 subjects from three camera viewpoints. The data includes approximately 20,000 action sequences and a total of 5.4 million frames. Each video lasts around 3 to 4 minutes, recorded at 30 FPS. </p>|
| 3  | [InfAR](https://www.sciencedirect.com/science/article/pii/S0925231216307044) | 10 | <p align="justify"> InfAR consists of 600 short clips, each approximately 4 seconds long, recorded at 25 FPS with a resolution of 293 × 256 using IR thermal imaging cameras.</p> |
| 4  | [UCLA Multiview](https://wangjiangb.github.io/my_data.html) | 10 | <p align="justify">This dataset includes 1,475 RGB sequences captured simultaneously from three camera views, with each action performed by 10 different subjects. </p> |
| 5  | [TVSum](https://zenodo.org/records/4884870) | 10 | <p align="justify"> This dataset includes 50 videos sourced from YouTube, showcasing 10 different types of activities such as animal healthcare, dog shows, and various stunts. Each category has five videos, and a total of 20 users manually created ground truth (GT) summaries for these videos. The typical duration of videos in this dataset ranges from 1 to 5 minutes, with an average length of around 4 minutes and 18 seconds. </p>|
| 6  | [SumMe](https://zenodo.org/records/4884870) | -- | <p align="justify"> This dataset consists of 25 videos that depict a variety of activities including cooking, festivals, sports, and holidays, also obtained from YouTube. The videos vary in length from 1.5 to 6.5 minutes, with a mean duration of about 2 minutes and 40 seconds. Each video has 15 to 18 user-generated summaries that are utilized for training and evaluation. </p>|
| 7  | [UCF Crime](https://www.crcv.ucf.edu/data/UCF101.php) | 14 | <p align="justify"> The UCF-Crime dataset is a large-scale, untrimmed video collection consisting of 1,900 videos that total 128 hours. It includes one normal class and 13 types of real-world anomalies, both indoor and outdoor, captured against diverse, complex backgrounds. The dataset ensures a balanced distribution of normal and abnormal scenes across the training and testing subsets. Training videos only feature video-level labels, while temporal annotations are provided solely for the testing videos. </p>|
| 8  | [LAD-2000](https://arxiv.org/pdf/2106.08570) | 14 | <p align="justify"> The LAD-2000 dataset is a large-scale benchmark for video anomaly detection, consisting of 2,000 video sequences that cover 14 types of anomalies, including crashes, fires, and violence. It provides both video-level and frame-level labels. </p> |
| 9  | [CUHK Avenue](https://www.cse.cuhk.edu.hk/leojia/projects/detectabnormal/dataset.html) | 2 | <p align="justify"> This dataset consists of 37 videos at 640×360 resolution, split into 16 training and 21 testing videos. It includes abnormal activities like loitering, throwing, and running, each video lasting two minutes. The dataset provides pixel-level annotations across approximately 31,000 frames captured from a stationary camera. </p>|
| 10 | [ShanghaiTech](https://svip-lab.github.io/dataset/campus_dataset.html) | 2 | <p align="justify"> This dataset is a medium-sized benchmark for video anomaly detection (VAD), consisting of 437 surveillance video clips. It includes 330 training videos and 107 testing videos, capturing 13 types of anomalous scenes from various angles and lighting conditions. The dataset features 130 abnormal events, such as chasing, jumping, and motorbike activities. </p>|
| 11 | [RWF-2000](https://arxiv.org/pdf/1911.05913) | 2 | <p align="justify"> The RWF-2000 dataset is a large-scale collection of 2,000 video clips, each 5 seconds long, captured from surveillance cameras in real-world settings. These clips are evenly divided between violent and non-violent behaviors, facilitating the development and evaluation of violence detection algorithms.</p> |
| 12 | [UCF101](https://www.crcv.ucf.edu/data/UCF101.php) | 101 | <p align="justify"> UCF101 is a widely used dataset containing real-world human activity videos. It includes diverse activities across different categories, such as human-object interactions, human-human interactions, and sports. The videos are recorded at 320×240 resolution with a duration of approximately 2 to 10 seconds. </p>|
| 13 | [HMDB51](https://serre-lab.clps.brown.edu/resource/hmdb-a-large-human-motion-database/) | 51 | <p align="justify"> This dataset is collected from movies and online sources. It is developed for real-world action recognition tasks, with videos recorded at 320×240 resolution and clip durations ranging from approximately 2 to 13 seconds. </p> |
| 14 | [UCF50](https://www.crcv.ucf.edu/data/UCF50.php) | 50 | <p align="justify"> UCF50 consists of daily human activities collected from YouTube. It presents challenges such as cluttered backgrounds, complex camera motion, and varying viewpoints. The videos have a resolution of 320×240 with a clip duration of approximately 2 to 7 seconds.</p> |
| 15 | [YouTube Action](https://www.crcv.ucf.edu/data/UCF_YouTube_Action.php) | 11 | <p align="justify"> The YouTube Action dataset contains videos of human activities, primarily focusing on sports. The videos are in 320×240 resolution with a clip duration of approximately 2 to 10 seconds. </p> |
| 16 | [HRI30](https://zenodo.org/records/5833411) | 30 | <p align="justify"> This dataset focuses on human behaviors in industrial environments with a total of 2,940 video clips. The videos, recorded at 720×480 resolution, include complex human-robot interactions, workplace safety incidents, and other industrial activities. </p>|
| 17 | [Industrial Surveillance](https://github.com/FathUMinUllah3797/VD_ConvLSTM_GRU?tab=readme-ov-file) | 2 | <p align="justify"> This dataset consists of 300 videos, categorized into fight and no-fight. These videos, captured in 360×240 resolution, represent various scenarios from industrial surveillance environments. </p> |
| 18 | [Multiple Camera Fall](https://www.iro.umontreal.ca/~labimage/Dataset/) | 2 | <p align="justify"> This dataset contains a total of 192 videos that represent two classes, such as fall and daily activities. The original video stream is recorded in 720×480 dimensions with 30 frames per second. </p>|
| 19 | [UR Fall Detection](https://fenix.ur.edu.pl/mkepski/ds/uf.html) | 2 | <p align="justify"> The UR Fall Detection dataset consists of 192 videos, their video streams are recorded at a 720×480 resolution with 30 frames per second making it useful for fall detection. </p>|
| 20 | [DFAN](https://ieeexplore.ieee.org/abstract/document/9898909)  | 12 | <p align="justify"> DFAN is a small-scale, imbalanced, and diverse dataset comprising 3,804 images from 12 fire categories. The dataset is generated from YouTube, Facebook, and records videos of disaster management agencies. These videos were converted into frames with 40-60-frame skipping mechanism to increase the diversity of the extracted frames. The number of images per category is as follows: Boat fire (338), Building fire (305), Bus fire (400), Car fire (579), Cargo fire (207), Electric pole fire (300), Forest fire (480), Normal (97), Pick-up fire (257), SUV fire (240), Train fire (300), and Van fire (300).|
| 21 | [FD](https://ieeexplore.ieee.org/abstract/document/9171455) | 2 | <p align="justify"> This is a most widely used large-scale benchmark dataset, created by combining two existing datasets BoW-Fire and Foggia’s datasets. To further increase its volume, additional images were collected from various Internet sources. The final dataset comprises two classes such as fire and normal, each class consists of 25,000 images. |
| 22 | [BoWFire](https://www.kaggle.com/datasets/malligasenthil/bowfire/data) | 2 | <p align="justify"> It is an extremely small, imbalanced, and diverse dataset that consists of two classes such as fire and non-fire. The fire class contains 107 images, and the non-fire class consists of 119 images. |
| 23 | [FLAME](https://www.sciencedirect.com/science/article/pii/S1389128621001201) | 2 | <p align="justify"> The FLAME dataset was captured using various drones from different viewpoints, zoom levels, and camera types, including thermal and regular RGB cameras, to detect burning slash piles in Northern Arizona. The dataset was collected using three different cameras: the Zenmuse X4S, the Phantom 3 Camera, and the FLIR Vue Pro R thermal camera. The RGB modality, which is the most widely used for classification, consists of 39,375 frames for training and validation. The training set contains 80% of the data, while the remaining 20% is used for validation. Additionally, a separate testing set of 8,617 RGB images is organized in a dedicated folder. |
