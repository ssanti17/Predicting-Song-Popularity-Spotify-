# Predicting Song Popularity Using Spotify Data

__Project by Sarah Santiago, Shishi Feng, Simran Regmi, Winnie Lu for IEOR 142__

---

### Brief instructions on how to run our code included in the final submission zip file:


As mentioned in our paper our objective is to clean the spotify data on kaggle and build a model that predicts the song popularity using the features specific to a song.  If you are interested in replicating the data processing that we conducted to arrive at our final dataset csv in the zip file, please open the original Kaggle dataset online [here](http://tiny.cc/b5gut) to download the `tracks.csv`. Then save the csv in the same directory and run code bracket 1-17 of file `data_processing_lda.ipynb`. This will give you the final dataset that we used for all of our subsequent model building, named `spotify_final.csv.zip`.
If you rather not redo this data processing, then feel free to run any of the model ipynb documents using the `spotify_final.csv` after you unzip it.



In most cases in each individual model construction, we used the name spotify to refer to the `spotify_final.csv`. 
In order to make sure that the data are correct. Before running the code that trains the model, open a new cell, enter and run:
`spotify = pd.read_csv(‘spotify_final.csv’)`


The three folders `Data`, `Data Processing and Model Building`, and `Pdfs` have our data, models, and pdf versions of our notebooks. In the latter two folders, you will find the a total of four ipynb or pdf files containing the models that we used (namely, LDA, logistics regression, CART, random forest, etc).
