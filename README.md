# Ansible role: elasticsearch
Installs and configures jenkins.

## Requirements
None.

## Role Variables
|Key|Type|Description|Default|
|:--|:---|:----------|:------|
|elasticsearch_port|Integer||9200|
|elasticsearch_host|String||.0.0.0|

## Dependencies
+ [java](https://github.com/shomatan/ansible-java.git)

## Example playbook

```yaml
- hosts: all
  roles:
    - { role: elasticsearch }
```
