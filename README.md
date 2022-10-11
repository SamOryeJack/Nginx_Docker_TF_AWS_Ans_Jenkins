# Nginx_Docker_TF_AWS_Ans_Jenkins

Build using Nginx, Docker, Terraform, AWS, Ansible and Jenkins

Assumptions:

1.  The available free version of Linux
2.  The latest available version of NGINX for Linux
3.  EC2 instance size is t2.micro (free tier)
4.  Must create and use free tier of private AWS account
5.  The SSL certificate is self-signed
6.  The AWS Security Group is default

Acceptance Criteria:

1.  Post-provisioning report demonstrates evidence of
    a. No provisioning errors
    b. Sequence of provisioning steps
    c. Up and running instance of NGINX
    d. Listening on ports 80 and 443
    e. Response on ports 80 and 443
    f. content of active instance configuration file

2.  Run automated pipeline 3 times in a row and receive the same result (fully remove provisioned EC2 with components after every deployment, automation is optional for removal)
