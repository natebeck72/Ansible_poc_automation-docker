# Ansible_poc_automation-docker
This is the Ansible configuration scripts for SASE POC's

These ansible scripts will configure the NGFW with a basic configuration and the NAT rules to allow traffic through.  Then it will put a base configuration into the panorama.

The config ansible playbook currently has the section for the wildcard cert we use in our POV's commented out, as some folks will not have access to those files.

The BestPractice ansible playbook is subjective and will include things that will/can be useful in a POV, it is NOT advertised as a current all encompassing best practice configuration.

After the Best Practice playbook, the SE will need to enable enhanced logging in the default logging profile and then they can commit the configuration.
