# TFE_aws_external
TFE installation with PostgreSQL and external installation



# TODO
- [ ] Create an AWS RDS PostgreSQL
- [ ] create a virtual machine in a public network with public IP address.
    - [ ] use standard ubuntu 
    - [ ] firewall inbound are all from user building external ip
    - [ ] firewall outbound rules
          postgresql rds
          AWS bucket          
- [ ] Create an AWS bucket
- [ ] create an elastic IP to attach to the instance
- [ ] transfer files to TFE virtual machine
      - airgap software
      - license
      - TLS certificates
      - Download the installer bootstrapper
- [ ] install TFE
- [ ] Create a valid certificate to use 
- [ ] point dns name to public ip address

# DONE
- [x] build network according to the diagram
- [ ] test it manually


