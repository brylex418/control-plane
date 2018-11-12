# control-plane
Control-plane stuff

1. Create your terraform.tvars file
```
env_id             = ""
short_env_id       = ""
access_key         = ""
secret_key         = ""
region             = "us-gov-west-1"
availability_zones = ["us-gov-west-1a", "us-gov-west-1b", "us-gov-west-1c"]
ops_manager_ami    = "ami-0a073a805412627b2"
dns_suffix         = ""
rds_instance_count = 0
vpc_cidr           = "10.0.0.0/16"
ssl_cert_arn       = ""
tags               = {
    Team = "abryant"
    Project = "GovCloud Deploy"
```

2. init

3. plan

4 apply
