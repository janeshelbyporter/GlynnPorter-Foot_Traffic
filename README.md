###### Optimization of Bike Taxi Pickup Locations in Downtown Charleston
Hi welcome to our GitHub! We researched the places with the highest foot traffic in downtown Charleston to find the best places for bike taxis to wait to pick people up. Here are a few steps to get started exploring our research.
  1. Download our data at this link. (We were limited by GitHub's file size requirements.)
  2. Download and run Data-Preprocessing.ipynb in Jupyter notebook. Make sure the csv files are saved in the same folder. If this step doesn't work for you, you can download weka-upload.csv. This is the file that the Data-Preprocessing code produces.
  3. After running the Pre-Processing file, now you need to convert it to ARFF. Go to https://ikuz.eu/csv2arff/. Upload weka-upload.csv, and click submit. Then check next to "First row contains labels." Then, click "Skip" next to the first variable, and make sure all the other variables are numerical. Before you click "Generate My ARFF," your page should look like this: <img width="673" alt="image" src="https://user-images.githubusercontent.com/78061469/165856836-382854c9-2ec1-40f6-85c4-c47bd3041114.png">
If something goes wrong, the ARFF file is also uploaded to this page. You can download it and move to the next step.
  5. Next, open WEKA, and click "Explorer."
  6. Then, click "Open File," and choose weka-upload.arff.
<img width="1019" alt="image" src="https://user-images.githubusercontent.com/78061469/165857167-7f2e142e-891b-4e1d-a243-e44a26bc4b4c.png">
  7. After it loads, go to "Cluster." 
  8. Then, click "Choose," and then "SimpleKMeans"
<img width="1016" alt="image" src="https://user-images.githubusercontent.com/78061469/165857291-c770150c-7b62-4e6d-89a7-f5fe0d4e69ed.png">
  9. Then, click "Choose," and then "SimpleKMeans"
  10. You can double-click "SimpleKMeans" at the top and change the number of clusters. We found that 5 was the best number of clusters.
<img width="603" alt="image" src="https://user-images.githubusercontent.com/78061469/165857506-70791f1a-3c5d-46dd-92a2-83311c3413f4.png">
  11. Make sure to change your cluster mode from "Use full training set" to "Percentage split" and set it equal to 66%.
  12. Then, click start, and it should output your results!
  13. If you would like to run our models 

