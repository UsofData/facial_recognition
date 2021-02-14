# facial_recognition
comparing 2 images to see if they belong to the same perosn

# Summary

I performed multiple different methods to solve the problem and outlined them into 3 files:

face_check_ContrastiveLoss: The first trial that involves Siamese Networks and Contrastive Loss Function.
face_check_triplets: The Second trial that involves using the Triplet Loss Function and arranging the data differently to accommodate for that. 
face_check_BCELOSS: The third and only successful file that involves Siamese Network and getting the absolute difference between the 2 Siamese Network and returning one output to be used for BCELOSS Function.

The only method I managed to actually train properly and avoid underfitting is the face_check_BCELOSS.
So, if you're short on time, I suggest just seeing this file alone.

At the end of the last file file, I have outlined a list of references I have used, as well as a list of other methods that can be done to solve this task.

# Required libraries

- Pandas
- Matplotlib
- Pytorch
- Hyperopt
