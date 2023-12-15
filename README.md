# final project
used skimage.hog function to apply Histogram of Oriented Gradient (HOG) feature descriptor to dataset image

(reshaped X dataset's size to 2-d array to compute the HOG descriptor) 

also, to get standard normally distributed data, used sklean.preprocessing.StandardScaler function

for the algorithm I chose Support Vector Machine(SVM) which is commonly used model along with hog descripter in object classification problem

for hyperparameters, I used sklearn.model_selection.GridSearchCV function to find best hyperparameters for SVM scoring 'accuracy'

(It seemed like it would take a long time, so I commented out the grid search part)
