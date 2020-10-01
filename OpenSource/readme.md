Machine Learning is more interesting and fun when combined with applications like OpenCV and Tensorflow. However, there's not much info availablity on its installation along with the latest python version i.e. 3.8.3. Even with the help of internet resources, it brought lot errors for the lastest version of python. Hence below are the necessary steps for OpenCV installation.
Open the terminal and type the following commands:
1. brew cask anaconda
2. export PATH="/usr/local/anaconda3/bin:$PATH"
Now all the conda commands will work.
3.conda create --name ComputerVision python=3.8
4.pip install opencv-python
To activate:
5.source activate ComputerVision
6.jupyter notebook