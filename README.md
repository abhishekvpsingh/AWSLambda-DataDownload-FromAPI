# AWSLambda-DataDownload-FromAPI



Set the following Environment Variables to run from local system

BUCKET_NAME=abhi-itv
ENVIRON=DEV
FILE_PREFIX=sandbox
BASELINE_FILE=2022-01-03-20.json.gz
BOOKMARK_FILE=bookmark

Also comment out the global upload_res , return global_res variable in DEV environ.




Set the following Environment Variables to run from Lambda Function

BUCKET_NAME=abhi-itv 
FILE_PREFIX=sandbox 
BASELINE_FILE=2022-01-03-20.json.gz 
BOOKMARK_FILE=bookmark 
