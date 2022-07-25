# CGV_Project_Compus_view
//Download this apt to run in ubuntu
sudo apt-get update
sudo apt-get install freeglut3
sudo apt-get install freeglut3-dev
sudo apt-get install binutils-gold
sudo apt-get install g++ cmake
sudo apt-get install libglew-dev
sudo apt-get install g++
sudo apt-get install mesa-common-dev
sudo apt-get install build-essential
sudo apt-get install libglew-dev libglm-dev

//To compile and display the project for c++ file 
g++ campus.cpp -lglut -lGL -lGLEW -lGLU -o campus 
