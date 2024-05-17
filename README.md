# abnormal_behaviour_detection

Hello! Welcome to my project titled **"abnormal_behaviour_detection"**. As the name suggests, it is a Image Classification task that detects abnormal behaviour of people. It is a multiclass classification task consisting of the classes normal, smoking and spitting.

## Dataset
The smoking and normal dataset were taken from kaggle. As the spitting dataset was not readily available, I collected the images from google and other sources and performed data augmentation over it.

## Training
I trained the model using 3 different base models namely MobileNetV2, EfficientNetB3 and DenseNet121. Densenet121 performed the best amongst the three and acheived an validation accuracy of about 99%. The python notebook can be found in the file named **"Abnormal-behaviour-densenet121.ipynb"**. The model architecture and weights after training could be found in the folder **"model_and_weights"** .

## Interface 
A gradio Interface for the same could be found at the notebook named **"Abnormal_behaviour_interface.ipynb""**.

## Conclusion
Overall it was a great learning experience for me. Throughout the project I learned various things like augmenting data, preventing overfitting, comparing models using various metrices,etc.

Thank you for looking at my work.
Have a nice day 😊.
