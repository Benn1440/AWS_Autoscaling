# AWS_Autoscaling

AWS Autoscaling monitors your applications and automatically adjusts capacity to maintain steady, predictable performance at the lowest possible cost.

AWS Autoscaling is free to use and it helps you optimize the costs of your AWS environment., it can help you optimize your utilization and cost efficiencies when consuming AWS services, so you only pay for the resources you actually need.

![EC2 Server](https://github.com/Benn1440/AWS_Autoscaling/assets/67696393/9fa90c45-ff9f-4e50-99c8-5b57aff8b86a)

When demand drops, AWS auto-scaling will automatically remove any excess resource capacity so that you avoid overspending.

Continually monitors your applications to make sure that they are operating at your desired performance levels. Using AWSAutoscaling, you maintain optimal application performance and availability, even when workloads are periodic, unpredictable, or continuously changing.

![create template](https://github.com/Benn1440/AWS_Autoscaling/assets/67696393/150fe430-9d9b-4c93-9b66-7dc8dde5ba5e)


You can capture the contents of an instance and its volume into an Amazon machine image(AMI) usually used for launching new instances with identical configurations.
Launch Templates are used to store launch parameters so that you do not have to specify them every time you launch an instance. I.e. AMI ID, Instance type, network settings, etc.


![LT hols info for net security](https://github.com/Benn1440/AWS_Autoscaling/assets/67696393/50c63417-9a8e-4351-9531-afccbed55aaa)


More than 5,000 launch templates per region can be created and 10,000 versions per launch template.

Using AWS Auto scaling you can build scaling plans that automate how groups of different resources respond to changes in demand.
You can optimize for balances between availability and costs. AWS Autoscaling automatically creates all of the scaling policies, and it sets targets for you based on your preference.

![Scaling Policy](https://github.com/Benn1440/AWS_Autoscaling/assets/67696393/b5550d94-e94c-48b7-989f-3953b086d5ed)

Amazon EC2 Auto scaling can determine the health status of an instance by using one or more of the following.

-	Status checks provided by Amazon EC2 to identify hardware and software issues that might impair an instance
-	Health checks provided by a load balancer, which can include custom health checks

![Autoscaling completed](https://github.com/Benn1440/AWS_Autoscaling/assets/67696393/accc7134-18d3-4ec3-87a4-4f8395d6d35d)

With target tracking scaling policies, you set a scaling metric(For instance, CPU utilization) and set a target value.
Amazon EC2 Auto scaling creates and manages the Amazon CloudWatch alarms that invoke the scaling policy. It calculates the scaling adjustments based on the metric and the target value.

![Launch Template](https://github.com/Benn1440/AWS_Autoscaling/assets/67696393/8fb509a4-f230-4bdb-9841-ab06d0ccffdf)

After you create a scaling policy, Amazon EC2 Auto scaling starts evaluating the policy against the metrics that were selected in the AMI.

Another awesome feature of Autoscale is its scheduling capability, allowing users to make their applications available at a desired time.

![Scheduled action](https://github.com/Benn1440/AWS_Autoscaling/assets/67696393/be134dc7-38da-4cae-9632-b491d2f4af01)

# Futher Reference on AWS Autoscaling

https://docs.aws.amazon.com/autoscaling/ec2/userguide/what-is-amazon-ec2-auto-scaling.html
