Simply ,the cron job having the role to assume ,it assumes that role ,by using annotation ,because kube2iam is running 

so finally annoatation will pull kube2iam ds and will direct the arn in ec2 metadata , to arn mentioned in annotation 
in this kube2iam works 



Cronjob generally creates job at certain time and gracefully shutdown 

k delete ns --force --grace-period=0 ,means it shutdown immediately as we are in hurry 

