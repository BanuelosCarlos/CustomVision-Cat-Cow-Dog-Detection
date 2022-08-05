# Azure Custom Vision Dog-Cat-Cow recognition model evidence
We will train a model to recognize between cows, dogs and cata.\
Let us go to customvision.ai, we acces with our account with an Azure subscription and in Projects we create a new project, with name, description and resource.
![Images](Images/1.png)\
\
For this we will need to create a select a resource, in this case we create one, with name, the Azure subscription, a resource group, kind of service, the location and the pricing.

![Images](Images/2.png)\
\
I used this configuration for this model.

![Images](Images/3.png)\
\
Now we wil need to load the images, especifying the tag of each group of animal, and a group of pictures that are the control.

![Images](Images/4.png)\
\
My image set looks like this.

![Images](Images/5.png)\
\
It is time to train the model, and it starts to train with the data set that we have loaded.

![Images](Images/6.png)\
\
Once the training is done the following panel will be shown to us.

![Images](Images/7.png)\
\
And the model is ready to predict with new inputs.
![Images](Images/8.png)\
\
For a dog.
![Images](Images/9.png)\
\
For a cat.

![Images](Images/10.png)\
\And finally for a cow,
![Images](Images/11.png)