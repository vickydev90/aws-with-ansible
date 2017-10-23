The playbook should be run as:

$ ansible-playbook createec2instance.yml –extra-vars volume-size=30 -e instance_type=t2.micro -e region=us=west-1 -e keypair=my.pem -e count=1 
