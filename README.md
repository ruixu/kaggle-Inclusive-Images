# kaggle Inclusive Images

## Download data
- Download data from AWS S3 storage with awscli: 
    ```
    aws s3 --no-sign-request sync s3://open-images-dataset/train train/ > /dev/null &
    aws s3 --no-sign-request sync s3://open-images-dataset/validation validation/ > /dev/null &
    aws s3 --no-sign-request sync s3://open-images-dataset/test test/ > /dev/null &
    ```