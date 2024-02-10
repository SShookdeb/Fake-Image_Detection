# For test this project you have to clone the project at first with command :
git clone https://github.com/SShookdeb/Fake-Image_Detection.git

Make a floder of that cloned directory named "Datascience"

mkdir Datascience

Inside the Datascience Directory make two another floder:
"Original", "Fake"

mkdir Original

mkdir Fake

After That you have to take minimum 1000 .JPG Image of your real face for Original Dataset
And for duplicate or fake image you have to take Image of your photograph, Id card photogrpagh, any types of duplicate photo you could. If you have issue with it check my Fake1.jpg, Fake2.jpg ....... Like this 

After that Put all original photograph on the "Original" Floder
And Put all duplicate folder on your "Fake" Floder

After done this open Anaconda jupyter notebook

After that go to the cloned file and open the "Fake_Image_Detection.ipynb" file on jupyter notebook 

After that create a cell on the top of all the cell and
install all requirement by this command on the first cell 

pip install numpy pandas matplotlib cv2 tensorflow sklearn itertools

After That click the kernal option and restart and run all the cell 

copy some original and duplicate image on your cloned current directory
At last predict your original and duplicate or image by entering the image file name inside the "prepare" function as an argument 

