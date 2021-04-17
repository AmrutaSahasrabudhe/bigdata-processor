# BigData
Big data is a field that treats ways to analyze, systematically extract information from, or otherwise deal with data sets that are too large or complex to be dealt with by traditional data-processing application software

## 
To debug issues on bigdata server we can use the resource manager to get ID information. Based upon ID we can get more details on the processing of job. If a job status remains as ACCEPTED and does not move ahead there could be multiple reasons for it. The common issue is that all the assigned vcores are already usedup by other processes. If job status is PROCESSING it means the process is running. If status is FINISHED it means the process has completed. Another issue could be there is not enough memory. All these parameters can be validated using resource manager. Bad query will demand more vcores. 
