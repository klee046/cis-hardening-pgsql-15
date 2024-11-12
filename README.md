Ansible Role kn-cis-pg-15
========================

Ansible Role for PostgreSQL 15 Hardening accordingly to CIS v1.1.0 - 11-7-2023 Benchmarks

Usage: 

    sudo ansible-playbook -v kn-cis-pg-15/site.yml 


Test single Benchmark:

    sudo ansible-playbook kn-cis-pg-15/tests/test.yml -t rule_3_1_9

