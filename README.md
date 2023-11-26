# LOG/RAW DATA -> S3 -> LAMBDA FUNCTION -> DYNAMODB
Upload data to s3, trigger lambda function, process the csv, and insert data to dynamoDB
Architecture diagram:
![Screenshot (9)](https://github.com/arnav-snowleo/aws_s3/assets/68443456/ef95c278-b50f-4989-982d-deceb2473a59)

Upload CSV file to tS3 bucket:
![Screenshot (8)](https://github.com/arnav-snowleo/aws_s3/assets/68443456/2e844507-6035-4e73-b578-3665a64556f3)

Lambda Method Code in Python:
![Screenshot (7)](https://github.com/arnav-snowleo/aws_s3/assets/68443456/f77c1195-4ffe-452f-b68a-6cc65abac3cd)

Data inserted into DynamoDB:
![Screenshot (6)](https://github.com/arnav-snowleo/aws_s3/assets/68443456/1d251012-1d37-4719-b226-5d0e601282df)

CloudWatch Logs:
![Screenshot (5)](https://github.com/arnav-snowleo/aws_s3/assets/68443456/250f9a12-9894-403a-9022-3b8ab3c957dc)

