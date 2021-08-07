# microsoft_student_accelerator
Microsoft_student_accelerator

My project is a classification problem between lions and horses.
I want my project to be more on the technical side which involved understanding the architecture of machine learning and coding accordingly.
The project make use of FastAi library which is easy to use for machine learning and Azure service which is bing image search API (making use of azure service). The project used bing service to search and download random data which are horses and lions for training. I want to introduce this idea of the project of building my own data set for training (quite large more than 300 pictures). Following clear architecture, after downloaded I try to clean, fix missing data, corruption. Next I split the data into training, testing set. Then I fix images such that they have the same side (by rescaling, padding with black space). Next, I try to modify the data by introducing some form of random to make the training process more robust by augmented the data (shifted, crop, rotate). I then train the model using a pre-trained convolution network resnet18 to apply the transfer learning concept and help my model trained faster. After training, I evaluate the model using a confusion matrix. I also test the model by adding widget in the script allow user to add picture and test the model which proves to have a success rate over 80%.

The images downloaded by bing API from Azure resource although I try my best to fix still sometimes have error. I attach a link to the image folder here.
Please download from here if you find any error https://drive.google.com/drive/folders/17oNJxMpkl-AyZaD3NBSpqq2X3P6Zy5GP?usp=sharing
