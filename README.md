# webServe-com-a-aws
Criando um Web serve com a aws

#Link para acesso liberado *44.211.120.11*

#VPC 
Foram escolhidas 2 regiões de disponibilidade para esse projeto 1a e 1b.

#SUBNETS
Foram riados 4 subnets, 2 públicas com o mesmo igw e 2 privadas cada uma com o seu Nat Igw.

#INSTÂNCIA
Temos uma EC2 conectada através de uma sub-netpublica em linux com o seguintes dados de usuário 
#I/bin/bash
sudo yum update -y
sudo yum install httpd -y
sudo systemctl start httpd
sudo systemctl enable http

grupo de segurança liberado porta 80 através do grupo de segurança com 0.0.0.0/00 tipo http

BUckets do Amazon S3
Buckets são objetos de armazenamento 
Tamanho quase ilimitado de dados não estruturados mas cada objeto pode ter no máximo 5TB, além disso 
você pode criar quantos objetos você quiser 






