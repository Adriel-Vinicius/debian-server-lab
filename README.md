<h1>Debian Server Lab</h1>

Laboratório pessoal de infraestrutura utilizando Debian 12 (Bookworm) em ambiente minimalista (sem interface gráfica), com foco em:

- Administração de servidores Linux

- Segurança básica

- Containerização

- Execução de APIs e bots

- Backend e banco de dados

- Estudos de redes

---

<h2>Objetivo</h2>

- Construir um servidor enxuto, estável e seguro para:

- Hospedagem de aplicações próprias

- Execução de bots

- Backend de APIs

- Banco de dados local

- Ambiente de experimentação controlado

---

<h2>Arquitetura</h2>

Sistema operacional: Debian 12 (NetInstall)
Modo: Minimal (sem interface gráfica)
Acesso remoto: SSH
Gerenciamento de pacotes: APT

---

<h2>Stack principal:</h2>

- Nginx

- Node.js

- Python

- Docker

- PostgreSQL / SQLite

- Git

- UFW

- PM2 / Supervisor

- Cron

---

<h2>Segurança Implementada</h2>

- Atualização inicial do sistema

- Firewall configurado (UFW)

- SSH habilitado

- Login root desabilitado via SSH

- Uso de sudo para privilégios administrativos

- Sistema sem interface gráfica

---

<h2>Estrutura do Projeto</h2>

docs/        → Documentação e diagramas
setup/       → Scripts de configuração inicial
docker/      → Configuração de containers
nginx/       → Configuração do servidor web
scripts/     → Automação e manutenção

---

<h2>Instalação Base</h2>

Após instalar o Debian:

sudo apt update && sudo apt upgrade -y
sudo apt install git curl ufw

---

<h2>Documentação Completa</h2>

A documentação detalhada está disponível em:

/docs/Guia Prático de Infraestrutura Linux com Debian e OpenWRT.pdf

ou

[Guia Prático de Infraestrutura Linux com Debian e OpenWRT (PDF)](https://github.com/Adriel-Vinicius/debian-server-lab/blob/main/docs/Guia%20Prático%20de%20Infraestrutura%20Linux%20com%20Debian%20e%20OpenWRT.pdf)

---

<h2>Finalidade</h2>

Este projeto faz parte do meu desenvolvimento como estudante de Análise e Desenvolvimento de Sistemas, com foco em infraestrutura, backend e administração Linux.
