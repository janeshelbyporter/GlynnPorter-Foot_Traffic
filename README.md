# Optimization of Bike Taxi Pickup Locations in Downtown Charleston
Hi welcome to our GitHub! We researched the places with the highest foot traffic in downtown Charleston to find the best places for bike taxis to wait to pick people up. Here are a few steps to get started exploring our research.
  1. Download our data at this link. (We were limited by GitHub's file size requirements.)
  2. Download and run Data-Preprocessing.ipynb in Jupyter notebook. Make sure the csv files are saved in the same folder. If this step doesn't work for you, you can download weka-upload.csv. This is the file that the Data-Preprocessing code produces.
  3. After running the Pre-Processing file, now you need to convert it to ARFF. Go to https://ikuz.eu/csv2arff/. Upload weka-upload.csv, and click submit. Then check next to "First row contains labels." Then, click "Skip" next to the first variable, and make sure all the other variables are numerical. Before you click "Generate My ARFF," your page should look like this:
 <img width="673" alt="image" src="https://user-images.githubusercontent.com/78061469/165856836-382854c9-2ec1-40f6-85c4-c47bd3041114.png">
 If something goes wrong, the ARFF file is also uploaded to this page. You can download it and move to the next step.
  4. Next, open WEKA, and click "Explorer."
  5. Click 
