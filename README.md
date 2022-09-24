# EmotionPrediction

1. All the codes are *.ipynb jupyter notebook files and they have been run in the Google Colab environment 
with GPU hardware accelerator. 

Because of that, to run the codes, you have to change the all paths in the first box written as;
	
	data = pd.read_csv('drive/MyDrive/ravdes/***.csv') -> 
	data = pd.read_csv('dataset/***.csv')

in which all related ***.csv files are provided in the dataset directory. All CSV files are obtained separately 

2. There are 6 different *.ipynb files, 2 for EMODB, 2 for EMOVO, and 2 for RAVDES. 
RAVDES is the first dataset and used initially. However for males, the file is overwritten for now, 
and it is created again and rerun from scratch again since the first one is not at hand. 
There is a slight difference with the preview file for males.

3. Datasets are in the DB folder. All the codes are given for each dataset 