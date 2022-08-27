# IDiffNet
### Usage:
1. Environment: I have tested this code with python3.7, tensorflow-gpu-1.15.4 
2. Run DiffNet: 
   1. Download the yelp data from this [link](https://drive.google.com/drive/folders/1hIkRDIVI87CUM4xFGjHMeipOlPz97ThX?usp=sharing), and unzip the directories in yelp data to the sub-directory named idiffnet of your local clone repository.
   2. cd the sub-directory idiffnet and execute the command `python entry.py --data_name=<data_name> --model_name=idiffnet --gpu=<gpu id>` 
3. If you have any available gpu device, you can specify the gpu id, or you can just ignore the gpu id. 

Following are the command examples:  
`python entry.py --data_name=yelp --model_name=idiffnet` 
