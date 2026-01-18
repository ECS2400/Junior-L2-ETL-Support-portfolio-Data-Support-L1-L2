# Real-Life Examples of My Work

## Example 1 – Failed ETL Job
**Issue:** A scheduled QualityStage job failed in production.  

**Actions Taken:**
- Reviewed job logs in QualityStage  
- Identified a database connection timeout  
- Verified database availability on Linux  
- Restarted the job after the connection was restored  

## Example 2 – Missing Input File
**Issue:** ETL job could not find a required input file.  

**Actions Taken:**
- Checked file location on Linux server  
- Verified file permissions  
- Coordinated with the upstream team to re-deliver the file  
- Re-ran the job successfully  

## Example 3 – System Performance Issue
**Issue:** ETL job was running significantly slower than usual.  

**Actions Taken:**
- Checked CPU and memory usage on the server  
- Notified infrastructure team about resource constraints  
- Monitored job progress after performance improvement  

## Example 4 – Data Mismatch Between Source and Target

**Issue:** Business reported that some records were missing in the reporting layer.

**Actions Taken:**
- Queried source and target tables using SQL  
- Compared record counts and key fields using JOINs  
- Identified missing records caused by a failed ETL run  
- Re-triggered the affected QualityStage job after validation  


--THANK YOU FOR READING ALL OF THIS :) 
