# Dataset Description

**Kaggle data:** [Lab 2 - Feedforward Neural Network dataset](https://www.kaggle.com/competitions/lab-2-feedforward-neural-network/data)

The dataset contains samples of the function $y = x^2$. Use the training data
to fit a neural network and predict the target values for the test inputs.

The training inputs range from `-2` to `2`, while the test inputs range from
`-3` to `3`. Therefore, some test inputs fall outside the training range.

## Files

- `train.csv` - training dataset; `y` is the target value.
- `test.csv` - test dataset; predict the corresponding values of `y`.
- `sample_submission.csv` - sample submission in the required format.

## Columns

- `id` - unique row identifier.
- `x` - input value.
- `y` - target value in the training set, calculated as $x^2$.
- `y_pred` - predicted target value required in the submission file.

## Submission File

For each `id` in the test set, predict the corresponding value of $y$.

Required CSV format:

```csv
id,y_pred
0,0.0
1,0.0
2,0.0
```
