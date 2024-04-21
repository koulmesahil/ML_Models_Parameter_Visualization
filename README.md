# ML_Models_Parameter_Visualization
This Python code helps you understand how a machine learning model called Random Forest works on data that's like a fake version of real-world data. We split the data into two parts: one part to teach the model (training) and the other to see how well it learned (testing).

The main part of the code makes a picture called an ROC curve. It shows how good the model is at telling things apart. For example, in a medical test, it could show how good the test is at finding sick people without wrongly saying healthy people are sick.

The code also lets you play with two things:

Class Weight: It helps the model handle when there are more examples of one thing than another. For instance, if there are way more healthy people than sick ones in the data, the model might think everyone is healthy. So, we use class weight to help it understand that being sick is important too. Number of Trees (n_estimators): This is how many mini-models the Random Forest uses. More trees can make the model better but can also make it slower. The sliders you see let you change these things, and the plot updates to show you how these changes affect the ROC curve. It's like a playground where you can try different settings and see how they influence how well the model works.
