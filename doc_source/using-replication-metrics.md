# Using Replication Metrics to Monitor Amazon S3 Replcation Configurations<a name="using-replication-metrics"></a>

Each replication rule that has S3 Replication Time Control \(S3 RTC\) enabled will publish replication metrics\. With replication metrics, you can monitor the total number and size of objects that are pending replication, and the maximum replication time to the destination Region\. You can then monitor each data set that you replicate separately\. 

Replication metrics are available within 15 minutes of enabling S3 RTC\. Replication metrics are available through [AWS Management Console](https://console.aws.amazon.com/s3/), the [Amazon Simple Storage Service API Reference](https://docs.aws.amazon.com/AmazonS3/latest/API/), the [AWS SDK](https://docs.aws.amazon.com/AmazonS3/latest/dev/UsingAWSSDK.html), the [AWS Command Line Interface \(AWS CLI\)](https://docs.aws.amazon.com/cli/latest/reference/), and the [Amazon CloudWatch User Guide](https://docs.aws.amazon.com/AmazonCloudWatch/latest/DeveloperGuide/)\. For more information, see [Monitoring Metrics with Amazon CloudWatch](cloudwatch-monitoring.md)\. 