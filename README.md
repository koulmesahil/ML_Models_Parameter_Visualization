# ML_Models_Parameter_Visualization
This Python code helps you understand how a machine learning model called Random Forest works on data that's like a fake version of real-world data. We split the data into two parts: one part to teach the model (training) and the other to see how well it learned (testing).

The main part of the code makes a picture called an ROC curve. It shows how good the model is at telling things apart. For example, in a medical test, it could show how good the test is at finding sick people without wrongly saying healthy people are sick.

The code also lets you play with two things:

Class Weight: It helps the model handle when there are more examples of one thing than another. For instance, if there are way more healthy people than sick ones in the data, the model might think everyone is healthy. So, we use class weight to help it understand that being sick is important too. Number of Trees (n_estimators): This is how many mini-models the Random Forest uses. More trees can make the model better but can also make it slower. The sliders you see let you change these things, and the plot updates to show you how these changes affect the ROC curve. It's like a playground where you can try different settings and see how they influence how well the model works.

In order to see the visulizations you will have to download and run the notebook locally,
![Data_Visualization_ML_Model_parameters ipynb-Colab-GoogleChrome2024-04-2118-14-17-ezgif com-video-to-gif-converter](https://github.com/koulmesahil/ML_Models_Parameter_Visualization/assets/63248279/382f14a3-c7e7-4b37-b1aa-4f59dfee1980)
![Data_Visualization_ML_Model_parameters ipynb-Colab-GoogleChrome2024-04-2118-13-22-ezgif com-video-to-gif-converter](https://github.com/koulmesahil/ML_Models_Parameter_Visualization/assets/63248279/edb917c0-d7ea-430c-a6b6-c5dbac51cadb)
![Data_Visualization_ML_Model_parameters ipynb-Colab-GoogleChrome2024-04-2118-15-04-ezgif com-video-to-gif-converter](https://github.com/koulmesahil/ML_Models_Parameter_Visualization/assets/63248279/54b5cf4b-ffdd-4bd4-8e1b-fb0c8d97d95d)
