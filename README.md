# Fluker

## Descrição
Rede social desenvolvida em equipe com prazo curto e foco em entrega funcional. O objetivo era construir uma plataforma com funcionalidades essenciais — feed, chat, notificações e autenticação — como primeiro projeto colaborativo da equipe, aprendendo a entregar software funcionando sob restrição real de tempo.

## Status
Pausado

## Funcionalidades
- Autenticação — cadastro, login e logout
- Feed — criação e visualização de postagens
- Chat integrado — troca de mensagens entre usuários
- Notificações — alertas de novas interações

## Tecnologias
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Flask](https://img.shields.io/badge/flask-%23000.svg?style=for-the-badge&logo=flask&logoColor=white)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)

## Observações
- **MVP funcional** - desenvolvimento suspenso temporariamente por demandas prioritárias.
- **CSV como banco de dados** — escolha deliberada para eliminar a curva de setup de um banco relacional dentro do prazo disponível. Funcionou para o escopo, mas não escala e não suporta concorrência. Trade-off consciente entre velocidade de entrega e qualidade técnica.
- **Arquitetura monolítica** — toda a lógica centralizada em `app.py` para reduzir a carga cognitiva da equipe com níveis diferentes de experiência. Gera acoplamento que dificulta manutenção futura.
- **Melhorias previstas** — migração para banco de dados relacional (PostgreSQL), modularização do monólito, implementação de funcionalidade de recuperação de senha e reorganização geral da estrutura do projeto.
- **Deploy** — [fluker.pythonanywhere.com](https://fluker.pythonanywhere.com)