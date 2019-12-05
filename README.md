# aws_chat_analysis
Analyzing chat data in AWS


Downloaded chat data from the Ubuntu Dialog Corpus

--Removed folder column from csv

--Removed data, from and to columns

--Kept id and text

--Deleted existing ID and replaced with serial ID

--Trimmed data down to 50 rows

--Uploaded CSV to s3
--Created a topic modelling job in AWS Comprehend that writes to an s3 bucket


