## Wine quality prediction using Amazon SageMaker Autopilot

This repository contains an example for performing prediction using Amazon SageMaker Autopilot. The notebook contains a complete walkthrough for performing the steps from SageMaker Autopilot, from pointing Autopilot to our tabular labeled data, to having a running inference endpoint.

### Overview

[Amazon SageMaker](https://aws.amazon.com/sagemaker/) is a fully managed service that provides every developer and data scientist with the ability to build, train and deploy machine learning (ML) models quickly. SageMaker Autopilot allows you to specify your own labeled data in tabular format in your S3 bucket, followed by specifying the output location in your S3 bucket. Autopilot will then perform all the steps in between, from data preparation, feature engineering, model generation, model tuning, and optional deployment, generating notebooks along the way to give you visibility into the steps it performed. All output is saved in the S3 location you specified. SageMaker Autopilot will generate multiple models using various algorithms and give you the option to select the model that is best suited for your use case. This model can then be deployed to a inference endpoint for real-time inference.

This example contains a Jupyter Notebook that demonstrates how to use a SageMaker Autopilot to predict the quality of wine found in Northern Portugal. The data set was obtained from the UCI Machine Learning repository (http://archive.ics.uci.edu/ml/datasets) and contains the physicochemical properties as inputs and sensory score as the output variables.

### Repository structure

This repository contains

* [A Jupyter Notebook](https://github.com/aws-samples/autopilot-portugal-wines/autopilot_wine_quality.ipynb) to invoke SageMaker Autopilot and create an optimal model for predicting wine quality in Northern Portugal.

## Security

See [CONTRIBUTING](CONTRIBUTING.md#security-issue-notifications) for more information.

## License

This library is licensed under the MIT-0 License. See the LICENSE file.
