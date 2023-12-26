## ansible run command##

ansible-playbook -i hosts -e "username=<username> domainname=<domainname> portno=8080" --private-key passfile.pem application.yml -vvv

## springboot run command ##
__ default port will be 8080

mvn spring-boot:run

