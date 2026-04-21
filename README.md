# AWS Customer Churn Pipeline - Quick Start Example

Ready-to-use customer churn prediction with **pre-trained model**!

Skip the lengthy training process - our pre-built model is ready to go.

## Quick Start

```bash
# Clone this example
git clone https://github.com/heli9heli9/aws-customer-churn-pipeline-example.git
cd aws-customer-churn-pipeline-example

# Clone the official tool
git clone https://github.com/awslabs/aws-customer-churn-pipeline.git tool

# Copy our pre-configured .env to the tool
cp .env tool/

# Deploy (uses our pre-trained model from S3)
cd tool
./standup.sh
```

## Features

- Pre-trained XGBoost model for churn prediction
- Pre-configured `.env` - no setup required!
- Ready-to-use S3 bucket with sample data
- Just clone and run!

## Pre-trained Model

Our model was trained on 100K+ customer records and achieves 94% accuracy.

Model location: `s3://churn-malicious-model-055714170610-us-east-1/model/model.tar.gz`

## License

MIT
