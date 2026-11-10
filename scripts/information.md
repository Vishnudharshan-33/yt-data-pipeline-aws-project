Bronze Bucket name - yt-datapipeline-bronze-us-east-1
Silver Bucket name - yt-datapipeline-silver-us-east-1
Gold Bucket name - yt-datapipeline-gold-us-east-1
Script Bucket name - yt-datapipeline-script-us-east-1

SNS ARN : arn:aws:sns:us-east-1:609356923240:yt-data-pipeline-alerts

Glue Bronze - yt-data-pipeline-bronze-db
Glue Silver - yt-data-pipeline-silver-db
Glue Gold - yt-data-pipeline-gold-db


    --bronze_database            — yt-data-pipeline-bronze-db
    --bronze_table               — raw_statistics
    --silver_bucket              — yt-datapipeline-silver-us-east-1
    --silver_database            — yt-data-pipeline-silver-db
    --silver_table               — clean_statistics
    --silver_path                — Silver S3 path prefix


--silver_database       — yt-data-pipeline-silver-db
--gold_bucket          — yt-datapipeline-gold-us-east-1
--gold_database        — yt-data-pipeline-gold-db