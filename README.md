# Guia de Comandos de Rede (CMD)

Este repositório reúne os principais comandos utilizados no Prompt de Comando (CMD) para diagnóstico e análise de redes.

Objetivos:

- Aprender comandos de rede
- Entender protocolos TCP/IP
- Desenvolver conhecimentos em infraestrutura
- Servir como material de consulta

## Comandos

- ipconfig
- ping
- tracert
  
- # 1. IPConfig

## O que é?

O comando `ipconfig` exibe todas as configurações de rede do computador.

## Comando

Mostra:

- Nome do computador
- Adaptador de rede
- IPv4: É o endereço da máquina na rede. Cada dispositivo possui um IPv4 único dentro da rede local.
- IPv6: É a nova versão do protocolo IP. Foi criado porque o IPv4 possui quantidade limitada de endereços.
- Gateway: É o endereço do roteador. Todo acesso à internet passa pelo Gateway.

Quando utilizar?
Descobrir seu IP
Verificar Gateway
Descobrir problemas de rede
Conferir DNS
Diagnosticar conexão

---

# 2. ping.md

## O que é?

O Ping testa a comunicação entre seu computador e outro dispositivo.

Utiliza o protocolo ICMP.

## Sintaxe
ping + endereço

Exemplo

ping google.com

ou

ping 8.8.8.8
Ping contínuo
ping -t google.com

O computador continuará enviando pacotes até você pressionar:

CTRL + C
Informações exibidas

Tempo
TTL
Pacotes enviados
Pacotes recebidos
Pacotes perdidos

Quanto menor, melhor.

Quantidade máxima de roteadores que um pacote pode atravessar.

Quando utilizar?
Verificar internet
Testar estabilidade
Descobrir perda de pacotes
Testar latência
Sites para testar

Google
ping google.com

Cloudflare
ping 1.1.1.1
- DNS
- DHCP
- Endereço MAC
