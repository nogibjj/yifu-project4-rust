# Cloud-based Big Data Project

- This project is going to build a CLI tool in data engineering that uses AWS Athena.
- I will use the dataset [Kaggle](https://www.kaggle.com/datasets/fedesoriano/traffic-prediction-dataset) to practice using SQL queries to analyze the data and build a model to predict the traffic volume with AWS Athena.

## Tasks

- Create an S3 bucket and upload the dataset to it. I would either use the AWS S3 console or the AWS CLI to do this.
- Create an Athena database and table to store the dataset (using the AWS Athena console or the AWS CLI). Specify the correct file format and schema for the dataset.
- Write SQL queries to analyze the data (in AWS Athena console or in a text editor). Test queries and make sure they produce the desired results.
- Run queries in AWS Athena and view the results (AWS Athena console or the AWS CLI). Save results to a file for further analysis or visualization.

## Dataset

- This dataset contains 48.1k (48120) observations of the number of vehicles each hour in four different junctions:
  1) DateTime
  2) Juction
  3) Vehicles
  4) ID


## References

- [rust-cli-template](https://github.com/kbknapp/rust-cli-template)
- [traffic-prediction-dataset](https://www.kaggle.com/datasets/fedesoriano/traffic-prediction-dataset)
