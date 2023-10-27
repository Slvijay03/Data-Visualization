# weather_visualization

**Description**
     
     Simple visualization of dataset using python libraries (such as seaborn, pandas, etc..)

**NOTE**
     
     *Take a glance of what the functions are really mean before starting your plot*

Datasets of different kinds can be found at Kaggle...**https://www.kaggle.com/datasets**

Case 1:
 
 Following are some of the functions used to represent the weather dataset:

  1. displot - Used to visualize **continous dataset**. Only one column can be executed at a time.
  2. jointplot(bivariate function) - Helps to visualize 2 column data in a single plot.
  3. stripplot - It is used to visualize the distribution of categorical data.It uses scatter plot.
               // if your data on plot is too messy you can use the command --> **jitter = True**
  4. boxplot - It is useful for colorful representation of 2 columns at a time.
  5. countplot - It is used in case of visualizing the **discrete dataset**. 


Case 2:

 Following are some of the functions used to represent the mental health dataset:

  1. scatterplot - Uses dot to represent data from a dataset.For representation you can use the code
                **plt.scatter(df['ABC'],df['DEF'])**
  2. comparision using scatterplot - 2 different data from dataset can be compared.
  3. histogram - You can visualize using the code **plt.histplot(df['xyz'])**


