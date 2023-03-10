# IMAGE COLORIZATION
Our goal for this project is to create a web application that allows users to colorize black and white photos different genres and black and white manga. The different selections of genres will correspond to different deep-learning models that have been separately trained with image data relating to each genre. We propose this method of image colorization to show that our approach of separating models by genres will lead to better and  more accurate results than some previous models that implement a model using all genres to train one model. 

## REPO STRUCTURE
- **app/big-data** holds the necesary files needed to run the app. To run the Image Colorization Tool on your local machine first make sure to first unzip the model .h5 files.
    To run : ```python3 main.py```

    > - Example images are also provided here
    > - Make sure to run the load_model notebook to produce models and add them to the app/big-data directory before running the app

- **models folder** : contains Jupyter notebook used for train models and performing evaluations. The models deployed in our application can be found in the links below:

    > landscape: https://drive.google.com/file/d/1-UTFSIhJJlHhdgbm90D0DUS5rgImsFMZ/view?usp=share_link
    > huamn: https://drive.google.com/file/d/1-GkGE6MjURQKKyfVHpo8TjFzXMeuZbLh/view?usp=share_link
    > objects/animals: https://drive.google.com/file/d/1-Fuz6JHb_oK4G4PQf1wU4Bi-q7wrd1L2/view?usp=share_link
    > manga: https://drive.google.com/file/d/1-3pAYhgSD1EUUStdZ_qqx1deEqvj7CCi/view?usp=share_link
