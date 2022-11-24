For Problem 1, I used the xlrd package. I tested the notebook on Colab and it works fine. However, it gave me some problem with the version of the package, so I updated them with the following commands:

!pip install --upgrade xlrd
!pip install --upgrade pandas

After this, I restarted the kernel and everything worked out.

For Problems 2 and 3, I imported the csv files as:

train_data = pd.read_csv("content/drive/MyDrive/Data_train.csv")
test_data = pd.read_csv("content/drive/MyDrive/Data_test.csv")

For some reason, Colab could not load the files so I used the following lines.

#train_data = pd.read_csv("/content/drive/MyDrive/Data_train.csv") #for Colab
#train_test = pd.read_csv("/content/drive/MyDrive/Data_test.csv") #for Colab

If Colab gives a problem when importing the set, uncommenting the above lines should do the job. 
