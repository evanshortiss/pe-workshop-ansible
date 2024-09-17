To run the playbook:

`ansible-playbook playbooks/ocp4_workload_platform_engineering_workshop.yml`

After the install, check _playbooks/user-info.yaml_ to obtain the password for
GitLab user `user1`. Use this when logging into Red Hat Developer Hub.

Remove workload:

`ansible-playbook playbooks/ocp4_workload_platform_engineering_workshop.yml -e ACTION=remove`

## Layer Customisations onto Developer Hub

Use the _app-config-rhdh.yaml_ file inside the _roles/ocp4_workload_platform_engineering_workshop_
to layer customisations such as custom branding onto the Red Hat Developer Hub
instance.