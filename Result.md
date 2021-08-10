Result:
After training, the model is able to detect lion and horse 
Reflection:
There are many to take into account when training model:
1/ Preprocessing - As I use the bing image search to download lots of images, I notice that there error in the data (image is unreadable, missing data, uncorrected size, format) 
and these error prevent the code from running. This makes cleaning the data very important (delete error, fill in mixing data, fix, crop and pad data to make others). Corrupted data 
could also be misleading the training process
2/ technique to improve training - I find that by augmented the data (croping padding rotating fix focus) the model is relatively better. I also notice not to overtrain as this will
lead to overfitting the data (only work well with training data set). Augmenting the data helps a bit in preventing overfitting
3/ Using pre-train model like resnet18 produce better and faster result applying transfer learning
