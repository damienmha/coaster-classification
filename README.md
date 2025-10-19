# Roller Coaster Classification

As a frequent visitor of theme parks and amusement parks and a thrill seeker, I am a bit of a roller coaster enthusiast. I found roller coaster data online and became curious about what insights could be learned about a roller coaster through some of its basic statistics. 

Based on the data in one file, I attempted to train multiple classificantion algorithms and a neural network to idenitfy roller coasters by type (steel, wood, or hybrid) based on the characteristics in the data. I will continue trying to improve this, though there are some issues with class imbalance. There may also not be enough variables that can accurately contribute to predicting this

I am therefore looking at a second csv file in some of the data I found to attempt the same task. It has more variables that could be useful, but it is much messier and required a long data cleaning process. I have now finished cleaning it and am training classification models and a deep learning model on it. The track materials in this data were listed as steel, wood and "other" rather than having a hybrid category. Maybe the "other" coasters are not strictly hybrid, so I have kept it listed under the "other" label
