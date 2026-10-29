# ec2-scheduler-app

Python 3.12 Lambda code for the EC2 Scheduler project.

Stops or starts EC2 instances tagged Schedule=office-hours and sends a report to SNS. The action (stop or start) comes in the event input.

The infrastructure (Terraform) lives in the repo ec2-scheduler-infra.
