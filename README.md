# ☁️ Computação e Redes no Microsoft Azure

Este repositório contém um resumo aprofundado sobre os principais conceitos de **computação em nuvem** e **infraestrutura de redes** utilizando a plataforma **Microsoft Azure**. É voltado para estudantes, iniciantes na nuvem e profissionais que desejam entender como os recursos de computação e redes se integram no ecossistema Azure.

---

## 📌 Índice

- [1. O que é o Microsoft Azure](#1-o-que-é-o-microsoft-azure)
- [2. Fundamentos da Computação em Nuvem](#2-fundamentos-da-computação-em-nuvem)
- [3. Modelos de Serviço: IaaS, PaaS, SaaS](#3-modelos-de-serviço-iaas-paas-saas)
- [4. Principais Serviços de Computação no Azure](#4-principais-serviços-de-computação-no-azure)
- [5. Arquitetura de Redes no Azure](#5-arquitetura-de-redes-no-azure)
- [6. Serviços de Rede no Azure](#6-serviços-de-rede-no-azure)
- [7. Segurança em Computação e Redes](#7-segurança-em-computação-e-redes)

---

## 1. O que é o Microsoft Azure

O **Microsoft Azure** é a plataforma de **computação em nuvem** da Microsoft, com presença global em **mais de 60 regiões**, fornecendo serviços em diversas categorias como computação, rede, armazenamento, IA, DevOps e segurança. Ele permite:

- Criar e escalar máquinas virtuais.
- Armazenar dados com segurança.
- Executar aplicações web ou containers.
- Integrar redes locais com a nuvem.
- Automatizar e monitorar recursos.

---

## 2. Fundamentos da Computação em Nuvem

A computação em nuvem oferece acesso sob demanda a recursos computacionais via internet. Os principais conceitos são:

| Conceito            | Definição |
|---------------------|-----------|
| **Elasticidade**     | Capacidade de escalar automaticamente conforme a demanda. |
| **Alta disponibilidade** | Mínima interrupção de serviços. |
| **Escalabilidade**    | Ajuste de recursos horizontal (mais máquinas) ou vertical (mais potência). |
| **Pagamento sob demanda** | Você paga apenas pelo que consome. |
| **Redução de custos operacionais** | Sem necessidade de investir em hardware físico. |

---

## 3. Modelos de Serviço: IaaS, PaaS, SaaS

| Modelo | Descrição | Responsabilidade do usuário | Exemplo Azure |
|--------|-----------|-----------------------------|---------------|
| **IaaS** (Infrastructure as a Service) | Infraestrutura virtualizada (rede, VMs, armazenamento) | Instalação e manutenção do sistema operacional e apps | Azure Virtual Machines |
| **PaaS** (Platform as a Service) | Plataforma pronta para desenvolvimento e deploy | Código da aplicação | Azure App Services, Azure SQL |
| **SaaS** (Software as a Service) | Software pronto para uso via navegador | Nenhuma | Microsoft 365, Power BI |

---

## 4. Principais Serviços de Computação no Azure

### 🔹 Azure Virtual Machines (VMs)
- Instância virtual de servidor.
- Pode rodar Windows, Linux, Java, Python, .NET etc.
- Ideal para: simular servidores, hospedar bancos de dados, fazer testes.

### 🔹 Azure App Service
- Serviço de hospedagem gerenciada para aplicações web.
- Suporta CI/CD com GitHub, Azure DevOps.
- Escalabilidade automática.

### 🔹 Azure Kubernetes Service (AKS)
- Orquestração de containers usando Kubernetes.
- Permite implantar clusters de forma simplificada.

### 🔹 Azure Functions
- Executa código em resposta a eventos (serverless).
- Usa linguagens como JavaScript, C#, Python.

### 🔹 Azure Virtual Desktop
- Infraestrutura de desktop remoto.
- Permite acessar sistemas Windows em nuvem.

---

## 5. Arquitetura de Redes no Azure

### 🔹 Azure Virtual Network (VNet)
- Equivalente a uma rede local no Azure.
- Pode conter várias sub-redes, NSGs, roteadores e gateways.

### 🔹 Sub-redes (Subnets)
- Dividem a VNet em segmentos lógicos.
- Permitem aplicar políticas de segurança específicas.

### 🔹 Endereçamento IP
- IPs públicos: acessíveis pela internet.
- IPs privados: internos à rede virtual.

### 🔹 NSG (Network Security Group)
- Controla tráfego de entrada e saída com regras baseadas em IP, porta e protocolo.

### 🔹 Azure DNS
- Gerencia domínios e resolve nomes dentro da VNet.

---

## 6. Serviços de Rede no Azure

| Serviço                  | Descrição |
|--------------------------|-----------|
| **Azure Load Balancer** | Balanceia tráfego TCP/UDP entre VMs. |
| **Azure Application Gateway** | Load balancer de camada 7 (HTTP/S), com WAF integrado. |
| **Azure VPN Gateway**    | Cria túneis criptografados entre redes on-premises e o Azure. |
| **Azure ExpressRoute**   | Conexão privada e dedicada entre o data center e o Azure. |
| **Azure Bastion**        | Acesso remoto seguro a VMs sem expor IP público. |
| **VNet Peering**         | Conecta duas VNets com alta performance. |

---

## 7. Segurança em Computação e Redes

### 🔐 Boas Práticas

- Use **Azure Defender** para proteção de recursos.
- Habilite **DDoS Protection Standard** para mitigar ataques.
- Utilize **Azure Key Vault** para armazenar segredos e chaves.
- Controle de acesso com **Azure Role-Based Access Control (RBAC)**.
- Ative **MFA (Autenticação Multifator)** via Azure Active Directory.

---
