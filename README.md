# Music categorization project (APS360)

The project aims at training a model for music categorization. It will accept a music track given in input and will return the category of the music (pop, rock, ...) among the ones the model learnt.

Below is the list of all categories taken into account in this project:

- blues
- classical
- country
- disco
- hiphop
- jazz
- metal
- pop
- reggae
- rock

## Set up

Whether you want to use the notebooks or the python files, you need to resolve all dependencies. You can install them either in your virtual environment or Python base environment with the following command: `pip install -r requirements.txt`. 

If you want to use notebooks defined in this repository, you can upload them on *Google Collab* or you can run a Jupyter notebook server locally. You can install Jupyter by following [the official documentation](https://docs.jupyter.org/en/latest/install/notebook-classic.html).

## Dataset used

We used GTzan dataset for this project as a base. You can download it [here](https://www.kaggle.com/datasets/andradaolteanu/gtzan-dataset-music-genre-classification). Then, we proceed to data processing. You can find the related notebook in `data_processing/`.

You can find the processed data by following this [link](https://drive.google.com/drive/folders/1Yid03FGzQOmdcSoYuXXJsaHBIshL9Zvl).