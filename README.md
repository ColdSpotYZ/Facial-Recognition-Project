# Facial Recognition Project
##--NOT MAINTAINED--

How to use
---
## Step 1
```zsh
Install docker by following the instructions in 
```
[https://docs.docker.com/install](https://docs.docker.com/install)

## Step 2
```zsh
git clone https://github.com/ColdSpotYZ/Facial-Recognition-Project.git && cd Facial-Recognition-Project
```

## Step 3
```zsh
sudo docker build -t Facial-Recognition .
```

## Step 4 ( Do this once)
```zsh
sudo docker run --name facial-recognition -it Facial-Recognition 
```
### Note: subsequent startups should use
```zsh
sudo docker run facial-recognition
```
