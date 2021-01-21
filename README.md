# Face_Mask_Detector
Data set used : https://github.com/prajnasb/observations.git    (Prajna Bhandary)
Video link :  https://youtu.be/rCs0jaYHz30   (see with subtitles On)

Model used: MobileNet pre-trained on ImageNet   ----> transfer learning and fine tuning ----> 2 neurons at the output layer as we have two classes [mask, non_mask]


About contents of this Repository: 
1. Face_mask_detection_train.ipynb      : file created for Model Building and Train, Model was saved as model.h5 in drive
2. Face_mask_detection_test.ipynb       : testing of images with the trained model (model.h5)
3. model.h5                             : trained model 
4. haarcascade_frontalface_default.xml  : we use haarcascade for detection of frontal face. The detected ROI is fed to the model to detect whether mask is there or not 
