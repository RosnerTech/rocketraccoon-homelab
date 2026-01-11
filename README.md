# 🏠 Homelab – Fase 1 | Infraestrutura Base

Este repositório documenta a **Fase 1 do meu Homelab**, com foco em infraestrutura, redes, containers e boas práticas DevOps.

O objetivo é criar um ambiente **realista, seguro e escalável**, servindo como laboratório prático e portfólio técnico.

---

## 📁 Estrutura do Repositório

```text
homelab/
├── docs/                     # Documentação das aplicações
│   ├── proxmox.md
│   ├── opnsense.md
│   ├── nginx-proxy-manager.md
│   ├── pihole.md
│   └── portainer.md
│
├── docker/                   # Docker Compose por aplicação
│   ├── gamora-proxy/
│   ├── mantis-pihole/
│   └── nebulosa-portainer/
│
├── scripts/                  # Scripts auxiliares
├── .gitignore
└── README.md
```

📌 **Toda a documentação detalhada das aplicações está centralizada na pasta `/docs`.**

---

## 🛠️ Tecnologias Utilizadas

### 🔹 Virtualização & Infraestrutura
[![Proxmox](https://img.shields.io/badge/Proxmox-E57000?style=for-the-badge&logo=proxmox&logoColor=white)](https://www.proxmox.com/en/)
[![OPNsense](https://img.shields.io/badge/OPNsense-D94F00?style=for-the-badge&logo=opnsense&logoColor=white)](https://opnsense.org/)

---

### 🔹 Containers & Orquestração
[![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)](https://www.docker.com/)
[![Docker Compose](https://img.shields.io/badge/Docker%20Compose-2496ED?style=for-the-badge&logo=docker&logoColor=white)](https://docs.docker.com/compose/)

---

### 🔹 Serviços do Homelab
[![Nginx](https://img.shields.io/badge/Nginx%20Proxy%20Manager-009639?style=for-the-badge&logo=nginx&logoColor=white)](https://nginxproxymanager.com/)
[![Pi-hole](https://img.shields.io/badge/Pi--hole-96060C?style=for-the-badge&logo=pi-hole&logoColor=white)](https://pi-hole.net/)
[![Portainer](https://img.shields.io/badge/Portainer-13BEF9?style=for-the-badge&logo=portainer&logoColor=white)](https://www.portainer.io/)

---

### 🔹 Ferramentas de Desenvolvimento
[![VS Code](https://img.shields.io/badge/Visual%20Studio%20Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)](https://code.visualstudio.com/)

---

## 🎯 Objetivo da Fase 1

- Construção da base do homelab
- Firewall dedicado e DNS controlado
- Proxy reverso com SSL
- Containers com dados persistentes
- Organização e padrão para evolução futura

---

## 🚀 Próximas Fases (Roadmap)

- 📊 Monitoramento (Grafana / Prometheus)
- 🤖 Automação com Ansible
- ☸️ Kubernetes (ambiente de estudos)
- 🔐 Zero Trust e segmentação por VLAN

---

## 👤 Autor

**Rosner Pelaes Nascimento**  
📧 rosner@rosnertech.com.br | ros.tecinfo@gmail.com  
🌐 https://blog.rosnertech.com.br
