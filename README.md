# AWS Cloud Formation Template for EC2 start stop
ec2_start_stop.cft



# AWS_Lambda
AWS Lambda for EC2 and RDS start-stop using AWS tagging method and cron function as a trigger.

Cron Function To trigger AWS Lambda using CloudWatch Event

Start: cron(15,30 4 ? * MON-FRI *)

Stop: cron(30,45 16 ? * MON-FRI *)

