# Pupil and blink detection algorithms for near-eye device applications
To obtain the pupil center of the human eye in infrared images taken by a near-eye device for gaze tracking, pupil and blink detection algorithms are proposed. The eye-detection model and the eye feature point model are trained through the dlib library machine learning, the eye area is segmented, rough positioning of the eye area is realized, the redundant image information is removed, the number of image processing calculations are removed for the subsequent pupil positioning, and the processing time is shortened. In pupil detection, the candidate pupil contours are screened based on the gray information, shape characteristics and other pupil image information to obtain the correct pupil contour information and realize precise pupil positioning. The eye feature model is used to obtain the coordinate of the feature point of the eye, the aspect ratio of the eye is obtained by conversion, and blink statistics are performed. Experiments show that the correct rate of the pupil detection method reaches 97.24%, and the correct rate of blink detection reaches 91.59%.
## System Requirements
We develop the Windows version of `simple pupil` using 64 bit Windows 10.
## 7-Zip
Install 7-zip to extract files.
## Python
you will need a 64 bit version of Python 3.8. If you install any other version, make sure to install the 64 bit version!
## Install Python Libraries
we recommend using a virtual environment for running `simple pupil`. To install all Python dependencies, you can use the `requirements.txt` file from the root of the simple pupil repository.
## Model
`detector4.svm` `predictor4.dat`
## Software
`pupil.exe`
## 说明
model file 和软件放在同一路径下，软件即可正常使用。
导入拍摄的人眼视频文件xxx.mp4、用户信息文件name.txt,通过pupil.exe进行瞳孔检测拟合，得到相应数据文件。

## Result
获得测试者瞳孔拟合（包含眨眼次数）的视频文件、瞳孔中心位置，瞳孔直径数据文件。
