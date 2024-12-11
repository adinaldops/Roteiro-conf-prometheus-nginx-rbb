Roteiro de Configuração RBB Prometheus e Nginx
Esse roteiro  foi elaborado para adaptar o Nginx com ajustes de segurança,  junto ao Promtheus, disponibilizado no Github da RBB.
Testes, Configurações, Certificados  etc.  foram utilizados os seguintes softwares/ferramentas: Docker-compose, Openssl, apache2-utils e SO ubuntu Server( Caso for utilizar distribuições Linux e ferramentas diferentes, devem adaptar ao seu cenário) 
Certificados dos clientes devem ser concatenados em um único arquivo .crt ou .pem
Comando para concatenar:  cat  cert_dataprev.crt  cert_bndes.crt cert_cnpq.crt >> certificado_client.crt
Ou editar o arquivo certificado_client.crt e cola a chave publica do certificado do client
