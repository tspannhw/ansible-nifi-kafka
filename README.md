# ansible-nifi-kafka

This is a set of roles and playbooks for deploying Kafka and NiFi on EC2.

## Roles

- Common (limits, Java, JDK)
- Zookeeper
- Kafka
- NiFi

## Playbooks

There are 3 playbooks included. Two of these are for Kafka and one for NiFi.

They can be executed as follows (assuming the machines have already been provisioned):

```sh
ansible-playbook -i ./ec2.py kafka1.yml
ansible-playbook -i ./ec2.py kafka2.yml
ansible-playbook -i ./ec2.py nifi.yml
```

## License

Copyright &copy; 2018 Joey Frazee. ansible-nifi-kafka is released under the [Apache License Version 2.0](LICENSE).
