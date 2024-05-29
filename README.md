# cloudnotes
Reference notes for Cloud education and certifications

S3 file storage types, Glue transformation times, and Athena query statistics.

Apache Iceberg and Parquet are the fastest to access using Athena and provide the smallest 
data storage size to keep S3 costs low. The compression available in these formats is 
the most efficient.

Athena charges are based on volume of data queried and the run time of the query.
Use the best compression paired with the fastest Athena query performance to achieve the 
lowest charges for Amazon Athena.

The worker type, the number of workers employed, and the job's run time determine the 
Glue service charges. Short run times with smaller worker types are optimal.
Find the balance between worker size and run time to achieve a cost-optimal solution. 
Track job results by time, worker size, worker count, and cost to empirically find 
the most efficient configuration.



