# ELB Presence

Registers the EC2 host to an ELB on start. Deregisters on stop. Forked from
CoreOS and changed to use the python3 base image.

## Environmental Variables

* `AWS_REGION` = Region the load balancer is in
* `ELB_NAME` = Name of the load balancer
