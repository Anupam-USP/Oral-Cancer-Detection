# Oral-Cancer-Detection
This project focusses on detecting oral cancer(carcinoma) in the tongue region. It will be extended to predict the multiple classes of cancer and covering of the whole mouth cavity too.
![image](https://user-images.githubusercontent.com/98142436/162369512-22cd338d-8db3-42f0-8b8d-2fe277fabe33.png)

## Our Proposed Work ->
![image](https://user-images.githubusercontent.com/98142436/162369597-894dab69-8135-4763-9f58-208fbeb954a8.png)

## Cancerous Image:
![image](https://user-images.githubusercontent.com/98142436/162369852-cd922fb2-6b9c-47ca-860b-702b0c3a2222.png)
Non Cancerous Image(collected from friends and neighbors):
![image](https://user-images.githubusercontent.com/98142436/162369923-f1091850-57ca-416f-9fcb-52ca20d7a305.png)

## Pipeline for the Project->
![image](https://user-images.githubusercontent.com/98142436/162369992-2c007814-e17d-4753-9bbf-12a308c38db3.png)

## Preprocessing ->
![image](https://user-images.githubusercontent.com/98142436/162370198-92505943-a73b-4910-ab17-9bc00c8fb738.png)

## VGG Architecture used for Classification-> 
![image](https://user-images.githubusercontent.com/98142436/162370234-83444604-1125-41d0-8e5a-348dea2654bb.png)

## Survey of around 88 custom and inbuilt models were being used along with custom optimizers were being used ->
Few with accepable perfomances are shown.
![image](https://user-images.githubusercontent.com/98142436/162370615-e8ec2db2-de88-40a9-8dd2-d8094fdc81f6.png)

## Performance of DenseNet-201 ->
This model had better conventional training than VGG which will be used in future purposes
![image](https://user-images.githubusercontent.com/98142436/162370705-5d97a6a8-ad82-4bd0-87d1-b80b12ca9a60.png)

## Ensembling Pipeline->
The Deep Learning Model was combined with 3 Machine Learning Algorithms->
1. AdaBoost
2. Random Forest
3. Kernel Support Vector Machine
![image](https://user-images.githubusercontent.com/98142436/162370958-d6c226c7-0cad-4755-97ae-354fc85d4c86.png)

## App Screenshots built to be used to predict cancer->
![image](https://user-images.githubusercontent.com/98142436/162371053-77cbf2fb-c9ca-44e5-86b2-c5e8f256d6ce.png)


## To update `environment.yml` file
`conda activate Oral`

`conda env export > environment.yml`
