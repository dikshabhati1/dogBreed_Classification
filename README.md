# dogBreed_Classification
# Goal
The goal is to classify images into 120 categroies of dog breed.
# Data
Their are 14399 dog images in train dataset and 1681 dog images in train datset.Also their is one label csv.
I had taken this datset from dockship website.Here is the link to download the dataset:!wget -O "dog_breed_classification_ai_challenge-dataset.zip" "https://dockship-job-models.s3.ap-south-1.amazonaws.com/5d1d683b041da2669eed8b591fba65ac?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAIDOPTEUZ2LEOQEGQ%2F20200919%2Fap-south-1%2Fs3%2Faws4_request&X-Amz-Date=20200919T100832Z&X-Amz-Expires=1800&X-Amz-Signature=c9233a3bd1f2e2283a61991a92255a3bbd77e04cf00b1a2847ec41f6f7e5fcdb&X-Amz-SignedHeaders=host&response-content-disposition=attachment%3B%20filename%3D%22dog_breed_classification_ai_challenge-dataset.zip%22". 
# Accuracy
I got loss: 1.9650 ,accuracy: 0.8313 ,val_loss: 5.2307 ,val_accuracy: 0.7486 when i used InceptionV3.<br>
And when i used InceptionResNetV2 I got loss: 1.3932 ,accuracy: 0.6262 ,val_loss: 0.6798 ,val_accuracy: 0.8281
