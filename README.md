# Fraud Detection Using AWS Sagemaker

## Dataset
The dataset is publicaly available which was collected and analyzed during a research collaboration of Worldline and the Machine Learning Group of Université Libre de Bruxelles on big data mining and fraud detection. The dataset consists of anonymized credit card transactions over a two-day period in 2013 by European cardholders. In order to preserve the anonymity of the users, all features have been transformed using Principal Component Analysis (PCA), resulting in a dataset with 28 continuous PCA features, and two more features representing time and amount. Because the dataset is derived from real data, the distribution of fraud is low compared to legitimate transactions. Fraudulent transactions make up 0.172% of the total transactions. 

## Template
If you download this template it will automatically launch the solution and all associated components. The default configuration deploys an Amazon API Gateway, an AWS Lambda function, an Amazon SageMaker notebook instance, an Amazon Kinesis Data Firehose delivery stream, and Amazon Simple Storage Service (Amazon S3) buckets, but you can also customize the template based on your specific needs.
