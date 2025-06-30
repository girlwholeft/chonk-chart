# chonk-chart
A model to predict a cat's position on the chonk chart.

This model uses a cat’s weight, breed, and sex to determine its place on this chonk chart. The chonk chart determines how fat or “chonk” a cat is. It is a densely connected neural network trained from ~400 example cats. You can use the model to make predictions by adjusting the weight with a value between 2 and 9 and changing the boolean values for breed and gender. Note that only one breed and one gender can be labeled as true. 

Use pip install -r requirements.txt to download requirements. Ensure all files are in the same directory. 

Run chonk-cats-model.ipynb to get the .h5 file. Then, you can play with chonk-model-test.ipynb.
