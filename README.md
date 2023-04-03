# Data_Bias
# Testing Bias in the Perspective API

This project aims to test for potential biases in the Perspective API, a natural language processing model released by Google Jigsaw. The Perspective API is designed to identify toxic language in internet comments, but its accuracy and potential biases have been called into question.

## Data Exploration

In this project, I analyzed a dataset of internet comments and their toxicity scores, and determined a threshold for the model based on the distribution of toxicity scores in the training set. We then used the Perspective API to score the toxicity of a test set of comments, and compared the scores to various hypotheses about the model's performance.

## Hypotheses Testing

We tested several hypotheses that Perspective will be less likely to mark comments without dirty words as toxic.

Based on my testing, I found that the Perspective API is less likely to mark comments without dirty words as toxic. However, my results may not generalize to other datasets or contexts.

## Conclusion

My testing has raised important questions about the potential for bias in machine learning models and the importance of careful evaluation and testing. It is essential that I continue to study and address biases in machine learning models in order to create more fair and inclusive models.

## Dependencies

- pandas
- googleapiclient
- langdetect
- tqdm
- Python 3.8 or later

## Usage

To run the code, first clone the repository:  

git clone `https://github.com/VannieCC/Data_Bias.git`

Then install the dependencies: 

```
pip install pandas google-api-python-client langdetect tqdm
```

Finally, run the `Perspective_APl.ipynb` notebook using Jupyter.

## License

This project is licensed under the MIT License - see the LICENSE.md file for details.
