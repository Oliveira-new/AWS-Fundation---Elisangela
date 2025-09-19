# AWS-Fundation---Elisangela
Repositório do curso de formação AWS Cloud Foundations
Entreda do desafio Instancias EC2 contendo um fluxograma utilizando o draw.io.

O fluxogrma é a presentatividade de geração de arquivos para enviar para o Banco Central
Os dados (movimentações e informações de clientes, contas e saldos) estão em um banco de dados SQL Server On Primise, que é alimentado por um sistema de Contas Correntas. 
Essas informações são enviadas para ser armazenado em um S3 na AWS através de um ETL.
Na AWS, o Lambda é responsavel de processar o arquivo, enviar as informações para um banco de dados RDS, que faz a geração do arquivos em formato conforme exigencia do Banco Central.
