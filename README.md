# ML Tool

A simple tool for machine learning requirements.

## Modes

### `generate-data`: Create a Train / Test Split

We pass to it a csv file that will be split according to a ratio.

Example: We split it to 80% training and 20% testing data.

Required Parameters:
* `ratio`: Percentage to split
* `input-file`: Input csv
* `output-train-file`: Output training set
* `output-test-file`: Output test set