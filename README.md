# Indoor-Scene-Recognition-with-Visual-Attributes

Instructions 

Setup required packages 

```pip3 install -r requirements.txt```
   
in the root directory of the project 

Attribute Network

1. Download SUN Dataset with attributes
   Download Images: http://cs.brown.edu/~gmpatter/Attributes/SUNAttributeDB_Images.tar.gz and unzip it
   and place the folder  in directory as Attribute_Network. 
   Download Attribute Dataset: http://cs.brown.edu/~gmpatter/Attributes/SUNAttributeDB.tar.gz and unzip it 
   and place folder in the directory as "Scene Detector Network"
   
2. Run the Attribute Network Training script by running 

   ``` python3 main.py ```
   
3. Upon training , the trained model is stored as model.pth in the Attribute Network directory which predicts
   visual attributes for training the Indoor Scene Recognition Network
   
   
Scene Recognition Network

1. Download MIT Indoor 67 dataset and place train and test folder in the scene Detector Network
   directory.
   
2. Run the scene detector training scripts by running

   ```python3 main.py```

3. After completion of training , the model is stored in the Scene detector network directory as 
   model.pth
