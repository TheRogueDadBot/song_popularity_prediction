<h1>Machine Learning Application for Song Popularity</h1>
<h2>Quick-Start Guide for the Song Popularity Prediction Application</h2>

<p>This Quick-Start Guide is designed to help users install and operate the Song Popularity Prediction Application on a Windows 10 system. The application is developed on a macOS with an M1 chip, but the following instructions will ensure compatibility and ease of use on Windows-based systems.</p>

<h3>Prerequisites:</h3>
<ul>
    <li>Ensure Python 3.8 or higher is installed.</li>
    <li>Jupyter Notebook or Jupyter Lab should be installed to open .ipynb files.</li>
</ul>

<h3>Getting Started:</h3>
<ul>
    <li>Go to <a href="https://github.com/TheRogueDadBot/song_popularity_prediction.git">https://github.com/TheRogueDadBot/song_popularity_prediction.git</a></li>
    <li>Download the provided spotify_songs.csv data file</li>
    <li>Download song_popularity_prediction.ipynb file. ‘Raw’—>’Save as…’</li>
    <li>Save these files to a known directory on your computer.</li>
</ul>

<h3>Step 1: Install Required Libraries</h3>
<p>Open a command prompt or terminal window and run the following:</p>

- pip install pandas==2.1.3
- pip install numpy==1.26.2
- pip install matplotlib==3.8.2
- pip install seaborn==0.13.0
- pip install scikit-learn==1.3.2
- pip install ipywidgets==8.1.1

<h3>Step 2: Open the Jupyter Notebook</h3>
<ul>
    <li>In the same command prompt or terminal window, start Jupyter Notebook by running jupyter notebook or jupyter lab</li>
    <li>Navigate to and open the provided Jupyter Notebook file (e.g., song_popularity_prediction.ipynb).</li>
</ul>
<h3>Step 3: Update File Paths</h3>
<p>In the notebook, update the file path in the second cell for the CSV data to match where you saved them on your computer.</p>
<h3>Step 4: Run the Notebook</h3>
<ul>
    <li>Execute each cell in the notebook by clicking 'Run' or pressing Shift+Enter.</li>
    <li>Or Run —> Run All Cells</li>
    <li>The notebook will display visualizations and allow you to interact with the predictive model and the recommendation system.</li>
</ul>
<h3>Using the Recommendation System:</h3>
<ul>
    <li>Choose a genre from the dropdown menu to display the top 5 recommended songs in that genre.</li>
    <li>Click the "Recommend Popular Songs" button to see the recommendations.</li>
</ul>
<h3>Using the Prediction Model:</h3>
<ul>
    <li>Input song features into the provided text boxes or use the default values for a quick test.</li>
    <li>Click the "Predict Song Popularity" button to see the predicted popularity score for the input features.</li>
</ul>
<h3>Visualizations:</h3>
<p>Scroll through the notebook to view the provided visualizations, including the correlation matrix, distribution of track popularity, and pair plots.</p>
<h3>Step 5: Save Your Work</h3>
<p>Save any changes you make to the notebook to ensure you can revisit your session later.</p>
<h3>Troubleshooting:</h3>
<ul>
    <li>If visualizations or interactive elements do not display, ensure all cells have been run and that the notebook is trusted (an option in the Jupyter interface).</li>
    <li>For issues with libraries or dependencies, verify that you have an internet connection and that all requirements have been installed correctly.</li>
</ul>
<h3>Final Steps:</h3>
<p>Explore the notebook to understand how the application predicts song popularity and provides song recommendations. Use the application to inform playlist decisions and enhance listener engagement with data-driven insights.</p>
