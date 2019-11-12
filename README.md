# Anomaly Detection

## Algorithms in Machine Learning, ISAE-SUPAERO

This repository contains course materials for my Machine Learning class on the topic of Anomaly Detection:
- <em>anomaly_detection_class.pdf</em> : course presentation with teaching content
- <em>anomaly_detection_class.ipynb</em> : Python notebook illustrating the course notions
- <em>anomaly_detection_class-empty.ipynb</em> : same Python notebook to follow with students during class

An application exercise is also available:
- <em>anomaly_detection_exercise.pdf</em> : instructions for the exercise
- <em>data/dataset.csv</em> : the dataset to be used to answer the questions

### Setting up Anaconda environment

To setup the Anaconda environment with required dependencies, execute the following instructions in Anaconda prompt or Linux shell.

```shell
# Clone this github repository on your machine
git clone https://github.com/jfabrice/ml-class-anomaly-detection.git

# Change working directory inside the repo
cd ml-class-anomaly-detection

# Create a new virtual environment
conda create -n anomalydetectionenv python==3.7

# Activate the environment
## For Linux
source activate anomalydetectionenv
## For Windows
activate anomalydetectionenv

# Install the requirements
pip install -r requirements.txt
```
