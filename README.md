# Facial Recognition Project

How to use
---
## Step 1
```zsh
Install docker by following the instructions in <a href="https://docs.docker.com/install/"> https://docs.docker.com/install/ </a>
```
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
sudo docker run --name Facial-Recognition -it Facial-Recognition 
```
### Note: subsequent startups should use
```zsh
sudo docker run Facial-Recognition
```
