# Border-security-surveillance-using-Drone
AI model for Border security surveillance using Drone

unfortunately i didn't found any dataset for this project so i manually download all images that is in border area captured by drone or images from aerial view, having objects like person, tent, weapons, vehicles and manually labelled it using online tool makesense.ai.

Train object detection algorithm (YOLOv5) on this dataset and its giving a good results. Model able to detect object from within 150 meter high images/video.
Due to work with small hardware with drone i just train a small model weights..

# Results from Trained model:
you can see in results that model is predicting very far object preety well..
![media_images_Validation_100_3](https://user-images.githubusercontent.com/65647192/160339874-6a1468dd-8b86-422a-b641-bd9b21dccda7.jpg)
![media_images_Validation_100_5](https://user-images.githubusercontent.com/65647192/160339886-3d4fbfea-d0fe-4f69-8dc0-02ab648bb4ae.jpg)

# Future Enhancement:

Collect more images and will train model for better hardware devices..

# Note 
Pre-trained weights are confidential feel free to reach out for industrial use or any other purpose.

