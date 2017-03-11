Scene Recognition Using Bag of Words

included files:

· RGB2Lab.m - coverts RGB image to Lab

· batchToVisualWords.m - runs getVisualWords on every image in data set

· buildRecognitionSystem.m - creates histograms of visual words for training set

· createFilterBank.m - generates set of filters

· dictionaryHarris.mat - dictionary of visual words using Harris Corner points

· dictionaryRandom.mat - dictionary of visual words using random points

· evaluateRecognitionSystem_NN.m - runs classification and generates accuracy percentage using nearest neighbors

· evaluateRecognitionSystem_kNN.m - runs classification and generates accuracy percentage using k nearest neighbors, with k values ranging from 1 to 40

· extractFilterResponses.m - gets all filter responses for an image using generated set of filters

· getDictionary.m  - generates dictionaryHarris.mat and dictionaryRandom.mat

· getHarrisPoints.m - uses Harris corner detection to select key points from image

· getImageDistance.m - gets distance between two visual word histograms

· getImageFeatures.m - creates visual word histogram for image

· getRandomPoints.m - selects random points from image

· getVisualWords.m - maps each pixel in an image to its closest word in the dictionary

· visionHarris.mat - classification data for harris points

· visionRandom.mat - classificaton data for random points

Training data available in traintest.mat
