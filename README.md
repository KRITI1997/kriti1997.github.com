
# Machine Learning , Data Enthusiast

[Why Should You Hire Me?](https://drive.google.com/file/d/1jp45oV3JsH69dmSe3bnLWUzYTkCYaeqD/view?usp=drive_link)

## 💻 Technical Skills
- **Software and Programming** | C++, Python, Java, MATLAB, R, OpenCV, TensorFlow, PyTorch, NumPy, Matplotlib, Scikit, Pandas
- **Databases and Operating System** | MySQL, Linux, Windows, AWS
- **Hardware** | Jetson Nano, Raspberry Pi, Nordic Development kit

## 🎓 Education
- **Master of Science, Electrical Engineering** <br>
_North Carolina State University (Aug 2022 - May 2024)_
- **Bachelor of Technology, Electronics and Communication Engineering** <br>
_Shiv Nadar University (Aug 2015 - May 2019)_

## Publications
Singh Kriti and P. C. Jain. "Traffic control enhancement with video camera images using AI." Optical and Wireless Technologies: Proceedings of OWT 2019. Springer Singapore, 2020.

Kriti Singh et al."Sweet Potato Yield Prediction Using Machine Learning Based on Multispectral Images Acquired from Small Unmanned Aerial Vehicle” Digital Agriculture Journal, MDPI, 2024. [Accepted]



## Work Experience
**Computer Vision @ Osrostrum Inc. (_July 2024 - Present_)**
- Processed 3D pointclouds to create heightmaps for training data and trained a MobileNet-v2 for classification task.
- Optimized a rendering pipeline by focusing on triangulation of landmark points and enhancing the projection matrices for robust 3D reconstruction.
- Trained and finetuned Mobilenet-v2 for keypoint annotation in pointcloud.


**System Design/Architecture Intern @ Tesla (_Feb 2024 - May 2024_)**
- Processed machine sensor data by querying, aggregating and analyzing the data to create an end-to-end ML pipeline.
- Compared state-of-the-art architectures including CNN and Transformer based models along with classical ML approaches to
detect anomalous machine behavior for predictive maintenance of HVAC systems contributing to energy optimization efforts at Gigafactory Nevada.
- Deployed validated model through Apache Airflow seamlessly integrating it with Kubernetes for scalable production deployment.


**AI Research Intern @ US Department of Agriculture (_May 2023 - August 2023_)**
- Analyzed remote sensing agriculture data over a sweet potato field through ANOVA test, Pearson Correlation and PCA analysis.
- Investigated and developed an ensemble model using XGBoost and Random Forest for yield prediction modeling based on
extracted features obtaining a R-square of 0.89.
- Developed a web application using Flask for rapid model evaluation reducing testing time by 25%.
- Evaluated the importance of different vegetation indices calculated from the multisprectal data in prediction modeling of yield and the relationship between different nitrogen and cover crop treatments.
  
**Project Assistant, Active Robotic Sensing Laboratory @ NCSU (_Jan 2023 - Present_)**
- Investigated photogrammetric methods such as Structure from Motion for 3D reconstruction from 2D crop images.
- Implemented and performed comparative analysis of several NeRF based deep learning pipelines on custom dataset.
- Analysed the 3D point clouds generated from COLMAP to ascertain views and directions with incorrect estimated camera parameters to guide data acquisition for better reconstruction.
- Implemented BayesNeRF for uncertainity quantification in reconstruction.

**Computer Vision Intern @ Omnipresent Robot Technologies (_Feb 2022 - May 2022_)**
- Led a ground penetration radar project for underground pipeline detection.
- Implemented spatial and linear transformation on images for parabola detection achieving test accuracy of 90%.
- Collaborated with frontend UI team for integration of algorithm with a web application.
- Analyzed Change Detection algorithms and implemented DASNet algorithm on satellite imagery data achieving a 95% accuracy.

**Research Assistant, ZEN Lab @ Indian Institute of Science (_July 2019 - May 2020_)**
- Developed a wagon tracking algorithm using Bluetooth Low Energy technology.
- Implemented RF acoustic localization to form a relay network of Bluetooth nodes and enable data transfer between nodes.

## Projects
### Acute Otitis Media Detection (Computer Vision)

Collaborated with medical practitioners to collect and label ear membrane data. Preprocessed the images and used augmentation techniques for improving the training data.Demonstrated a 70% accuracy by implementing **RCNN**, **Fast RCNN** and **Faster RCNN** algorithms in MATLAB.


![Image labelling in MATLAB](/assets/img/image_labelling.png)


![RCNN Detection Results](/assets/img/rcnn_detection.png)


### Conditional Variational Autoencoder on CelebA Dataset (Deep Learning)

Implemented and trained a CVAE in PyTorch for image manipulation and morphing with an acceptable MSE reconstruction loss.Developed and trained a CVAE to encode and manipulate images in CelebA database. CelebA dataset contains more than 200K celebrity images, each with 40 binary face attributes annotations (like Male, Smiling, eye glasses etc.). Each image has its own face attributes annotation, which is encoded as a 40- dimensional binary vector: 0 means that the image does not show the corresponding attribute, 1 means that it does.Once the model was trained we used the previously trained CVAE to manipulate an image by changing the attribute vector input to the encoded image.Generative models have the ability to interpolate real samples to generate non- existent manipulated samples. The interpolation simply consists in performing linear algebra in the latent space learned by the generative model.


![Manipulated faces with sunglasses](/assets/img/beard_man.png)


![Interpolated results for morphing](/assets/img/nterpolation.png)

### Terrain Identification from Time Series Data

The main aim of the project was develop a model that could predict the terrain on which a person is walking, using only data from gyroscope and accelerometers.The features were xyz coordinates from accelerometer and gyroscope. The labels were (0) standing or walking in solid ground, (1) going down the stairs, (2) going up the stairs, and (3)  walking on grass. There was a difference between sampling frequency of features and the labels.Processed the datapoints as vectors to handle the frequency mismatch.Handled class imbalance through SMOTE and trained 1D-CNN, LSTM and an ensemble network with ensemble network performaing the best in terms of f1 score, precision and recall.

### Deepfake Detection (Deep Learning)

Extracted frames from the CelebDF dataset videos for dataset and  evaluated performance of Xception Network on the curated dataset optimizing the architecture to improve validation accuracy.Generated embeddings using FaceNet by using MTCNN for cropping and isolating the faces from the image frames and implemented triplet loss in PyTorch to improve the deepfake detection accuracy.

[poster.pdf](https://github.com/user-attachments/files/16809242/poster.pdf)
![Poster of the project](/assets/img/poster.png)

### Image Blending using Laplacian Pyramid (Image Processing)

Programmed gaussian and laplacian pyramid for image blending based on a binary mask provided by the user through a GUI
created for selecting a ROI on image using roipoly library in python.Tuned the parameters of gaussian kernel for smooth blending between two images.
![Blending results](/assets/img/gaussian_blending.png)





