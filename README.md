# geoguessr-classification
See blog post detailing the goal, data, approach, and model architecture [here](https://medium.com/@tef1/geoguessr-guesser-98e01efb5235).

## geoguessr-predictions.ipynb
  This notebook loads a saved version of the model and makes Top-5 predictions on specific images availabile. This was used to assess the performance of the model in non-quantitative ways. See the comments in the notebook for insights on model behavior.

## geoguessr-training.ipynb
  This notebook shows the training process for the most successful version of the model. The model configuration in this notebook was: 20% image size, 45% dropout rate, and early stopping patience of 3. 
