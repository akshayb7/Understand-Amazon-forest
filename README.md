# Undersanding Amazon from Space

Every minute, the world loses an area of forest the size of 48 football fields. And deforestation in the Amazon Basin accounts for the largest share, contributing to reduced biodiversity, habitat loss, climate change, and other devastating effects. But better data about the location of deforestation and human encroachment on forests can help governments and local stakeholders respond more quickly and effectively.

To help with this, we will try to label satellite image chips with atmospheric conditions and various classes of land cover/land use. Resulting algorithms can help the global community better understand where, how, and why deforestation happens all over the world - and ultimately how to respond.

The data for this project has been taken from a Kaggle competition and can be found here: https://www.kaggle.com/c/planet-understanding-the-amazon-from-space#description

## Dependencies

1. Pytorch
2. Fastai v1
3. Kaggle.json file (for downloading data)

## Result

By only using a single CNN model, the submission from this notebook gives us an f2 score of 0.92741 in the Kaggle competition, which would have placed in the top 15% of the competition.
To improve this result, we can try creating an ensemble of CNN models and use them concurrently for predictions. (This will be implemented later)
