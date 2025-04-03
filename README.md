# IDS_IoT_Cameras
In this project, the goal is to create an IDS (intrusion detection system) specifically for IoT cameras. A model such as this, if implemented into IoT cameras in development, would help decrease the risk of breaches resulting in exposed camera feeds. A detection system such as this will greatly help consumers ensure their privacy. 

As it seems that BF attacks may be easier to detect than the other traffic types using traffic data, we create 2 separate models, where one runs before the second. The first will be a binary classification model that detects brute force attacks, and the second will be a multi-class detection model that determines traffic type if brute force is not present. As brute force attacks are of utmost concern (in the context of this project), we test a 2-model system where BF is prioritized against a one-model system that detects any traffic type to determine which is more accurate in correctly identifying intrusion. 

All code in this folder runs on the following libraries:

- Python 3.12.2
- pandas ≥ 2.2.2
- seaborn ≥ 0.13.2
- matplotlib ≥ 3.9.2
- scikit-learn ≥ 1.5.1
- numpy ≥ 1.26.4
- imblearn ≥ 0.13.0
- requests ≥ 2.32.3
- collections ≥
- scipy ≥ 1.15.2

If not already installed, any can be installed using the
!pip install <library> command in terminal. 

The code should be ran in order of 01, 02, ..., 07. The Jupiter notebook files will output all necessary data, however the finalized data is already included in the data folder and therefore any file could be run first instead of starting at 01. There as some commented portions to reduce runtime.  
