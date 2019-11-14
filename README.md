# ansible-poc

This is a small Ansible Playbook that deploys [Wiremock](http://wiremock.org/) to a Cloud Foundry space.

You can run it with
```bash
ansible-playbook deploy-wiremock.yml --extra-vars "org=hdc space=improvementws" --ask-vault-pass
```

I played around with basic things like variable aggreation, templates and Vault integration.

This is definitely not the best approach for what I want to achieve, next steps are to look into Ansible roles and modules.