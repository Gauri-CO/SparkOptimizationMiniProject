# SparkOptimizationMiniProject

As part of Spark Optmimzation project there are below twp main parts of the query to be optimised:

1. Group by
2. Join 

For GroupBy there is HashMergeAggregate operator in the Physical Plan.
Join operator is Broadcast join since one of the dataset is small.

![image](https://user-images.githubusercontent.com/75573079/128239742-be6d1173-b300-414d-9b35-2c73449b7032.png)


As part of optimization.
partition the answer data by 'month' and bucket by 'question_id'
