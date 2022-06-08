# Metric Learning Homework

Please open the reports (part 1 and part 2) to read my results.

## Task Description

You are provided with Stanford Online Products dataset [DL]. It contains train (Ebay_train) and test (Ebay_test) sets. Train set should be divided into train and val.  

You need to choose a backbone [one] from torchvision.models and perform:  
* Build an index based on the training set and perform the retrieval of the val set using any library you want [faiss, annoy, etc].  
* Estimate Accuracy and mAP5 for both class and super_class for the val set.  
* Perform the retrieval for the test set. 
* For each class choose a 3-5 pictures and  generate visualizations similar to [slide]     


Repeat previous actions for:  
* Plain pre-trained ImageNet backbone  
* Fine-tuned with vanilla Cross-Entropy and classification approach  
* Fine-tuned using ArcFace Loss  
* Fine-tuned using the Siamese approach and Contrastive Loss  
* Fine-tuned using Triplet Loss   

You will need to choose augmentations to prevent overfitting and improve generalization. For fast experiments choose image size ~224…256 px and light backbone [like efficientnet_b0, resnet18 or similar].  
