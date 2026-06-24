Bronze Bucket Name - yt-trending-adi-bronze 
Silver Bucket Name - yt-trending-adi-silver 
Gold Bucket Name - yt-trending-adi-gold

Script Bucket - yt-trending-adi-script

SNS ARN - arn:aws:sns:ap-south-1:974842793619:yt-data-pipeline-alerts-dev:fb8f2a45-83ad-4b7e-9661-bdaf6920ccfe

Glue Bronze - yt-pipeline-bronze-dev 
Glue Silver - yt-pipeline-silver-dev 
Glue Gold - yt-pipeline-gold-dev

--bronze_database - yt-pipeline-bronze-dev 
--bronze_table - raw_statistics 
--silver_bucket - yt-trending-adi-silver  
--silver_database - yt-pipeline-silver-dev 
--silver_table - clean_statistics

--silver_database - yt-pipeline-silver-dev
--gold_bucket - yt-trending-adi-gold 
--gold_database - yt-pipeline-gold-dev