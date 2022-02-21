# saponaws_cloudwatch_monitor_for_SAPhanaHA
monitor SAP HANA/Cluster status leverging Amazon EventBridge and CloudWatch custom metics, 
also set Amazon CloudWatch Alarm Notification to SNS
# Overview

# Architecture

![image](https://user-images.githubusercontent.com/13673388/154610281-bf9292f5-969a-4f97-83c0-2f7e97cf8c56.png)

# Requirements
1. the AWS Cli
2. SSM agent

# How to use
CloudFomration Template （in cloudformation folder）
Step1:
  upload cloudformation template to your S3 (ZHY or BJS)
Step2:
  excute hanamonitor.yaml with related parameters

AWS Cli scripts(in develop)

# Others
