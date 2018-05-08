# Ansible Role: Filebeat for Elastic
=========
[![Travis](https://img.shields.io/travis/kharkevich/ansible-elastic-filebeat.svg)](https://travis-ci.org/kharkevich/ansible-elastic-filebeat) [![Ansible Downloads](https://img.shields.io/ansible/role/d/24853.svg)](https://galaxy.ansible.com/kharkevich/elastic-heartbeat/) [![Ansible Role](https://img.shields.io/ansible/role/24853.svg)](https://galaxy.ansible.com/kharkevich/elastic-heartbeat/)

An Ansible Role that installs [Filebeat](https://www.elastic.co/products/beats/filebeat) on RedHat or Debian family distributives.

## Requirements

None.

## Role Variables

All available see in `defaults/main.yml`.

## Dependencies

None.

## Example Playbook

    - hosts: all
      roles:
        - kharkevich.filebeat
      vars:
        kibana_host: "http://kibana.example.com:5601"
        elasticsearch_hosts:
      	  - elastic0.example.com:9200
      	  - elastic1.example.com:9200

## License

Apache

## Author Information

This role was created by [Aliaksandr Kharkevich](https://github.com/kharkevich)
