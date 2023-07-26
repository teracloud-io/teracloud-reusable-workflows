# teracloud-reusable-workflows

This repo contains reusable workflows from Teracloud LLC

-------------------------------------------------------------------------------------

## Sync_to_s3.yaml

This is a YAML file that serves as a configuration for syncing data to an S3 bucket. It contains the following input variables:

### Input Variables

- `inputs.AWS_REGION`: The AWS region where the S3 bucket is located.
- `inputs.LOCAL_PREFIX`: The local prefix or path of the data to be synced.
- `inputs.BUCKET_NAME`: The name of the S3 bucket where the data will be synced.
- `inputs.BUCKET_PREFIX`: The prefix or path inside the S3 bucket where the data will be stored.
