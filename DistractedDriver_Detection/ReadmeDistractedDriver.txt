# Download Data from here : https://www.dropbox.com/s/0vyzjcqsdl6cqi2/state-farm-distracted-driver-detection.zip?dl=0
1. You need to classify images into these 10 classes 
•	c0: safe driving
•	c1: texting - right
•	c2: talking on the phone - right
•	c3: texting - left
•	c4: talking on the phone - left
•	c5: operating the radio
•	c6: drinking
•	c7: reaching behind
•	c8: hair and makeup
•	c9: talking to passenger


I am using SGD optimizer rather than Adam optimizer because the SGD optimizer gave better descent gradually, while the ADAM optimizer showed erratic pattern of descent.


SF_DistractedDriverDetect_Mobilenet-SGD- No extra layers.ipynb : Used MobileNet architecture without adding extra layers. The accuracy is approx. 88.6 % . So I gave preference to this Model. 

SF_DistractedDriverDetect_Mobilenet-SGD-Extra layers.ipynb: Used MobileNet architecture by adding some extra layers. The accuracy is approx. 86.39 %. The mobileNet model without extra layers gave better accuracy.


mobilenet_sgd_nolayers.hdf5 :  weights for the mobilenet without layers

mobilenet_sgd_withlayers.hdf5 : weights for the mobilenet with layers