###
- Deploys Conjur HA cluster with 2 standby and 1 leader
- Policy branching for Vault Synchronizer and regarding resources can be created via synchronizer_policy.yml
- Conjur CLI operations are insecure
- Conjur CLI should be installed on master
- Check parameters in vars/conjur_vms.yml
- Seccomp and 3rds party certificate installation can be configured also in vars/conjur_vms.yml
- Tested in Rocky Linux 8.6
