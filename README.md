# capsule-deploy-ar

Role to deploy capsule server and configure it for use with satellite.

## Variables

```
pert_capsule_external_fqdn: "{{ groups['capsules'][0].split('.')[0] }}.{{ subdomain_base }}"
pert_capsule_internal_fqdn: capsule.example.com
pert_capsule_user_name: admin
pert_capsule_user_password: "{{ common_password }}"
```