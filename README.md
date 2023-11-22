Quick-Start Guide for the Song Popularity Prediction Application

	This Quick-Start Guide is designed to help users install and operate the Song Popularity Prediction Application on a Windows 10 system. The application is developed on a macOS with an M1 chip, but the following instructions will ensure compatibility and ease of use on Windows-based systems.


Prerequisites:

Ensure Python 3.8 or higher is installed.  

Jupyter Notebook or Jupyter Lab should be installed to open .ipynb files.


Getting Started:

Go to https://github.com/TheRogueDadBot/song_popularity_prediction.git

Download the provided spotify_songs.csv data file 

Download song_popularity_prediction.ipynb file. ‘Raw’—>’Save as…’

Save thes files to a known directory on your computer.


Step 1: Install Required Libraries
Open a command prompt or terminal window and run the following

pip install pandas==2.1.3

pip install numpy==1.26.2

pip install matplotlib==3.8.2

pip install seaborn==0.13.0

pip install scikit-learn==1.3.2

pip install ipywidgets==8.1.1


Step 2: Open the Jupyter Notebook

In the same command prompt or terminal window, start Jupyter Notebook by running jupyter notebook or jupyter lab

Navigate to and open the provided Jupyter Notebook file (e.g., song_popularity_prediction.ipynb).


Step 3: Update File Paths

In the notebook, update the file path in the second cell for the CSV data to match where you saved them on your computer.  


Step 4: Run the Notebook

Execute each cell in the notebook by clicking 'Run' or pressing Shift+Enter.

Or Run —> Run All Cells

The notebook will display visualizations and allow you to interact with the predictive model and the recommendation system.


Using the Recommendation System:

Choose a genre from the dropdown menu to display the top 5 recommended songs in that genre.

Click the "Recommend Popular Songs" button to see the recommendations.


Using the Prediction Model:

Input song features into the provided text boxes or use the default values for a quick test.

Click the "Predict Song Popularity" button to see the predicted popularity score for the input features.


Visualizations:

Scroll through the notebook to view the provided visualizations, including the correlation matrix, distribution of track popularity, and pair plots.


Step 5: Save Your Work

Save any changes you make to the notebook to ensure you can revisit your session later.


Troubleshooting:

If visualizations or interactive elements do not display, ensure all cells have been run and that the notebook is trusted (an option in the Jupyter interface).

For issues with libraries or dependencies, verify that you have an internet connection and that all requirements have been installed correctly.


Final Steps:

Explore the notebook to understand how the application predicts song popularity and provides song recommendations.

Use the application to inform playlist decisions and enhance listener engagement with data-driven insights.
