# desafio-docker-microsservicos
Repositório de configurações para configurar e deployar serviços na nuvem com docker, nginx e linux na AWS

- install-docker-ubuntu.sh - script de instalação do docker em container Ubuntu
- banco.sql - script de geração de tabela para a prova de conceito
- dockerfile - configuração do container de proxy
- nginx.conf - configuração do balanceador de carga nginx.
  - substituir os IPs dos nós com os "Public IPv4 Address"
  - configurar firewall para liberar a porta 80 para HTTP
- index.php - página PHP com lógica de execução da prova de conceito.
  - substituir o IP do container da base de dados
