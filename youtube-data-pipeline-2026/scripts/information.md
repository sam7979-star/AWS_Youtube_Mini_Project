Bronze Bucket Name - yt-data-pipeline-bronze-eu-london-1-dev 
Silver Bucket Name - yt-data-pipeline-silver-eu-london-1-dev 
Gold Bucket Name - yt-data-pipeline-gold-eu-london-1-dev 
Script Bucket -yt-data-pipeline-script-eu-london-1-dev

SNS ARN -
arn:aws:sns:eu-west-2:218852528943:yt-data-pipeline-alerts-dev:dbbcdd1b-55e5-4eb1-bc9f-9d9e2e33890c
glue bronze_DB- yt_pipeline_bronze_dev
glue Silver_DB  yt_pipeline_silver_dev
glue gold_DB    yt_pipeline_gold_dev

--bronze_database   :       yt_pipeline_bronze_dev
--bronze_table      :       raw_statistics
--silver_buket      :       yt-data-pipeline-silver-eu-london-1-dev
--silver_database   :       yt_pipeline_silver_dev
--silver_table      :       clean_statistics
--gold-bucket       :       yt-data-pipeline-gold-eu-london-1-dev
--gold_database     :       yt_pipeline_gold_dev
                            yt-data-pipeline-gold-eu-london-1-dev