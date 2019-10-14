## PULFA

Installs and deploys the latest stable release of the Princeton University Library Finding Aids (PULFA) application

### Requirements

_To be drafted_

### Role Variables

_To be drafted_

### Dependencies

_To be drafted_

Please download the preconfigured eXistdb installation used for the PULFA from [https://raw.githubusercontent.com/pulibrary/pulfa-extras/master/exist-1.4.3-configured.tgz]

Please download the custom Solr installation from [https://raw.githubusercontent.com/pulibrary/pulfa-extras/master/solr.tgz]

Copy these into the `local_files/pulibrary.pulfa` directory.

### Example Playbook

```yaml
- hosts: localhost
  roles:
    - role: pulibrary.pulfa
```

### Notes
_To be drafted_
