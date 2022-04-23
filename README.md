# EmotionDetectionOmSanan

For a video demo, visit https://www.youtube.com/watch?v=-S2aZQ04EFk

First, download the FER2013 dataset from Kaggle.
https://www.kaggle.com/datasets/deadskull7/fer2013

Then unzip the Training_Images.zip and upload the folder to drive (this will take time),

****Note - Make sure to use the code and model from the updated code folder.****

They open emotion_detection.py for the code - the link for the Colab notebook is:
https://colab.research.google.com/drive/1Dpfp4e1J4V4yZxHPTRvspYks3GS38fjg

If any of the modules are not installed, use the pip install <module> command.

If you want, access the fModel.h5 in the repository using the load model function located after the model training. You will need to add it to the sketch first. It is only trained with 25 epochs so it won't be acurate. I used a more accurate one that was able to get better accuracy. Read the update below.

****Update**** - I uploaded a new version of the code (Emotion_Detection_Updated.py) and a new accurate model called finalModel.h5. For an accurate version, use the new code and model. If you want to train on your own, 200 epochs will take a bit longer than 2 hours. Each epoch takes 45 seconds with Google Colab Pro. 

The you can upload the testing folder or images in your drive if you want to use the testing images I used. Otherwise, use the X_Test images.

***Note*** - If you want your model to train much faster, get Colab Pro or use a different software.

*Also, this doesn't have much to do with the Jetson Nano since I was having some issues with it, so you can feel free to run it on your Mac/PC with just a working webcam.*