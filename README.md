<img src="https://i.imgur.com/Cb6DR9b.png">
# Chess: An analysis of 20.000 games
### by Germán Heim

Chess is a game between two opponents in which each one has 16 moving pieces placed on a board, divided into 64 squares. These squares are alternated in black and white colours, which constitute the 64 possible positions of the pieces for the game's development. Each player has sixteen pieces at the beginning of the game: a king, a queen, two bishops, two knights, two rooks, and eight pawns. The objective of the game is to "overthrow" the opponent's king.

The dataset used in this analysis takes more than 20.000 different games from the platform "[Lichess](http://lichess.org/)" (a free and open-source Internet chess platform run by a non-profit organization), using different time controls and by different rating ELOs.


### How to run the code

Use the following [*Jovian.ml hosted executable*](https://jovian.ai/germanheim/chess-an-analysis-of-100-games).
This is an executable [*Jupyter notebook*](https://jupyter.org) hosted on [Jovian.ml](https://www.jovian.ml), a platform for sharing data science projects. You can run and experiment with the code in a couple of ways: *using free online resources* or *on your own computer*.

#### Option 1: Running using free online resources

The easiest way to start executing this notebook is to click the "Run" button at the top of this page, and select "Run on Binder". This will run the notebook on [mybinder.org](https://mybinder.org), a free online service for running Jupyter notebooks. You can also select "Run on Colab" or "Run on Kaggle".


#### Option 2: Running on your computer locally

1. Install Conda by [following these instructions](https://conda.io/projects/conda/en/latest/user-guide/install/index.html). Add Conda binaries to your system `PATH`, so you can use the `conda` command on your terminal.

2. Create a Conda environment and install the required libraries by running these commands on the terminal:

```
conda create -n zerotopandas -y python=3.8 
conda activate zerotopandas
pip install jovian jupyter numpy pandas matplotlib seaborn opendatasets --upgrade
```

3. Press the "Clone" button above to copy the command for downloading the notebook, and run it on the terminal. This will create a new directory and download the notebook. The command will look something like this:

```
jovian clone notebook-owner/notebook-id
```



4. Enter the newly created directory using `cd directory-name` and start the Jupyter notebook.

```
jupyter notebook
```

You can now access Jupyter's web interface by clicking the link that shows up on the terminal or by visiting http://localhost:8888 on your browser. Click on the notebook file (it has a `.ipynb` extension) to open it.
