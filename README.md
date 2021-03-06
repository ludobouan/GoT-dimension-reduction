# GoT-dimension-reduction

Submission to Siraj Raval's competition ["Visualize a Game of Thrones Dataset"](https://www.youtube.com/watch?v=yQsOFWqpjkE
)

> The challenge for this video is to visualize [this](https://www.kaggle.com/mylesoneill/game-of-thrones) Game of Thrones dataset. Use T-SNE to lower the dimensionality of the data  and plot it using matplotlib. In your README, write our 2-3 sentences of something you discovered about the data after   visualizing it. This will be great practice in understanding why dimensionality reduction is so important and analyzing data  visually.

## Conclusions  
### Battle Outcome
![alt tag](https://github.com/ludobouan/GoT-dimension-reduction/blob/master/images/battles.png)  
With this format it is easy to see that battles with the same outcome have the similar parameters, although our sample size is small and we did not use dummy variables.  
The outcome of our target battle with unknown outcome is most likley WIN.
### Popularity
![alt tag](https://github.com/ludobouan/GoT-dimension-reduction/blob/master/images/popularity.png)  
The scatter plot shows us that characters with similar popularity have similar data values. The data is clearly a good indicator of the popularity of a character.
### Character Houses
![alt tag](https://github.com/ludobouan/GoT-dimension-reduction/blob/master/images/house.png)  
With the available data it is hard to infer a characters House. The character data in this dataset is not a good indicator of the House. (Full legend in the Notebook)

## Usage
Download the files and run the Jupyter Notebooks

## Dependencies
- Numpy
- Matplotlib
- Scikit-Learn

## Credits
Datasets : [link](https://www.kaggle.com/mylesoneill/game-of-thrones)  
Based on Siraj Ravel's introduction to using T-SNE with scikit-learn : [link](https://www.youtube.com/watch?v=yQsOFWqpjkE)

## License
[MIT License](https://github.com/Blabby/GoT-dimension-reduction/blob/master/LICENSE)
