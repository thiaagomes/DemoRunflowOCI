# 🚀 Integração OCI com Runflow
Este repositório contém um Lab prático de OCI, criado para demonstrar, de forma simples e progressiva, como provisionar uma máquina virtual através de um script terraform (Resource Manager) com SDK Runflow em modo self-host.


---

## 🎯 Objetivo

Ao final deste hands-on, você terá provisionado: 

- Uma VCN publica
- Uma subnet publica
- Internet Gateway, route table e security list
- Uma VM Ubuntu 22.04
- Docker e Docker Compose instalados automaticamente
- Firewall local da VM aberto para SSH, HTTP, HTTPS e porta do Runflow
- Pagina de status em `http://IP_PUBLICO`
- Porta publica do Runflow em `http://IP_PUBLICO:3000`

---

## ⚙️ Configuração

### 1. Oracle Cloud Infrastructure

1. Acesse [https://cloud.oracle.com/] e faça login
2. Acesse o canto superior direito "PROFILE" →  Identity Domain →  Compartments = "Create Compartment"
3. Após criação do Compartment, vá no menu principal no canto superior esquerdo → Developer Services → Resource Manager → Stacks → Create Stack:

    3.1 - ![alt text](img/image.png)
    3.2 Envie o arquivo : ....