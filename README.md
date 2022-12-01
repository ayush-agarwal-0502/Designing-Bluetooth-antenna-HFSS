# Designing-Bluetooth-antenna-HFSS

Had a course on antennas and propogation in 5th semester of my college . Since it was purely mathematical and boring , decided to simulate an antenna myself so that I could have a real life understanding of the subject . So installed HFSS , learnt throught ansys course and simulated an antenna myself . 

Decided to make a dipole antenna , since it is omnidirectional and hence useful in a variety of cases . The antenna I have designed is meant for usage in Bluetooth communication . The frequency range of bluetooth communication is around 2.4Ghz . 

First I made the initial model without considering the fringing end effects . 

![image](https://user-images.githubusercontent.com/86561124/205044807-2e11ef5a-8048-45ea-a7ff-8419081045bc.png)
![image](https://user-images.githubusercontent.com/86561124/205044839-1afc4586-2648-4cc7-bda6-0283fe0b0a57.png)
![image](https://user-images.githubusercontent.com/86561124/205043636-4d9797f7-eb3d-4e13-8469-6201e5d5d98d.png)
![image](https://user-images.githubusercontent.com/86561124/205043652-f2394df5-c3ea-479d-ae5d-8db49e1fd04f.png)


As the effective length of dipole antenna would be more than the physical length , I tuned the antenna so that it works the best at the required range , as opposed to the result 2.3Ghz which I got without considering the end effects . I adjusted the length and after a few iterations of tuning , I was able to achieve the required goal . 

![image](https://user-images.githubusercontent.com/86561124/205044124-9730b8aa-85b3-43af-9c33-eaa87c028c90.png)


The properties of the model are as follows : 

![image](https://user-images.githubusercontent.com/86561124/205044378-289e1e73-b422-4899-b0f9-17bc133569be.png)
![image](https://user-images.githubusercontent.com/86561124/205044423-b52ffb0d-8890-4e2a-a769-faa9915a60a2.png)

Finally , I executed the simulation . After about a minute or two , my computer generated the results (yes , antenna simulations take time to run ) 

Here are the resulting field patterns :

![image](https://user-images.githubusercontent.com/86561124/205044730-d4b5c5a4-4a11-48d6-852b-ed0d902046dc.png)
![image](https://user-images.githubusercontent.com/86561124/205044740-46f826f7-6e45-4a4b-acc4-26f590ec60d7.png)
![image](https://user-images.githubusercontent.com/86561124/205044772-90891efa-a3b2-4a88-b3a5-a329a3f4c195.png)

Hence my aim was accomplished !! 


