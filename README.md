# Cloud-based Big Data Project

- This project is going to use AWS S3 and AWS Sagemaker to do machine learning model code part. All analysis are done within an AWS Sagemaker notebook.
- I will use the dataset [traffic](https://www.kaggle.com/datasets/fedesoriano/traffic-prediction-dataset) to do the project.

## Tasks

- Create an S3 bucket and upload the dataset to it. I would either use the AWS S3 console or the AWS CLI to do this.
- Use AWS S3 to store our data and use AWS Sagemaker to do Machine Learning.
- Build a model to predict the traffic volume with AWS S3 and AWS Sagemaker.
- Fit the model to the data and evaluate the model.

## Dataset

- This dataset contains 48.1k (48120) observations of the number of vehicles each hour in four different junctions:
  1) DateTime
  2) Juction
  3) Vehicles
  4) ID
- Before analyzing the data, I would use Rust to preprocess and clean the data.

## Code Overflow

1. import important module   
2. import data file. 
3. data anlysis   
4. data cleaning   
5. build model and do evaluation

## Steps

1. create a bucket on AWS S3
2. upload data
3. create a notebook instance in AWS Sagemaker
4. create a IAM role for sagemaker AWS
5. create a notebook
6. Coding


## References

- [rust-cli-template](https://github.com/kbknapp/rust-cli-template)
- [traffic-prediction-dataset](https://www.kaggle.com/datasets/fedesoriano/traffic-prediction-dataset)
